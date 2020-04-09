# Adding JavaScript to a webpage

With the console we can immediately run a piece of JavaScript code, but as soon
as we refresh the browser we will loose everything what we have written. For
webpages there is another solution to run JavaScript code, we can insert the
script into the html document.

## `<script>` tag

We will need the `script` html tag to associate a JavaScript code with the
webpage.

The easiest way is to simply put our JS code between the opening and closing tag

```html
<script>
  console.log('Hello World!');
</script>
```

If you insert the code above into your html file, and open the page you will see
the message in the console.

### Separated *.js* file

In bigger projects the script and html content are usually separated. You can do
this too. The script tag has another attribute called `src` which should point
to a javascript file:

```html
<script type="text/javascript" src="./script.js"></script>
```

`./` before the file name means that the html and js files are in the same
folder

## Where to put the `script` tag

Its place does matter, the browser will try to understand and execute the script
as soon as it finds it. Usually we add the `<script>` tag right before the
closing `</body>` tag, so the browser can display the html content before starts
working on the script.

Now add a script to an html document from within you print the sum of two
numbers.
