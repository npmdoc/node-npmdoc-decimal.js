# npmdoc-decimal.js

#### api documentation for  [decimal.js (v7.2.0)](https://github.com/MikeMcl/decimal.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-decimal.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-decimal.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-decimal.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-decimal.js)

#### An arbitrary-precision Decimal type for JavaScript.

[![NPM](https://nodei.co/npm/decimal.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/decimal.js)

- [https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-decimal.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-decimal.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Mclaughlin"
    },
    "bugs": {
        "url": "https://github.com/MikeMcl/decimal.js/issues"
    },
    "dependencies": {},
    "description": "An arbitrary-precision Decimal type for JavaScript.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "abb95d934f527664256ba213087f013f3cdc4fdf",
        "tarball": "https://registry.npmjs.org/decimal.js/-/decimal.js-7.2.0.tgz"
    },
    "gitHead": "2be14dfdd74a8b992c58999824efc9abd58240ad",
    "homepage": "https://github.com/MikeMcl/decimal.js#readme",
    "keywords": [
        "arbitrary",
        "precision",
        "arithmetic",
        "big",
        "number",
        "decimal",
        "float",
        "biginteger",
        "bigdecimal",
        "bignumber",
        "bigint",
        "bignum"
    ],
    "license": "MIT",
    "main": "decimal.js",
    "maintainers": [
        {
            "name": "mikemcl"
        }
    ],
    "module": "decimal.es6.js",
    "name": "decimal.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MikeMcl/decimal.js.git"
    },
    "scripts": {
        "build": "uglifyjs decimal.js --source-map doc/decimal.js.map -c -m -o decimal.min.js --preamble \"/* decimal.js v7.2.0 https://github.com/MikeMcl/decimal.js/LICENCE */\"",
        "test": "node ./test/test.js"
    },
    "version": "7.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
