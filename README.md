# ace-mode-qml
An Ace Edit Mode for [QML](https://en.wikipedia.org/wiki/QML)


## Usage

1. Load `ace-mode-qml.js` after Ace, like so:

```html
<!-- ... -->
<script src="ace.js"></script>
<script src="ext-language_tools.js"></script>
<!-- ... -->
<!-- Add this line: -->
<script src="mode-qml.js"></script>
<!-- ... -->
```

2. Initialize the Edit Mode:

```js
MODE_PATH = "ace/mode/qml"
mode = new ace.require(MODE_PATH).Mode
session = new ace.EditSession("your content", MODE_PATH)
```

That's it! Enjoy syntax highlighting for QML :)
