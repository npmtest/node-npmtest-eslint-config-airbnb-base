# npmtest-eslint-config-airbnb-base

#### basic test coverage for  [eslint-config-airbnb-base (v11.1.3)](https://github.com/airbnb/javascript)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-config-airbnb-base.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-config-airbnb-base) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-config-airbnb-base.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-config-airbnb-base)

#### Airbnb's base JS ESLint config, following our styleguide

[![NPM](https://nodei.co/npm/eslint-config-airbnb-base.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-config-airbnb-base)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-config-airbnb-base/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-config-airbnb-base/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-config-airbnb-base/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-config-airbnb-base/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Teton-Landis",
        "url": "https://twitter.com/@jitl"
    },
    "bugs": {
        "url": "https://github.com/airbnb/javascript/issues"
    },
    "contributors": [
        {
            "name": "Jake Teton-Landis",
            "url": "https://twitter.com/jitl"
        },
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        },
        {
            "name": "Harrison Shoff",
            "url": "https://twitter.com/hshoff"
        }
    ],
    "dependencies": {},
    "description": "Airbnb's base JS ESLint config, following our styleguide",
    "devDependencies": {
        "babel-preset-airbnb": "^2.2.3",
        "babel-tape-runner": "^2.0.1",
        "editorconfig-tools": "^0.1.1",
        "eslint": "^3.19.0",
        "eslint-find-rules": "^1.14.3",
        "eslint-plugin-import": "^2.2.0",
        "in-publish": "^2.0.0",
        "safe-publish-latest": "^1.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "0e8db71514fa36b977fbcf977c01edcf863e0cf0",
        "tarball": "https://registry.npmjs.org/eslint-config-airbnb-base/-/eslint-config-airbnb-base-11.1.3.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "homepage": "https://github.com/airbnb/javascript",
    "keywords": [
        "eslint",
        "eslintconfig",
        "config",
        "airbnb",
        "javascript",
        "styleguide"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "airbnb"
        },
        {
            "name": "ljharb"
        }
    ],
    "name": "eslint-config-airbnb-base",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^3.19.0",
        "eslint-plugin-import": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/airbnb/javascript.git"
    },
    "scripts": {
        "lint": "eslint .",
        "prelint": "editorconfig-tools check * rules/* test/*",
        "prepublish": "(in-install || eslint-find-rules --unused) && (not-in-publish || npm test) && safe-publish-latest",
        "pretest": "npm run --silent lint",
        "test": "npm run --silent tests-only",
        "tests-only": "babel-tape-runner ./test/test-*.js",
        "travis": "npm run --silent test"
    },
    "version": "11.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
