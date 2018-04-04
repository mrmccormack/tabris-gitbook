# Big Arrow Functions
>It’s Time to Embrace Arrow Functions

- https://medium.com/javascript-scene/familiarity-bias-is-holding-you-back-its-time-to-embrace-arrow-functions-3d37e1a9bb75

---


# Event Handling Style

Events may be shown in two ways.

## Events as part of declaration

```js
// button with event outside
let resetbutton = new Button({
    centerX: 0,
    top: 'prev() 10',
    text: '  Reset'

  })
.appendTo(ui.contentView);

// event outsite create new
resetbutton.on('select', () => {
console.log ('you pressed reset');
console.log (urlInput.text);
  let HTML_TEMPLATE =  '<!DOCTYPE html>\
<html>\
<title>Hello Strapdown</title>\
<xmp theme="united" style="display:none;">\
' + urlInput.text + '</xmp>\
<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>\
</html>'

 webView.html = HTML_TEMPLATE;
  })
```

## Events outside of declaration

This book always separates the event from the declaration for readability.

