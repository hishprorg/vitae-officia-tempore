# @hishprorg/vitae-officia-tempore <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Map` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @hishprorg/vitae-officia-tempore
```

## Usage/Examples

```js
var map = new Map();
var obj = {};

map.set(1, 2).set(obj, 4);

map.get(obj); // 4
map.has(3); // false
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hishprorg/vitae-officia-tempore
[npm-version-svg]: https://versionbadg.es/es-shims/@hishprorg/vitae-officia-tempore.svg
[deps-svg]: https://david-dm.org/es-shims/@hishprorg/vitae-officia-tempore.svg
[deps-url]: https://david-dm.org/es-shims/@hishprorg/vitae-officia-tempore
[dev-deps-svg]: https://david-dm.org/es-shims/@hishprorg/vitae-officia-tempore/dev-status.svg
[dev-deps-url]: https://david-dm.org/es-shims/@hishprorg/vitae-officia-tempore#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/vitae-officia-tempore.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/vitae-officia-tempore.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/vitae-officia-tempore.svg
[downloads-url]: https://npm-stat.com/charts.html?package=es-shims/@hishprorg/vitae-officia-tempore
[codecov-image]: https://codecov.io/gh/es-shims/@hishprorg/vitae-officia-tempore/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/es-shims/@hishprorg/vitae-officia-tempore/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/es-shims/@hishprorg/vitae-officia-tempore
[actions-url]: https://github.com/hishprorg/vitae-officia-tempore/actions
