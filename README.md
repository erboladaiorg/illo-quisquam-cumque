# @erboladaiorg/illo-quisquam-cumque <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@erboladaiorg/illo-quisquam-cumque');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@erboladaiorg/illo-quisquam-cumque
[npm-version-svg]: https://versionbadg.es/inspect-js/@erboladaiorg/illo-quisquam-cumque.svg
[deps-svg]: https://david-dm.org/inspect-js/@erboladaiorg/illo-quisquam-cumque.svg
[deps-url]: https://david-dm.org/inspect-js/@erboladaiorg/illo-quisquam-cumque
[dev-deps-svg]: https://david-dm.org/inspect-js/@erboladaiorg/illo-quisquam-cumque/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@erboladaiorg/illo-quisquam-cumque#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/illo-quisquam-cumque.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/illo-quisquam-cumque.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/illo-quisquam-cumque.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/illo-quisquam-cumque
[codecov-image]: https://codecov.io/gh/inspect-js/@erboladaiorg/illo-quisquam-cumque/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@erboladaiorg/illo-quisquam-cumque/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@erboladaiorg/illo-quisquam-cumque
[actions-url]: https://github.com/erboladaiorg/illo-quisquam-cumque/actions
