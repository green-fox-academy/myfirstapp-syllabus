# A complicated form

## Help

- [Questions to this exercise](http://askbot.greenfox.academy/questions/scope:all/sort:activity-desc/tags:complicatedform/page:1/)

## The Overview

- Create a new pen on Codepen to work with
- This exercise uses very little styling the focus is on trying out `form` related elements
- Create the new HTML structure and apply the necessary styles

![lists and texts](assets/06.png)

## Building blocks

### Other form inputs

You'll need `radio` buttons and `checkbox`es in this exercise along with a `textaera`.

The `radio` and the `checkbox` as another `type` of `input`. All form inputs need a `name` property (that we didn't use before) so the user's input can get a codename. This is useful when submitting the form and the data arrives at the web application, but it is also needed for the `radio`s to be grouped together (so when you click on one the previously selected gets deselected).

```html
<input type="radio" name="gender" id="male">
<label for="male">Male</label>
<input type="radio" name="gender" id="female">
<label for="female">Female</label>
```

### Text through the border?

The arrangement in this form uses `fieldset`s to group the `input`s. [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset) you can find a really good example how it works. They look exactly like this without styling.

### Step by Step Guide

- Create a `form`
- Create `fieldset`s for each section and for the form
- Create the `legend`s for them
- Create the `input`s and the `button`
