# Naming Conventions

# Tip and Tricks

- this is a tip 


## Widgets

Generally, if there is on only one Widget in an app, just use the full name

`txtMarkDown`

## Importing Tabrisjs Modules

The local require function is used to load and import another module. It accepts a module identifier string and returns whatever that module exports.

These can be placed in any order. But this book always arranges them in alphabetical order as shown. You may find with a lot of requires, this technique will make it easier to find, add and delete things.

```js
const { app, device, TextView, ui } = require('tabris')
```

# JavaScript Standard Errors

google search...

* [https://github.com/eslint/eslint/issues/5150](https://github.com/eslint/eslint/issues/5150)

```js
// No idea if that is important for this, but using brackets also suppresses the warning, although it's still returning the assignment.

// Arrow function should not return assignment
const a = (v) => v.b = 1
// passes
const a = (v) => (v.b = 1)
```

So, on setting theme snippet... the second one works without error

```js
  .on('select', ({ index }) => ui.statusBar.background = BACKGROUNDS[index])
  .on('select', ({ index }) => (ui.statusBar.background = BACKGROUNDS[index]))
```

# Use of comments

```js
/*
 * This is
 * okay.
 */

// And so
// is this.

/* This is fine, too. */

//comment           // ✗ avoid
// comment          // ✓ ok

/*comment*/         // ✗ avoid
/* comment */       // ✓ ok


// above comment - always... Atom Javascrip Prettier Standard doesn't allow inline comments, after code 
var foo = 'bar'
```

# Naming conventions for variables, constants, functions and classes

**TL;DR:** Use _**lowerCamelCase**_ when naming constants, variables and functions and _**UpperCamelCase**_ \(capital first letter as well\) when naming classes. This will help you to easily distinguish between plain variables / functions, and classes that require instantiation. Use descriptive names, but try to keep them short.

**Otherwise:** Javascript is the only language in the world which allows to invoke a constructor \("Class"\) directly without instantiating it first. Consequently, Classes and function-constructors are differentiated by starting with UpperCamelCase.

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

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

# variables, constants etc.

* This is nice \(string literals or integer literals\):

```js
const PI = 3.14;
const ADDRESS = '10.0.0.1';
```

> but...

```js
const myObject = {'key': 'value'};
const userSuppliedNumber = getInputNumber()
```

**NOTE:**

* Google JavaScript Style Guide says:
* Declare all local variables with either const or let. Use const by default, unless a variable needs to be reassigned. The var keyword must not be used.

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

# Naming Convention for Widget Prefixes
> Suggested:

|Widget| Prefix | Example |
|--|--|-- |
| *Button* | `btn` |`btnReadFile`
| *TextInput* | `txi` | `txiMarkDown` |
| *TextView* | `txv` |  `txvCity` |


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




