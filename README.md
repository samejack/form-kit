[![npm version](https://badge.fury.io/js/jform.svg)](https://badge.fury.io/js/jform)

# jform jQuery Plugin

Web HTML Form Kit, convert JSON to form and auto fill field easily. ([Demo](http://samejack.github.io/jform/))

## Install by NPM Package

```shell
npm install jform
```

## HTML Input Support List

* Text Input
* Textarea
* Radio
* Check Box
* Check Box (Multiple)
* Select
* Select (Multiple)

## How to use

```javascript
// get javascript object from form element
var obj = $('#my-form').jform();

// set object info form element
$('#my-form').jform(obj);
// or
$('#my-form').jform('{"text":"1234"}');
```

## License
Apache License 2.0
