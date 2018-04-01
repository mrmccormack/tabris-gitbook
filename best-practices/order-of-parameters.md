# Ordering of Widget properties

Widget properties take the form

```js
property: parameter,
```

Note commas separate properties,  
Example:

```js
left: 8,
```

Properties may be listed on multiple lines or on one line as shown.

```js
let txiMarkDown = new TextInput({
  left: 8, right: 8, top: 'prev() 10',
  height: 100,
  message: MESSAGE,
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



