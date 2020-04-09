---
layout: default
---
# JavaScript Cheat Sheet

## Variables

```js
let number = (5 + 7.2 - 0.5) % 10; // use () to change the order of the operation
let name = 'Peter';
let text = 'My name is Adam';
text = 'My name is ' + name; // if a variable defined don't use let
text = `My name is ${name}`;
```

## Comparison and booleans

```js
let smaller = 5 < 10;
let name = 'Adam';
let bigger = 'this is longer'.length > name.length;
let same = 'Adam' === name; // !== for not equals
let age = 30;
let height = 180;
let tallAdult = age >= 18 && height >= 180; // || for or
```

## Conditions

```js
if(comparisonOrBoolean) {
  // Do something if the comparison or boolean is true
} else {
  // Do something if it is false
}
```

## Loops

```js
for(let i = 0; i < 100; i++) { // do 100 times
  console.log(`I won't cheat on the exam again.`);
}

let names = ['Peter', 'Adam', 'Joe'];

names.forEach((name) => { // for each item in names
  console.log(`Welcome, dear ${name}!`); // print out the item
})
```

## Script tag

```html
    ...
    <script src="script.js"></script>
  </body>
</html>
```

## jQuery

```html
    ...
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="script.js"></script>
  </body>
</html>
```

```js
$('h1').text('Coronavirus outbreak!'); // change the text
let backgroundColor = $('.red').css('background-color'); // get the color into a variable
$('.red').css('background-color', 'blue'); // change the color
$('h1').toggleClass('red'); // add or remove class
$('.add').on('click', (event) => { // clicking on .add class-ed elements
  $('.container').append('<p>A new paragraph</p>'); // add a new element into .container
});
```
