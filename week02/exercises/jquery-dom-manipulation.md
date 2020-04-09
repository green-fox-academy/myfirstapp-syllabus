---
layout: default
---
# Manipulate the DOM with jQuery

With jQuery you can not only change elements' style but also creating new ones
or simply deleting existing elements.

```js
$('body').append(
  '<h1>Hello World!</h1>'
);
```

With the previous snippet you can insert a new `h1` at the end of the `body`
element.

You might want to read [the documentation][jquery-append] about the `.append`
method to solve the next exercises

## Exercise 1

- Get your solution of the [fourth exercise][fourth-html-exercise] from the html
  day
- Create and include a `scripts.js` file just like before
- Create an array with random names and yours
- Using `forEach` to add each name to the `<ul>` list
- (Optional) Your name should be bold

## Exercise 2

- Work with the same files as in the previous exercise
- Create this object:
  ```javascript
  let additionalBlock = {
    title: "Added with javascript",
    text: "This block was added using JavaScript's jQuery library. How awesome!"
  };
  ```
- Add a new block at the end of the page, the `title` should be in a heading,
  the `text` should be in a paragraph block

[fourth-html-exercise]: http://stayathome-syllabus.greenfox.academy/week01/exercises/lists-and-texts.html
[jquery-append]: https://api.jquery.com/append/
