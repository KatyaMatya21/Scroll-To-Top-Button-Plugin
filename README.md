# Scroll-To-Top-Button-Plugin
jQuery plugin which adds scroll-to-top button on page

###Usage

First, add **up.css** and **up.js** to your page:

```html
<head>
...
<link rel="stylesheet" href="css/up.css">
...
<script src="up.js"></script>
</body>
```

Next, call plugin:

```js
// default options
var options = {
  class: '',
  positionY: 'bottom',
  positionX: 'left',
  text: 'Up',
  displayAlways: true
 };

new Up( options );
```

###Options

**class** - you can style button by yourself using custom class;

```
class: ''; //default
class: 'your-class'; 
``` 

**positionY**- top or bottom side of window;
```
positionY: 'bottom'; //default
positionY: 'top'; 
```

**positionX** - left or right side of window;
```
positionX: 'left'; //default
positionX: 'right';
```

**text** - you can write your text in this option; 
```
text: 'Up'; //default
text: 'Button';
``` 

**displayAlways**
```
displayAlways: true; //default  - button is always on a page;
displayAlways: false;  - button shows when user scroll page down for the window height;
```

###Dependencies
```
jQuery 1.7+
```

