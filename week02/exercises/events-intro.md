---
layout: default
---
# Events & Event Listeners

So far you can create a website which has some elements and maybe after the page
has loaded you change something on it. This sounds cool, but still not enough.
The user might want to interact with your webpage. Do actions like clicking on a
button, save some data during sign up or simply like/share some content.

This is where we will need the events. Events are actions made by the user and
we want to respond to them somehow. Fortunately jQuery can help us in this. It
is pretty easy to listen to events with jQuery:

```js
$(selector).on(eventType, function);
```

Above, you have to use a valid css *selector* and one of jQuery's predefined
*eventTypes*. The most common *events* are `click` and `submit`. The last
parameter is the action you want to perform upon the user interacted with your
page.

## Exercise 1

- Create a webpage
- Add a button to the body
- Insert jQuery
- Add a script at the end of the body
  - Add an event listener to the button
  - Log 'Yeah, you clicked me' to the console when the user clicks on the button

## Exercise 2

- Add another button to the webpage
- When the user clicks on the second button change the first button's text

## Exercise 3

- Add a third button to the webpage
- When the user clicks on the last button, change the `background-color` of each
  button
