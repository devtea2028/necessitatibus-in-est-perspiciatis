# @devtea2028/necessitatibus-in-est-perspiciatis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@devtea2028/necessitatibus-in-est-perspiciatis');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2028/necessitatibus-in-est-perspiciatis
[npm-version-svg]: https://versionbadg.es/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis.svg
[deps-svg]: https://david-dm.org/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis.svg
[deps-url]: https://david-dm.org/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis
[dev-deps-svg]: https://david-dm.org/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2028/necessitatibus-in-est-perspiciatis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2028/necessitatibus-in-est-perspiciatis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2028/necessitatibus-in-est-perspiciatis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2028/necessitatibus-in-est-perspiciatis
[codecov-image]: https://codecov.io/gh/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@devtea2028/necessitatibus-in-est-perspiciatis
[actions-url]: https://github.com/devtea2028/necessitatibus-in-est-perspiciatis/actions
