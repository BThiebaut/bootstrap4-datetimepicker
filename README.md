# Datetimepicker for Bootstrap 4
[![Build Status](https://travis-ci.org/pingcheng/bootstrap4-datetimepicker.svg?branch=master)](https://travis-ci.org/pingcheng/bootstrap4-datetimepicker)

Forked from [pingcheng](https://github.com/pingcheng/bootstrap4-datetimepicker)

Use fromUTC parameter to initialize from an moment UTC format
```js
  $('.datepicker').datetimepicker({
     locale: '{{ app.request.locale }}',
     sideBySide: true,
     icons: {
          time: 'mdi mdi-progress-clock',
          date: 'fa fa-calendar',
          up: 'fa fa-arrow-up',
          down: 'fa fa-arrow-down',
          previous: 'fa fa-chevron-left',
          next: 'fa fa-chevron-right',
          today: 'fa fa-calendar-check',
          clear: 'fa fa-trash-alt',
          close: 'fa fa-times-circle'
    },
   fromUTC: true
```
Click [here](http://eonasdan.github.io/bootstrap-datetimepicker/) for the official usage documentation.

## Changes

* Add UTC date format support
