[circleci-url]: https://circleci.com/gh/mgthomas99/random2
[circleci-shield-url]: https://img.shields.io/circleci/project/github/mgthomas99/random2.svg
[codecov-url]: https://codecov.io/gh/mgthomas99/random2
[codecov-shield-url]: https://img.shields.io/codecov/c/github/mgthomas99/random2.svg
[license-url]: https://github.com/mgthomas99/random2/blob/master/LICENSE
[license-shield-url]: https://img.shields.io/github/license/mgthomas99/random2.svg
[npm-url]: https://www.npmjs.com/package/random2
[npm-shield-url]: https://img.shields.io/npm/v/random2.svg

# random2
[![npm][npm-shield-url]][npm-url]
[![license][license-shield-url]][license-url]
[![CircleCI][circleci-shield-url]][circleci-url]
[![Codecov][codecov-shield-url]][codecov-url]
Seeded pseudorandom number generator object implementation for NodeJS.

## Usage
Install the module via npm: `npm install random2`

Install the module via yarn: `yarn random2`

Use it in your JS like so:
```
var random2 = require("random2");

var myRandom = new random2();
myRandom.next(); // Get a number
```
Or create a seeded instance:
```
var myRandom = new random2(5013);
myRandom.next();
```

### Typings
Typescript defenitions are included with the package.
