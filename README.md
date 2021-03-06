# mintScrollbar.js
Just another jQuery scrollbar plugin.

### Demo

![Demo](http://chart.apis.google.com/chart?cht=qr&chs=200x200&chl=http%3A//cople.github.io/mintScrollbar.js/&chld=H|0)
[Demo](http://cople.github.io/mintScrollbar.js/)

### Usage

```js
$(".demo").mintScrollbar();
```

### Options

```js
{
    onChange: null, // function
    axis: "auto", // "x", "y", "both", "auto"
    wheelSpeed: 120,
    disableOnMobile: true
}
```

### Methods

```js
$(".demo").data("mintScrollbar").resize();
$(".demo").data("mintScrollbar").update();
$(".demo").data("mintScrollbar").destroy();


$(".demo").data("mintScrollbar").scrollTo(destX, destY);
$(".demo").data("mintScrollbar").scrollToX(destX);
$(".demo").data("mintScrollbar").scrollToY(destY);


$(".demo").data("mintScrollbar").scrollBy(deltaX, deltaY);
$(".demo").data("mintScrollbar").scrollByX(deltaX);
$(".demo").data("mintScrollbar").scrollByY(deltaY);

$(".demo").data("mintScrollbar").scrollByLines(lines);
$(".demo").data("mintScrollbar").scrollByPages(pages);
```