# Pluralize

Angular adaption of the great work by @blakeembrey

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]

Return a pluralized or singularized word based on the input string.

## Installation

```javascript
npm install pluralize --save
bower install pluralize --save
```

### Angular

```javascript

angular.module('MyApp', ['jp.pluralise']);

angular.module('MyApp')
  .controller('MyController',ctrl)

  ctrl.$inject = ['pluralise'];

  function ctrl(pluralise) {

    // use the pluraliser


  }
```


### `<script>` tag

```html
<script src="pluralize.js"></script>
```

## Usage

```javascript
pluralise.pluralise('fox'); //=> "foxes"
pluralise.singularise('foxes'); //=> "fox"
```

## License

MIT

[npm-image]: https://img.shields.io/npm/v/pluralize.svg?style=flat
[npm-url]: https://npmjs.org/package/pluralize
[travis-image]: https://img.shields.io/travis/blakeembrey/pluralize.svg?style=flat
[travis-url]: https://travis-ci.org/blakeembrey/pluralize
[coveralls-image]: https://img.shields.io/coveralls/blakeembrey/pluralize.svg?style=flat
[coveralls-url]: https://coveralls.io/r/blakeembrey/pluralize?branch=master
