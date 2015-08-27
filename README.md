# Easy-parallaxe

## Synopsis
Easy Parallaxe is a jQuery plugin designed to parallax effects as simply as possible, on HTML Elements or background images.

## Get started
Load easy-parallaxe.js
```html
<script src="easy-parallaxe.js"></script>
```

Init parallaxe on your HTML element
```js
$(document).ready(function(){
    $('.myElement').parallaxe();
});
```

## Configuration
You can specify multiple options :
* type
* direction
* speed
```js
$(document).ready(function(){
    $('.myElement').parallaxe({
        speed: 2,
        direction: 'top',
        type: 'element'
    });
});
```


