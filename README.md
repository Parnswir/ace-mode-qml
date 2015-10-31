# ace-mode-qml
An Ace Edit Mode for [QML](https://en.wikipedia.org/wiki/QML)


## Usage

### Load `ace-mode-qml.js` after Ace, like so:

```html
<!-- ... -->
<script src="ace.js"></script>
<!-- Add this line: -->
<script src="mode-qml.js"></script>
<!-- ... -->
```

### Initialize the Edit Mode:

```js
var editor = ace.edit("editor");
editor.getSession().setMode("ace/mode/qml");
```

### That's it! Enjoy syntax highlighting for QML :smiley:
