# @ellentorg/aliquam-aspernatur-quidem <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@ellentorg/aliquam-aspernatur-quidem');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@ellentorg/aliquam-aspernatur-quidem
[2]: https://versionbadg.es/inspect-js/@ellentorg/aliquam-aspernatur-quidem.svg
[5]: https://david-dm.org/inspect-js/@ellentorg/aliquam-aspernatur-quidem.svg
[6]: https://david-dm.org/inspect-js/@ellentorg/aliquam-aspernatur-quidem
[7]: https://david-dm.org/inspect-js/@ellentorg/aliquam-aspernatur-quidem/dev-status.svg
[8]: https://david-dm.org/inspect-js/@ellentorg/aliquam-aspernatur-quidem#info=devDependencies
[11]: https://nodei.co/npm/@ellentorg/aliquam-aspernatur-quidem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@ellentorg/aliquam-aspernatur-quidem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@ellentorg/aliquam-aspernatur-quidem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@ellentorg/aliquam-aspernatur-quidem
[codecov-image]: https://codecov.io/gh/inspect-js/@ellentorg/aliquam-aspernatur-quidem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@ellentorg/aliquam-aspernatur-quidem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@ellentorg/aliquam-aspernatur-quidem
[actions-url]: https://github.com/ellentorg/aliquam-aspernatur-quidem/actions
