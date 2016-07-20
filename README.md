# Usage

To use, simple call on the required element i.e.

```js
if($('.contact-form').isOnScreen()) {
  // Display contact form/animate in/change user focus etc...
}
```

You can pass `x` & `y` offsets if you want the check to return true based on a
percent/factor amount of the element on screen i.e.

```js
$('.contact-form').isOnScreen(0.2, 0.2)
```

This would return true if 20% of the element was visible on the `x` and `y`
axises
