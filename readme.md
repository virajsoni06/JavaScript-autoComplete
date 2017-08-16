This is a forked repository of [Pixabay/JavaScript-autoComplete](https://github.com/Pixabay/JavaScript-autoComplete) with an additional method (`showSuggestions`) to trigger suggestions

JavaScript-autoComplete
===================

An extremely lightweight and powerful vanilla JavaScript completion suggester.

Tested in Firefox, Safari, Chrome, Opera, Internet Explorer 8+. No dependencies, written in plain JavaScript.
Released under the MIT License: http://www.opensource.org/licenses/mit-license.php

This plugin was developed by [Pixabay.com](https://pixabay.com/) - an international repository for sharing free public domain images.
We have implemented this piece of software in production on [plainJS](https://plainjs.com/) and we share it - in the spirit of Pixabay - freely with others.

## Demo and Documentation

https://goodies.pixabay.com/javascript/auto-complete/demo.html

## Features

* Lightweight: 5.4 kB of JavaScript - less than 2.4 kB gzipped
* Fully flexible data source
* Smart caching, delay and minimum character settings
* Callbacks


# Fork Contributors
- [Viraj Soni](https://github.com/virajsoni06)

## Changelog

### Version 1.0.6 - 2017/08/10

* Added option `reFocusAfterSelection` to enabe/disable focus on the field after selection

### Version 1.0.5 - 2017/08/10

* Added method `showSuggestions` to trigger the suggestion list


### Version 1.0.4 - 2016/02/10

* Included pull #6 and added offsetLeft/offsetTop as optional parameter for suggestions container.


### Version 1.0.3 - 2015/11/02

* Fixed #2: Unspecified error on IE 10.

### Version 1.0.2 - 2015/08/15

* Fixed: Hide suggestions on fast input.
* Fixed: Select item with tab.
* Fixed: Incorrect selection by mouse when suggestions are scrolled down.

### Version 1.0.1 - 2015/06/08

* Simplified code and minor bug fixes.

### Version 1.0.0 - 2015/06/07

* Prevent unnecessary search on pressing enter.

### Version 1.0.0 beta - 2015/05/12

* First release
