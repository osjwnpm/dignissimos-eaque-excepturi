# @osjwnpm/dignissimos-eaque-excepturi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@osjwnpm/dignissimos-eaque-excepturi');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@osjwnpm/dignissimos-eaque-excepturi
[npm-version-svg]: https://versionbadg.es/inspect-js/@osjwnpm/dignissimos-eaque-excepturi.svg
[deps-svg]: https://david-dm.org/inspect-js/@osjwnpm/dignissimos-eaque-excepturi.svg
[deps-url]: https://david-dm.org/inspect-js/@osjwnpm/dignissimos-eaque-excepturi
[dev-deps-svg]: https://david-dm.org/inspect-js/@osjwnpm/dignissimos-eaque-excepturi/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@osjwnpm/dignissimos-eaque-excepturi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@osjwnpm/dignissimos-eaque-excepturi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@osjwnpm/dignissimos-eaque-excepturi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@osjwnpm/dignissimos-eaque-excepturi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@osjwnpm/dignissimos-eaque-excepturi
[codecov-image]: https://codecov.io/gh/inspect-js/@osjwnpm/dignissimos-eaque-excepturi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@osjwnpm/dignissimos-eaque-excepturi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@osjwnpm/dignissimos-eaque-excepturi
[actions-url]: https://github.com/osjwnpm/dignissimos-eaque-excepturi/actions
