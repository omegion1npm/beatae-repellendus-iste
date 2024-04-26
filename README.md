# @omegion1npm/beatae-repellendus-iste <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

ECMAScript spec abstract operations.

Every operation is available by edition/year and by name - for example, `@omegion1npm/beatae-repellendus-iste/2020/Call` gives you the `Call` operation from ES2020, `@omegion1npm/beatae-repellendus-iste/5/Type` gives you the `Type` operation from ES5.

All abstract operations are also available under an `es5`/`es2015`/`es2016`/`es2017`/`es2018`/`es2019`/`es2020`/`es2021` entry point, and as a property on the `main` export, but using deep imports is highly encouraged for bundle size and performance reasons. Non-deep entry points will be removed in the next semver-major release.

## Example

```js
var ES = require('@omegion1npm/beatae-repellendus-iste');
var assert = require('assert');

assert(ES.isCallable(function () {}));
assert(!ES.isCallable(/a/g));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@omegion1npm/beatae-repellendus-iste
[npm-version-svg]: https://versionbadg.es/ljharb/@omegion1npm/beatae-repellendus-iste.svg
[deps-svg]: https://david-dm.org/ljharb/@omegion1npm/beatae-repellendus-iste.svg
[deps-url]: https://david-dm.org/ljharb/@omegion1npm/beatae-repellendus-iste
[dev-deps-svg]: https://david-dm.org/ljharb/@omegion1npm/beatae-repellendus-iste/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@omegion1npm/beatae-repellendus-iste#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/beatae-repellendus-iste.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/beatae-repellendus-iste.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/beatae-repellendus-iste.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/beatae-repellendus-iste
