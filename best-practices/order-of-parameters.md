# Ordering of Widget properties

Widget properties take the form

```js
property: parameter,
```

Note commas separate properties as shown:

```js
left: 8,
```

Properties may be listed on multiple lines or on one line:

```js
let txiMarkDown = new TextInput({
  left: 8, right: 8, top: 'prev() 10',
  height: 100,
  message: 'Enter URL here...',
  type: 'multiline',
  text: INITIAL_TEXT
}).appendTo(ui.contentView);
```

For readability, this book sets all positioning properties on one line, immediately afgter the `let` statement

```js
left: 8, right: 8, top: 'prev() 10'
```

Dimensions are shown next

```js
height: 100,
```

You might list the rest of properties in order of importance, although that might be difficult to decide upon.

