
AnimatedClick
=============

**AnimatedClick** is a custom web component that creates an animated effect around a click event. You can specify the type of effect (bubbles or ripples), animation speed, and color. It also allows you to edit the element's styles and apply changes on the fly.

Installation
-----------

You can install this component by cloning this repository:
```
git clone https://github.com/FredUA/animated-click.git
```

Usage
-----

To use AnimatedClick in your project, follow these steps:

1.  To use AnimatedClick, simply include the `animated-click.js` script in your HTML file:
```
<script type="module" src="./animated-click.js"></script>
```
2.  Then, you can use the `animated-click` element anywhere in your HTML file:
```
<animated-click></animated-click>
```
3.  By default, the element will use the `bubble` animation type, a `currentColor` color, and an animation speed of `500ms`. You can customize these settings by passing attributes to the element:
```
<animated-click type="ripple" color="blue" speed="1000"></animated-click>
```

The **`type`** attribute determines the type of animation effect (bubble or ripple). The **`color`** attribute determines the color of the animation effect. The **`speed`** attribute determines the speed of the animation effect in milliseconds.

API
---

### Properties
`type` (string): The type of animation effect. Can be bubble or ripple.

`color` (string): The color of the animation effect. Can be any valid CSS color value.

`speed` (number): The speed of the animation effect in milliseconds.

### Methods
AnimatedClick provides no public methods.

### Events
AnimatedClick provides no events.

Examples
--------

Here's an example of using the `animated-click` element:

```
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<script src="index.js" type="module" defer></script>
	<title>Animated click</title>
</head>

<body>
	<animated-click type="bubble" color="yellow" speed="350"></animated-click>
</body>

</html>
```

Browser Support
---------------
AnimatedClick is designed to work in modern browsers that support Custom Elements v1, Shadow DOM v1, and ES2015. This includes Chrome 63+, Firefox 63+, Safari 10.1+, and Edge 79+. For legacy browser support, consider using a Custom Elements polyfill such as [webcomponents.js](https://github.com/webcomponents/webcomponentsjs).

License
-------

AnimatedClick is licensed under the MIT License.