# Naming Conventions

## Widgets

Generally, if there is on only one Widget in an app, just use the full name

```js
// Create the activity indicator centered in the page
let activityIndicator = new ActivityIndicator({
  centerX: 0,
  centerY: 0
}).appendTo(ui.contentView);
```

```js
let txiMarkDown = new TextInput({
  left: 8, right: 8, top: 'prev() 10',
  height: 100,
  message: MESSAGE,
  type: 'multiline',
  text: INITIAL_TEXT
}).appendTo(ui.contentView);
```

| Widget | Prefix | Example |
| :--- | :--- | :--- |
| **TextInput** | **txi** | **txiMarkDown** |
| **TextView** | **txv** | ** txvCountry** |
| **Button** | **btn** | **btnReadFile** |



