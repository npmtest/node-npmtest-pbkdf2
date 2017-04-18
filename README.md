# npmtest-pbkdf2

#### test coverage for  [pbkdf2 (v3.0.9)](https://github.com/crypto-browserify/pbkdf2)  [![npm package](https://img.shields.io/npm/v/npmtest-pbkdf2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pbkdf2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pbkdf2.svg)](https://travis-ci.org/npmtest/node-npmtest-pbkdf2)

#### This library provides the functionality of PBKDF2 with the ability to use any supported hashing algorithm returned from crypto.getHashes()

[![NPM](https://nodei.co/npm/pbkdf2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pbkdf2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pbkdf2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pbkdf2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pbkdf2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pbkdf2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pbkdf2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pbkdf2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pbkdf2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pbkdf2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pbkdf2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pbkdf2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pbkdf2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pbkdf2/build/test-report.html](https://npmtest.github.io/node-npmtest-pbkdf2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pbkdf2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pbkdf2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pbkdf2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pbkdf2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pbkdf2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Cousens"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/crypto-browserify/pbkdf2/issues"
    },
    "dependencies": {
        "create-hmac": "^1.1.2"
    },
    "description": "This library provides the functionality of PBKDF2 with the ability to use any supported hashing algorithm returned from crypto.getHashes()",
    "devDependencies": {
        "browserify": "*",
        "nyc": "^6.4.0",
        "standard": "*",
        "tape": "^4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f2c4b25a600058b3c3773c086c37dbbee1ffe693",
        "tarball": "https://registry.npmjs.org/pbkdf2/-/pbkdf2-3.0.9.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "files": [
        "browser.js",
        "index.js",
        "node-shim-async.js",
        "node-shim.js",
        "precondition.js"
    ],
    "gitHead": "188f9b0aca397f2937249504f72d1d7e4b2f7bd3",
    "homepage": "https://github.com/crypto-browserify/pbkdf2",
    "keywords": [
        "pbkdf2",
        "kdf",
        "salt",
        "hash"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fundon"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "dcousens"
        },
        {
            "name": "jprichardson"
        },
        {
            "name": "dominictarr"
        },
        {
            "name": "indutny"
        }
    ],
    "name": "pbkdf2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/crypto-browserify/pbkdf2.git"
    },
    "scripts": {
        "bundle-test": "browserify test/index.js > test/bundle.js",
        "coverage": "nyc --check-coverage --branches 90 --functions 100 tape test/*.js",
        "lint": "standard",
        "prepublish": "npm run test",
        "test": "npm run lint && npm run unit",
        "unit": "tape test/*.js"
    },
    "standard": {
        "ignore": [
            "test/bundle.js"
        ]
    },
    "version": "3.0.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
