# @odczynflnpm/perferendis-neque-nulla <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A robust, ES3 compatible, "has own property" predicate.

## Example

```js
const assert = require('assert');
const hasOwn = require('@odczynflnpm/perferendis-neque-nulla');

assert.equal(hasOwn({}, 'toString'), false);
assert.equal(hasOwn([], 'length'), true);
assert.equal(hasOwn({ a: 42 }, 'a'), true);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@odczynflnpm/perferendis-neque-nulla
[npm-version-svg]: https://versionbadg.es/inspect-js/@odczynflnpm/perferendis-neque-nulla.svg
[deps-svg]: https://david-dm.org/odczynflnpm/perferendis-neque-nulla.svg
[deps-url]: https://david-dm.org/odczynflnpm/perferendis-neque-nulla
[dev-deps-svg]: https://david-dm.org/odczynflnpm/perferendis-neque-nulla/dev-status.svg
[dev-deps-url]: https://david-dm.org/odczynflnpm/perferendis-neque-nulla#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@odczynflnpm/perferendis-neque-nulla.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@odczynflnpm/perferendis-neque-nulla.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@odczynflnpm/perferendis-neque-nulla.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@odczynflnpm/perferendis-neque-nulla
[codecov-image]: https://codecov.io/gh/odczynflnpm/perferendis-neque-nulla/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/odczynflnpm/perferendis-neque-nulla/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/odczynflnpm/perferendis-neque-nulla
[actions-url]: https://github.com/odczynflnpm/perferendis-neque-nulla/actions
