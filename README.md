# Beautiful Images

Jquery script to select placeholder images for elements.

## Usage

First, include all the dependencies. All the files that you need (apart from jQuery) are in the `dist\` directory:

```html
<script src="jquery.beautiful-images.js"></script>
```

This will load placeholder images on all elements with the `beautiful-image` class

Or run `beautifulImage(container, size, variation)` on the element you want with optional size and variation of the images you want to load.

```html
<div id="sloth"></div>
<script>
  $( document ).ready(function() {
    beautifulImage("#sloth",500,100);
});
</script>
```
