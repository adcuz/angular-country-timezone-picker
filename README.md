# angular-country-picker

AngularJS directive to generate a list of countries as options of the select element. Additionally you can have an automatically updating select input for time zone.

## Installation

You can install the directive using [Bower](http://bower.io/):

```bash
$ bower install angular-country-timezone-picker
```

## Usage

### The country picker
```html
<country-timezone-picker-countries country-model="countryModel" class="form-control input-lg"></country-timezone-picker-countries>
```

### The timezone picker
```html
<country-timezone-picker-timezone country-model="countryModel" timezone-model="timezoneModel" class="form-control input-lg"></country-timezone-picker-timezone>
```
