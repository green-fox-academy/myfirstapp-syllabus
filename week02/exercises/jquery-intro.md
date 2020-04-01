# Intro to jQuery

There are many common problems in a webpage and don't want to solve them again
and again. This is why we have frameworks and libraries which provide you these
solutions out of the box.

jQuery is a library which perfect for smaller pages, later on you would consider
to use a more robust framework like React or Angular.

jQuery makes the development faster and more effective. Since jQuery is a
collection of ready made methods, you need to insert it into your webpage.
How can you do that? Of course with the `<script>` tag.

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
```

## Syntax

With jQuery you get a new method `$` every jQuery action starts with
`$(selector)` where selector is a valid css selector. Then you can tell jQuery
what to do with the selected element. For example if you have an `<h1>` element
with an `id="title"` attribute, then you can change its text with:

```js
$('#ŧitle').text('My new title');
```

## Exercise

- Get your solution of the [first exercise][first-html-exercise] from the html
  day
- Create a `scripts.js` file in the same folder as the `index.html`
- Include `jQuery` and your script file at the end of the HTML file, before the closing `<body>` tag
  ```html
  ...
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
      <script src="scripts.js"></script>
    </body>
  </html>
  ```
- Add `id`-s to the 3 blue HTML element in the HTML file
  - eg. `id="fox-1"`, `id="fox-2"` ...
- Using JavaScript (written in the `scripts.js` file)
  - Change the text of the first blue box from `Velox` to `Macrotis`
  - Change the border color of the second from `blue` to `purple`
  - Change the background color of all 3 blue boxes to `yellow`

> **Hint**: you might need to know out [how to change the style][jquery-css]
> of an element with jQuery

## Exercise 2

- Get your solution of the [second exercise][second-html-exercise] from the
  html day
- Create and include a `scripts.js` file just like before
- Add different classnames to the 4 elements in the HTML file
- Let's create some variables with the following names and values:
  - color: purple
  - number: 10
  - word: cool
- Change the background color of the first box to purple, if the `color` is purple
- Change the text of the second
  - if the `number` is bigger than 100 to `whoah, that's a big number.`
  - otherwise `just a regular number, please.`
- Change the text to `Power of DOM` of the third if the `word` is cool, otherwise change the fourth one

[first-html-exercise]: https://github.com/green-fox-academy/stayathome-syllabus/blob/master/week01/exercises/velox-zerda-lagopus.md
[jquery-css]: https://api.jquery.com/css/
[second-html-exercise]: https://github.com/green-fox-academy/stayathome-syllabus/blob/master/week01/exercises/directions.md
