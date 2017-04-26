# npmdoc-warehouse

#### basic api documentation for  [warehouse (v2.2.0)](https://github.com/tommy351/warehouse#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-warehouse.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-warehouse) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-warehouse.svg)](https://travis-ci.org/npmdoc/node-npmdoc-warehouse)

#### Simple JSON-based database

[![NPM](https://nodei.co/npm/warehouse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/warehouse)

- [https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-warehouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-warehouse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-warehouse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Chen",
        "url": "http://zespia.tw"
    },
    "bugs": {
        "url": "https://github.com/tommy351/warehouse/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.7",
        "bluebird": "^3.2.2",
        "cuid": "~1.3.8",
        "graceful-fs": "^4.1.3",
        "is-plain-object": "^2.0.1",
        "lodash": "^4.2.1"
    },
    "description": "Simple JSON-based database",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "eslint": "^1.10.3",
        "istanbul": "^0.4.2",
        "jscs": "^2.9.0",
        "jsdoc": "^3.4.0",
        "minami": "^1.1.1",
        "mocha": "^2.4.5",
        "sinon": "^1.17.3"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "5d09d64942992be667d8f7c86a09c2b8aea04062",
        "tarball": "https://registry.npmjs.org/warehouse/-/warehouse-2.2.0.tgz"
    },
    "gitHead": "e46a663a6e2d2fc00579a0d80412e976ac5da73f",
    "homepage": "https://github.com/tommy351/warehouse#readme",
    "keywords": [
        "database",
        "json",
        "db"
    ],
    "license": "MIT",
    "main": "lib/database",
    "maintainers": [
        {
            "name": "tommy351"
        }
    ],
    "name": "warehouse",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tommy351/warehouse.git"
    },
    "scripts": {
        "eslint": "eslint .",
        "jscs": "jscs .",
        "jsdoc": "jsdoc --configure .jsdoc.json",
        "test": "mocha test/index.js",
        "test-cov": "istanbul cover --print both _mocha -- test/index.js"
    },
    "version": "2.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
