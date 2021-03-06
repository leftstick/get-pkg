# get-pkg [![NPM version](https://img.shields.io/npm/v/get-pkg.svg?style=flat)](https://www.npmjs.com/package/get-pkg) [![NPM downloads](https://img.shields.io/npm/dm/get-pkg.svg?style=flat)](https://npmjs.org/package/get-pkg) [![Build Status](https://img.shields.io/travis/jonschlinkert/get-pkg.svg?style=flat)](https://travis-ci.org/jonschlinkert/get-pkg)

> Get the package.json for a project from npm.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install get-pkg --save
```

This code was pulled out of [get-pkgs](https://github.com/jonschlinkert/get-pkgs).

## Usage

```js
var getPkg = require('get-pkg');

getPkg('generate', function(err, pkg) {
  console.log(pkg);
});

//specify a registry
getPkg('generate', {
  registry: 'https://registry.npm.taobao.org/'
}, function(err, pkg) {
  console.log(pkg);
});
```

## Related projects

You might also be interested in these projects:

* [get-pkgs](https://www.npmjs.com/package/get-pkgs): Get the package.json for an array of repos from the npm registry, optionally filtering properties… [more](https://www.npmjs.com/package/get-pkgs) | [homepage](https://github.com/jonschlinkert/get-pkgs)
* [github-base](https://www.npmjs.com/package/github-base): Base methods for creating node.js apps that work with the GitHub API. | [homepage](https://github.com/jonschlinkert/github-base)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/get-pkg/issues/new).

## Building docs

Generate readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install verb && npm run docs
```

Or, if [verb](https://github.com/verbose/verb) is installed globally:

```sh
$ verb
```

## Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/get-pkg/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on April 11, 2016._