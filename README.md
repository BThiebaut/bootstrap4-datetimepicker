# Datetimepicker for Bootstrap 4 - VueJS

Forked from [pingcheng](https://github.com/pingcheng/bootstrap4-datetimepicker)

Use fromUTC parameter to initialize from an moment UTC format
Use vueContext to pass VueJs context to the picker object, then use vueProperty to pass the property to update on picker changes.

Note : Use dotted string like 'prop1.prop2' to use deep properties.

```js
  $('.datepicker').datetimepicker({
   fromUTC: true,
   vueContext : app,
   vueProperty : 'floor.property'
  });
```
Click [here](http://eonasdan.github.io/bootstrap-datetimepicker/) for the official usage documentation.

## Changes

* Add UTC date format support
* Add Vuejs binding context support
