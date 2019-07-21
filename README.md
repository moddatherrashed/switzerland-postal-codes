switzerland-postal-codes
========================

[![Build Status][travis-image]][travis-url]
[![Coverage Status][coverage-image]][coverage-url]
[![Dependencies Status][daviddm-image]][daviddm-url]
[![NPM version][npm-image]][npm-url]

Switzerland postal codes Javascript module.

Install
-------

```bash
npm i switzerland-postal-codes --save
```

or

```bash
bower install switzerland-postal-codes
```

Usage
-----

```js
var postalCodes = require('switzerland-postal-codes');

console.log(postalCodes['1260']); //=> 'Nyon'
```

or use `dist/postal-codes.json` or `dist/postal-codes-full.json` in your HTML.

Demo
----

See the [demo](https://williambelle.github.io/switzerland-postal-codes/).

Data
----

  - Postal codes based on the [official postal codes database][1] from Swiss Post
  - Geolocation based on the [Geonames database][2] licensed under a [Creative
    Commons Attribution 3.0 License][3].

Contributing
------------

Contributions are always welcome.

See [Contributing](CONTRIBUTING.md).

Developer
---------

  * [William Belle](https://github.com/williambelle)

License
-------

The MIT License (MIT)

[1]: https://www.post.ch/en/business/a-z-of-subjects/maintaining-customer-addresses/address-master-data
[2]: http://www.geonames.org/
[3]: http://creativecommons.org/licenses/by/3.0/
[npm-image]: https://img.shields.io/npm/v/switzerland-postal-codes.svg
[npm-url]: https://www.npmjs.com/package/switzerland-postal-codes
[travis-image]: https://travis-ci.org/williambelle/switzerland-postal-codes.svg?branch=master
[travis-url]: https://travis-ci.org/williambelle/switzerland-postal-codes
[coverage-image]: https://coveralls.io/repos/github/williambelle/switzerland-postal-codes/badge.svg
[coverage-url]: https://coveralls.io/github/williambelle/switzerland-postal-codes
[daviddm-image]: https://david-dm.org/williambelle/switzerland-postal-codes/status.svg
[daviddm-url]: https://david-dm.org/williambelle/switzerland-postal-codes
