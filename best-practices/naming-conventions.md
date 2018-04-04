# Naming Conventions

## Widgets

Generally, if there is on only one Widget in an app, just use the full name



`txtMarkDown`

# Naming conventions for variables, constants, functions and classes

**TL;DR:** Use ***lowerCamelCase*** when naming constants, variables and functions and ***UpperCamelCase*** (capital first letter as well) when naming classes. This will help you to easily distinguish between plain variables / functions, and classes that require instantiation. Use descriptive names, but try to keep them short.

**Otherwise:** Javascript is the only language in the world which allows to invoke a constructor ("Class") directly without instantiating it first. Consequently, Classes and function-constructors are differentiated by starting with UpperCamelCase.

#### Code Example
```javascript
  // for class name we use UpperCamelCase
  class SomeClassExample {}
    
  // for const names we use the const keyword and lowerCamelCase
  const config = {
    key: 'value'
  };

  // for variables and functions names we use lowerCamelCase
  let someVariableExample = 'value';
  function doSomething() {}
```


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



