![Logo](admin/birthdays.png)

# ioBroker.birthdays

[![NPM version](http://img.shields.io/npm/v/iobroker.birthdays.svg)](https://www.npmjs.com/package/iobroker.birthdays)
[![Downloads](https://img.shields.io/npm/dm/iobroker.birthdays.svg)](https://www.npmjs.com/package/iobroker.birthdays)
[![Stable](http://iobroker.live/badges/birthdays-stable.svg)](http://iobroker.live/badges/birthdays-stable.svg)
[![installed](http://iobroker.live/badges/birthdays-installed.svg)](http://iobroker.live/badges/birthdays-installed.svg)
[![Dependency Status](https://img.shields.io/david/klein0r/iobroker.birthdays.svg)](https://david-dm.org/klein0r/iobroker.birthdays)
[![Known Vulnerabilities](https://snyk.io/test/github/klein0r/ioBroker.birthdays/badge.svg)](https://snyk.io/test/github/klein0r/ioBroker.birthdays)
![Test and Release](https://github.com/klein0r/ioBroker.birthdays/workflows/Test%20and%20Release/badge.svg)

[![NPM](https://nodei.co/npm/iobroker.birthdays.png?downloads=true)](https://nodei.co/npm/iobroker.birthdays/)

Use an ical file to import your contacts birthdays or define the birthday dates directly in the adapter settings

## Sponsored by

[![ioBroker Master Kurs](https://haus-automatisierung.com/images/ads/ioBroker-Kurs.png)](https://haus-automatisierung.com/iobroker-kurs/?refid=iobroker-birthdays)

## Installation

Please use the "adapter list" in ioBroker to install a stable version of this adapter. You can also use the CLI to install this adapter:

```
iobroker add birthdays
```

## Documentation

[🇺🇸 Documentation](./docs/en/basics.md)

[🇩🇪 Dokumentation](./docs/de/basics.md)

## Changelog

<!--
  Placeholder for the next version (at the beginning of the line):
  ### **WORK IN PROGRESS**
-->
### **WORK IN PROGRESS**

* (klein0r) CardDAV password config is not a clear text anymore

### 1.1.0 (2022-02-24)

* (klein0r) Added CardDAV support

### 1.0.0 (2022-02-10)

* (klein0r) Updated state roles
* (klein0r) Added hint for Admin 4 configuration
* (klein0r) Fixed translations

### 0.2.0 (2022-01-06)

* (klein0r) Added option to ignore certificate errors

### 0.1.8 (2022-01-03)

* (klein0r) Birthdays on 29th of February create NaN objects
* (klein0r) Added check for empty names
* (klein0r) Added date checks

### 0.1.7 (2021-12-23)

* (klein0r) Added defaults for birthdays table

### 0.1.6 (2021-11-18)

* (klein0r) Require new version for translated instance objects
* (klein0r) Fixed timeout handling

### 0.1.5 (2021-11-15)

* (klein0r) Updated internal state handling

### 0.1.4 (2021-11-14)

* (klein0r) Translated all objects

### 0.1.3 (2021-11-07)

* (klein0r) Format dates using ioBrokers configured formats

### 0.1.2 (2021-11-06)

* (klein0r) Fixed missing translations

### 0.1.1 (2021-11-05)

* (klein0r) Added custom date format
* (klein0r) Added custom next separator

### 0.1.0 (2021-11-05)

* (klein0r) Admin 5 Support

### 0.0.3 (2021-03-23)

* (klein0r) Added next and nextAfter birthdays

### 0.0.2 (2021-03-23)

* (klein0r) Added more objects and states

### 0.0.1 (2020-12-28)

* (klein0r) initial release

## Credits

[Logo by herbanu](https://pixabay.com/de/vectors/geburtstag-karte-cele-feier-design-3148707/)

## License

The MIT License (MIT)

Copyright (c) 2022 Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
