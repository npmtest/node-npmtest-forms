# test coverage for  [forms (v1.3.0)](https://github.com/caolan/forms#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-forms.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-forms) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-forms.svg)](https://travis-ci.org/npmtest/node-npmtest-forms)
#### An easy way to create, parse, and validate forms

[![NPM](https://nodei.co/npm/forms.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/forms)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-forms/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-forms/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-forms/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-forms/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-forms/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-forms/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-forms/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-forms/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-forms/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-forms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-forms/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-forms/build/test-report.html](https://npmtest.github.io/node-npmtest-forms/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-forms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-forms/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-forms/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-forms/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-forms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-forms/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-forms/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-forms/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Caolan McMahon"
    },
    "bugs": {
        "url": "https://github.com/caolan/forms/issues"
    },
    "contributors": [
        {
            "name": "Caolan McMahon"
        },
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        }
    ],
    "dependencies": {
        "async": "^2.1.2",
        "formidable": "^1.0.17",
        "is": "^3.2.0",
        "object-keys": "^1.0.11",
        "object.assign": "^4.0.4",
        "qs": "^6.3.0",
        "string.prototype.trim": "^1.1.2"
    },
    "description": "An easy way to create, parse, and validate forms",
    "devDependencies": {
        "@ljharb/eslint-config": "^8.0.0",
        "covert": "^1.1.0",
        "eslint": "^3.10.2",
        "evalmd": "^0.0.17",
        "jscs": "^3.0.7",
        "nsp": "^2.6.2",
        "tape": "^4.6.2",
        "tape-dom": "^0.0.12",
        "testling": "^1.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8a3a32361724b2fd33bea2a7881ea0ec7d0a0e07",
        "tarball": "https://registry.npmjs.org/forms/-/forms-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.4"
    },
    "gitHead": "78d8d3a5818d0586d8f54a9eecb09dd8ff4534f2",
    "homepage": "https://github.com/caolan/forms#readme",
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/caolan/forms/raw/master/LICENSE"
        }
    ],
    "main": "./index",
    "maintainers": [
        {
            "name": "caolan"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "forms",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/caolan/forms.git"
    },
    "scripts": {
        "coverage": "covert test/*.js",
        "coverage-quiet": "covert --quiet test/*.js",
        "eslint": "eslint test/*.js lib/*.js example/simple.js example/complex.js",
        "jscs": "jscs test/*.js lib/*.js example/simple.js example/complex.js",
        "lint": "npm run jscs && npm run eslint && evalmd *.md",
        "posttest": "npm run security",
        "pretest": "npm run lint",
        "security": "nsp check",
        "test": "npm run tests-only",
        "test-browser": "testling",
        "tests-only": "tape test/*.js"
    },
    "testling": {
        "files": "test-browser.js",
        "browsers": [
            "iexplore/6..latest",
            "firefox/3..10",
            "firefox/15..latest",
            "firefox/nightly",
            "chrome/4..10",
            "chrome/23..latest",
            "chrome/canary",
            "opera/10..latest",
            "opera/next",
            "safari/5.0.5..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2"
        ]
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
