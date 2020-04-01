---
layout: default
---
# Images everywhere

## Help

- [Questions to this exercise](http://askbot.greenfox.academy/questions/tags:images/)

## The Overview

- Create a new pen on Codepen to work with
- You'll create this step by step (but you can give it a try on your own):
  - images used:
    - https://cdn.pixabay.com/photo/2020/03/26/05/07/travel-4969279_1280.jpg
    - https://cdn.pixabay.com/photo/2020/03/27/18/01/switzerland-4974469_1280.jpg
    - https://cdn.pixabay.com/photo/2020/03/27/21/26/costa-rica-4975038_1280.jpg
  - The width of them are set to `300px` with `50px` margin
  - When the mouse over `400px` with `0` margin

![links](assets/images-02.png)

## Step by Step

To place a simple image on a webpage, use the `img` tag in HTML with the `src` attribute that contains the image's location. You can use any image that is available on the internet, just pay attention to the rights of the image (It may not be free to use).

```html
<img src="https://website.com/image.jpg">
```

> Note: the urls in the examples are just examples, they don't point to actual images

You can even use your own images if you upload them to an image sharing website for example [Imgur](https://imgur.com). Click on the New Post on the top left and Choose a Photo from your computer. When the image appears, right click on the image and select Copy Image Address. You can insert this into the `src` attribute on Codepen. Or you can look for free images from any website and copy the address the same way. [Pixabay](https://pixabay.com/) contains a lot of beautiful free images you can use.

If the image is not loaded for some reason (the url changed or the image is removed) you can show a replacement text which also helps for viewers who just can't see the pictures (eg. reading the website for people who can't see). This text can be set with the `alt` attribute.

```html
<img src="https://website.com/skyscrapers.jpg" alt="Beautiful tall buildings touching the sky">
```

### Place 3 images and set the `width` to `300px`

- The example uses these images:
  - https://cdn.pixabay.com/photo/2020/03/26/05/07/travel-4969279_1280.jpg
  - https://cdn.pixabay.com/photo/2020/03/27/18/01/switzerland-4974469_1280.jpg
  - https://cdn.pixabay.com/photo/2020/03/27/21/26/costa-rica-4975038_1280.jpg

![links](assets/images-01.png)

> Note: if your screen is smaller than 900px-s, they won't fit in one row, then try to set the width to a smaller number

Remember, the `hover` pseudo-class can be used on images too.

### Make the `img` tags bigger if the mouse is over it

- The example is set to `400px`

![links](assets/images-03.png)

Try moving the mouse over each of them. It works just like with the links. Moving over the first image, that becomes bigger, moving to the next the first one shrinks back and the second becomes big.

It can be a little annoying that the rest of the images move down and the third one a little to the right. That's because the `height` of the whole line changes too. By default the browser wants to keep to image's original aspect ratio, so it is not weird looking. If you set both the `width` and `height` then you can get a twisted picture.

So instead fixing the `height`, you can use a `margin` that is removed when the image is bigger.

### Set `50px` margin to the `img` tag and `0` to it's `hover`ed version

![links](assets/images-02.png)

Now the other (not hovered) images stay in place.
