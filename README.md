# @taktikorg/similique-earum-soluta <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@taktikorg/similique-earum-soluta');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/similique-earum-soluta
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikorg/similique-earum-soluta.svg
[deps-svg]: https://david-dm.org/inspect-js/@taktikorg/similique-earum-soluta.svg
[deps-url]: https://david-dm.org/inspect-js/@taktikorg/similique-earum-soluta
[dev-deps-svg]: https://david-dm.org/inspect-js/@taktikorg/similique-earum-soluta/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@taktikorg/similique-earum-soluta#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/similique-earum-soluta.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/similique-earum-soluta.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/similique-earum-soluta.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/similique-earum-soluta
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/similique-earum-soluta/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/similique-earum-soluta/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/similique-earum-soluta
[actions-url]: https://github.com/taktikorg/similique-earum-soluta/actions
