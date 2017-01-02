# omit-deep [![NPM version](https://img.shields.io/npm/v/omit-deep.svg?style=flat)](https://www.npmjs.com/package/omit-deep) [![NPM monthly downloads](https://img.shields.io/npm/dm/omit-deep.svg?style=flat)](https://npmjs.org/package/omit-deep)  [![NPM total downloads](https://img.shields.io/npm/dt/omit-deep.svg?style=flat)](https://npmjs.org/package/omit-deep) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/omit-deep.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/omit-deep)

> Recursively omit the specified key or keys from an object.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save omit-deep
```

## Usage

```js
var omitDeep = require('omit-deep');

omitDeep({a: 'a', b: 'b', c: {b: 'b', d: {b: 'b', f: 'f'}}});
//=> {a: 'a', c: {d: {f: 'f'}}}
```

## About

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors

| **Commits** | **Contributor** | 
| --- | --- |
| 11 | [jonschlinkert](https://github.com/jonschlinkert) |
| 2 | [splodingsocks](https://github.com/splodingsocks) |
| 1 | [rikukissa](https://github.com/rikukissa) |

### Building docs

_(This document was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme) (a [verb](https://github.com/verbose/verb) generator), please don't edit the readme directly. Any changes to the readme must be made in [.verb.md](.verb.md).)_

To generate the readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install -g verb verb-generate-readme && verb
```

### Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

### License

Copyright © 2017, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.2.1, on January 01, 2017._