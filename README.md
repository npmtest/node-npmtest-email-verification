# npmtest-email-verification

#### basic test coverage for  [email-verification (v0.4.6)](http://email-verification.xyz/)  [![npm package](https://img.shields.io/npm/v/npmtest-email-verification.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-email-verification) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-email-verification.svg)](https://travis-ci.org/npmtest/node-npmtest-email-verification)

#### Verify email sign-up using MongoDB.

[![NPM](https://nodei.co/npm/email-verification.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/email-verification)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-email-verification/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-email-verification/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-email-verification/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-email-verification/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-email-verification/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-email-verification/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-email-verification/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-email-verification/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-email-verification/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-email-verification/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-email-verification/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-email-verification/build/test-report.html](https://npmtest.github.io/node-npmtest-email-verification/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-email-verification/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-email-verification/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-email-verification/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-email-verification/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-email-verification/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-email-verification/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-email-verification/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-email-verification/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "email-verification",
    "version": "0.4.6",
    "description": "Verify email sign-up using MongoDB.",
    "main": "index.js",
    "scripts": {
        "format:examples": "js-beautify -r examples/**/*.js",
        "format:main": "js-beautify -r index.js",
        "format:test": "js-beautify -s 2 -r test/*.js",
        "format": "npm run format:main && npm run format:examples && npm run format:test",
        "lint:examples": "jshint --reporter=node_modules/jshint-stylish examples/**/*.js",
        "lint:main": "jshint --reporter=node_modules/jshint-stylish index.js",
        "lint:test": "jshint --reporter=node_modules/jshint-stylish test/*.js",
        "lint": "npm run lint:main && npm run lint:examples && npm run lint:test",
        "test": "mocha"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/whitef0x0/node-email-verification"
    },
    "keywords": [
        "mongodb",
        "auth",
        "authentication",
        "email"
    ],
    "author": "Dakota St. Laurent <hello@saintdako.com> (http://saintdako.com/)",
    "contributors": [
        {
            "name": "David Baldwynn",
            "url": "https://github.com/whitef0x0"
        },
        {
            "name": "Frank Cash",
            "url": "https://github.com/frankcash"
        }
    ],
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/whitef0x0/node-email-verification/issues"
    },
    "homepage": "http://email-verification.xyz/",
    "dependencies": {
        "mongoose": "~3.8.0",
        "nodemailer": "^1.3.0",
        "rand-token": "^0.2.1"
    },
    "devDependencies": {
        "async": "^1.4.2",
        "bcryptjs": "^2.3.0",
        "body-parser": "^1.9.3",
        "chai": "*",
        "express": "^4.10.4",
        "js-beautify": "^1.5.10",
        "jshint": "*",
        "jshint-stylish": "*",
        "mocha": "*",
        "nodemailer-stub-transport": "^1.0.0",
        "bluebird": "*"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
