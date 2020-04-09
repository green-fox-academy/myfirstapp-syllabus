---
layout: default
---
# Basic building blocks in JavaScript

Now lets see how can we do complex applications with our variables and types

## Building blocks

There are 3 building blocks in programming science which can be used to build
any kind of application. One you know already, the assignment

```js
let variable = 12; // this is an assignment
```

Next you will get familiar with the other 2.

### Condition

You can make a piece of your code optional, with the `if` statement. It lets you
define a condition which your code depends on

```js
let myVariable = false;
if (myVariable === true) {
  console.log('The condition has been evaluated to true');
}
```

If you run the above code in the console or in a webpage you will see nothing in
the console. Please change something to see the desired message in the console.

Our `if` statement gives us more capabilities, we can tell what we want to do if
the given condition has been evaluated to false.

```js
let a = 7;
if (a < 5) {
  console.log(a / 2);
} else {
  console.log(a * 2);
}
```

Questions:

- What will be printed if we run the previous code snippet?
- What should be changed to get 1 printed to the console?

You can read more about the `if` statement in the [documentation][mdn-if]

### Loops

Sometimes you want to execute a piece of code several times. Like in the real
life when you want to move books from one shelf to another.

- you grab the book
- you move it to the other shelf
- you release the book

And you do this until you have books to move.

```js
let bookCount = 10;

for (let i = 0; i < bookCount; i++) {
  // here comes the code which moves the books
  // this block will be repeated bookCunt times
}
```

#### Exercises

- Create a loop which prints the numbers from 0-9.
- Change the previous loop to print the numbers from 1 to 10.
- Print the even numbers between 0 and 20.

## Functions

Usually there are many repeating code blocks in an application, when we want
to execute the same code but with different circumstances/environments. Just
imagine how you pay your bills. The steps are the same you just transfer
different amount to different bank accounts. So the amount and the bank
account are parameters of this activity. In programming languages these
activities are called functions.

```js
let payBill = (amount, beneficiary) => {
  // transfer amount money to the beneficiary
};
```

Within functions you can use the `return` keyword which will give back the
function's output. For example if you want to add 2 numbers, then you will need
the result as well:

```js
let add = (a, b) => {
  return a + b;  // the return keyword will give you back the result
};

console.log(add(1, 2)) // will print 3
```

### Exercise 1

Use your previous for loops and create a function which print the first **N**
numbers.

```js
printNumbersTill(20); // should print 1, 1, 2, ...., 20
printNumbersTill(15); // should print 1, 1, 2, ...., 15
```

### Exercise 2

Create a method which gets a name as parameter and then returns a greeting to
the specified person.

```js
getGreetingTo('Mark');              // Should not print to the console
console.log(getGreetingTo('Mark')); // Should print 'Hello Mark!'
```

## For loops and arrays

We need to iterate through arrays pretty often, what do you think how can you do
that? As you remember for loops execute something **N** times, so if we want to
print an array's values we will need to execute the loop `.length` times.

### Exercise 1

Create a method which gets an array as parameter and prints each value from it.

```js
printValues([0, 3, 6, 7, 9]); // prints the following lines:
//  0
//  3
//  6
//  7
//  9
```

This is how your solution should look like:

```js
let printValues = (array) => {
  for (let i = 0; i < array.length; i++) {
    console.log(array[i]);
  }
};
```

### `forEach`

Usually we try to avoid this `i` variable, it makes our code more complicated.
When we want to iterate through an array we have a special syntax for that.

```js
let myNumbers = [10, 20, 30, 50, 12];

// here we say, we want to do something with each item
myNumbers.forEach((number) => {
  // within the function I can tell what I want to do with the items
  console.log(number);
});
```

#### Exercise 2

Change your previous `printValues` function to use `forEach` loop.

[mdn-if]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else
