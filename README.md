# npmdoc-mocha-phantomjs

#### api documentation for  [mocha-phantomjs (v4.1.0)](https://github.com/nathanboktae/mocha-phantomjs#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mocha-phantomjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mocha-phantomjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mocha-phantomjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mocha-phantomjs)

#### Run mocha browser tests in phantomjs via the command line

[![NPM](https://nodei.co/npm/mocha-phantomjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-phantomjs)

- [https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mocha-phantomjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Black",
        "url": "http://nathanblack.org"
    },
    "bin": {
        "mocha-phantomjs": "./bin/mocha-phantomjs"
    },
    "bugs": {
        "url": "http://github.com/nathanboktae/mocha-phantomjs/issues"
    },
    "contributors": [
        {
            "name": "Jonathan Chapman",
            "url": "https://github.com/chafnan"
        },
        {
            "name": "Ken Collins",
            "url": "http://metaskills.net/"
        }
    ],
    "dependencies": {
        "commander": "^2.8.1",
        "mocha-phantomjs-core": "^1.1.0",
        "phantomjs": "1.9.7-15"
    },
    "description": "Run mocha browser tests in phantomjs via the command line",
    "devDependencies": {
        "bluebird": "^2.9.25",
        "chai": "^2.3.0",
        "co-mocha": "^1.1.0",
        "coffee-script": "^1.9.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c75e16612e1a6af0ad8d281e3a2fef49d55e505b",
        "tarball": "https://registry.npmjs.org/mocha-phantomjs/-/mocha-phantomjs-4.1.0.tgz"
    },
    "gitHead": "cfd02ef25593ecbfcdf7fc04b0e1f2be657f4f47",
    "homepage": "https://github.com/nathanboktae/mocha-phantomjs#readme",
    "keywords": [
        "phantomjs",
        "mocha",
        "test",
        "runner",
        "command line",
        "browser"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/nathanboktae/mocha-phantomjs/blob/master/MIT-LICENSE"
        }
    ],
    "main": "./bin/mocha-phantomjs",
    "maintainers": [
        {
            "name": "metaskills"
        },
        {
            "name": "nathanboktae"
        }
    ],
    "name": "mocha-phantomjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nathanboktae/mocha-phantomjs.git"
    },
    "scripts": {
        "test": "mocha --harmony --compilers coffee:coffee-script/register test/mocha-phantomjs.coffee -t 5000"
    },
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
