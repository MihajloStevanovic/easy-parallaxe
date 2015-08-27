# asy-parallaxe

## Synopsis
Easy Parallax is a jQuery plugin designed to parallax effects as simply as possible, on HTML Elements or pictures funds.

## Started
Load easy-parallaxe.js
```js
YSLLaNuitDeLHomme.init({baseUrl:'/ysl/lndh/', locale:'en'});
```

Init parallaxe on your HTML element
```js
$(document).ready(function(){
    $('.myElement').parallaxe({
        speed: 2,
        direction: 'top',
        type: 'element'
    });
});
```

## Configuration
You can specify multiple options :
* type
* direction
* speed


