# NO LONGER MAINTAINED - If you want to take this project over, please create an issue.

# angular-country-timezone-picker

AngularJS directive to generate a list of countries as options of the select element. Additionally you can have an automatically updating select input for time zone.

### [Demo](http://plnkr.co/edit/4BXNap?p=preview)

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
