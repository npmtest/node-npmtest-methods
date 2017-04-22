# npmtest-methods

#### basic test coverage for  [methods (v1.1.2)](https://github.com/jshttp/methods)  [![npm package](https://img.shields.io/npm/v/npmtest-methods.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-methods) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-methods.svg)](https://travis-ci.org/npmtest/node-npmtest-methods)

#### HTTP methods that node supports

[![NPM](https://nodei.co/npm/methods.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/methods)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-methods/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-methods/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-methods/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-methods/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-methods/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-methods/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-methods/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-methods/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-methods/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-methods/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-methods/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-methods/build/test-report.html](https://npmtest.github.io/node-npmtest-methods/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-methods/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-methods/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-methods/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-methods/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-methods/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-methods/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "http": false
    },
    "bugs": {
        "url": "https://github.com/jshttp/methods/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        },
        {
            "name": "TJ Holowaychuk",
            "url": "http://tjholowaychuk.com"
        }
    ],
    "dependencies": {},
    "description": "HTTP methods that node supports",
    "devDependencies": {
        "istanbul": "0.4.1",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5529a4d67654134edcc5266656835b0f851afcee",
        "tarball": "https://registry.npmjs.org/methods/-/methods-1.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "index.js",
        "HISTORY.md",
        "LICENSE"
    ],
    "gitHead": "25d257d913f1b94bd2d73581521ff72c81469140",
    "homepage": "https://github.com/jshttp/methods",
    "keywords": [
        "http",
        "methods"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "dougwilson"
        }
    ],
    "name": "methods",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/methods.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
