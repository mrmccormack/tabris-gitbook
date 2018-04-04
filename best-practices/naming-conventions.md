# Naming Conventions

## Widgets

Generally, if there is on only one Widget in an app, just use the full name



`txtMarkDown`


# variables, constants etc.

- This is nice (string literals or integer literals):

```js
const PI = 3.14;
const ADDRESS = '10.0.0.1';
```

>but...

```js
const myObject = {'key': 'value'};
const userSuppliedNumber = getInputNumber()

```

**NOTE:**
- Google JavaScript Style Guide says:
- Declare all local variables with either const or let. Use const by default, unless a variable needs to be reassigned. The var keyword must not be used.

---


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



`txtMarkDown`





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



| `Widget` | `Prefix` | `Example` |
| :--- | :--- | :--- |
| **`TextInput`** | **`txi`** | **`txiMarkDown`** |
| **`TextView`** | **`txv`** | **` txvCountry`** |
| **`Button`** | **`btn`** | **`btnReadFile`** |
| asdf | asdf | asdf |



