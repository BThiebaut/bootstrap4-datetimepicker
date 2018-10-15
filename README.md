# Datetimepicker for Bootstrap 4 - Binding support

Forked from [pingcheng](https://github.com/pingcheng/bootstrap4-datetimepicker)

Use fromUTC parameter to initialize from an moment UTC format
Use bindingContext to pass binding context to the picker object, then use bindingProperty to pass the property to update when picker change.

Note : Use dotted string like 'prop1.prop2' to use deep properties.

```js
  $('.datepicker').datetimepicker({
   fromUTC: true,
   bindingContext : app,
   bindingProperty : 'floor.property'
  });
```
Click [here](http://eonasdan.github.io/bootstrap-datetimepicker/) for the official usage documentation.

## Changes

* Add UTC date format support
* Add binding context support (tested with VueJs)


## TODO
* Update unit tests
