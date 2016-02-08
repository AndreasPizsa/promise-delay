# promise-delay [![NPM version](https://badge.fury.io/js/promise-delay.svg)](http://badge.fury.io/js/promise-delay)

> Promise.delay() for ES6. Returns a promise that will be resolved after a delay.

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i promise-delay --save
```

## Usage

```js
require('promise-delay')();
```

or with `any-promise`

```js
require('promise-delay')(require('any-promise'));
```

## API

### Promise.delay(ms[,value])

```js
Promise
  .delay(1000,'hello')
  .then(console.log);
// -> writes 'hello' after 1000ms
```

### promise.delay(ms)

```js
myAsyncFunction()
  .delay(1000)
  .then(console.log);
// -> writes the result of `myAsyncFunction` after a delay of 1000ms 
```

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/AndreasPizsa/promise-delay/issues/new).

## Author

**Andreas Pizsa**

+ [github/https.](https://github.com/https.)
+ [twitter/https.](http://twitter.com/https.)

## License

Copyright © 2016 Andreas Pizsa
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on February 08, 2016._