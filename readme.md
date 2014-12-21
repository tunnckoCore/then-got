## [![npm][npmjs-img]][npmjs-url] [![mit license][license-img]][license-url] [![build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![deps status][daviddm-img]][daviddm-url]

> Simplified and promised HTTP/HTTPS requests, sindresorhus/got

## Install
```bash
npm install then-got
npm test
```


## Usage
> For more use-cases see the [tests](./test.js)

```js
var assert = require('assert');
var got = require('then-got');

got('http://todomvc.com')
    .then(function fulfilled(res) {
      //=> <!doctype html> ...
      assert.ok(startsWith(res, '<!doctype html>'));
      assert.ok(res.length >= 1000);
    });
```

## Author
**Charlike Mike Reagent**
+ [gratipay/tunnckoCore][author-gratipay]
+ [twitter/tunnckoCore][author-twitter]
+ [github/tunnckoCore][author-github]
+ [npmjs/tunnckoCore][author-npmjs]
+ [more ...][contrib-more]


## License [![MIT license][license-img]][license-url]
Copyright (c) 2014 [Charlike Mike Reagent][contrib-more], [contributors][contrib-graf].  
Released under the [`MIT`][license-url] license.


[npmjs-url]: http://npm.im/then-got
[npmjs-img]: https://img.shields.io/npm/v/then-got.svg?style=flat&label=then-got

[coveralls-url]: https://coveralls.io/r/tunnckoCore/then-got?branch=master
[coveralls-img]: https://img.shields.io/coveralls/tunnckoCore/then-got.svg?style=flat

[license-url]: https://github.com/tunnckoCore/then-got/blob/master/license.md
[license-img]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat

[travis-url]: https://travis-ci.org/tunnckoCore/then-got
[travis-img]: https://img.shields.io/travis/tunnckoCore/then-got.svg?style=flat

[daviddm-url]: https://david-dm.org/tunnckoCore/then-got
[daviddm-img]: https://img.shields.io/david/tunnckoCore/then-got.svg?style=flat

[author-gratipay]: https://gratipay.com/tunnckoCore
[author-twitter]: https://twitter.com/tunnckoCore
[author-github]: https://github.com/tunnckoCore
[author-npmjs]: https://npmjs.org/~tunnckocore

[contrib-more]: http://j.mp/1stW47C
[contrib-graf]: https://github.com/tunnckoCore/then-got/graphs/contributors

***

_Powered and automated by [readdirp + hogan.js](https://github.com/tunnckoCore), December 21, 2014_