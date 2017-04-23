# npmtest-replace-ext

#### basic test coverage for  [replace-ext (v1.0.0)](https://github.com/gulpjs/replace-ext#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-replace-ext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-replace-ext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-replace-ext.svg)](https://travis-ci.org/npmtest/node-npmtest-replace-ext)

#### Replaces a file extension with another one

[![NPM](https://nodei.co/npm/replace-ext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/replace-ext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-replace-ext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-replace-ext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-replace-ext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-replace-ext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-replace-ext/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-replace-ext/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-replace-ext/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-replace-ext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-replace-ext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-replace-ext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-replace-ext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-replace-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-replace-ext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-replace-ext/build/test-report.html](https://npmtest.github.io/node-npmtest-replace-ext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-replace-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-replace-ext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-replace-ext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-replace-ext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-replace-ext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-replace-ext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-replace-ext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-replace-ext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gulp Team",
        "url": "http://gulpjs.com/"
    },
    "bugs": {
        "url": "https://github.com/gulpjs/replace-ext/issues"
    },
    "contributors": [
        {
            "name": "Eric Schoffstall"
        },
        {
            "name": "Blaine Bublitz"
        }
    ],
    "dependencies": {},
    "description": "Replaces a file extension with another one",
    "devDependencies": {
        "eslint": "^1.10.3",
        "eslint-config-gulp": "^2.0.0",
        "expect": "^1.16.0",
        "istanbul": "^0.4.3",
        "istanbul-coveralls": "^1.0.3",
        "jscs": "^2.3.5",
        "jscs-preset-gulp": "^1.0.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "de63128373fcbf7c3ccfa4de5a480c45a67958eb",
        "tarball": "https://registry.npmjs.org/replace-ext/-/replace-ext-1.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "index.js"
    ],
    "gitHead": "adaec75e316f1c375dc7a2cb51c7b762b135cc0e",
    "homepage": "https://github.com/gulpjs/replace-ext#readme",
    "keywords": [
        "gulp",
        "extensions",
        "filepath",
        "basename"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "contra"
        },
        {
            "name": "fractal"
        },
        {
            "name": "phated"
        }
    ],
    "name": "replace-ext",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gulpjs/replace-ext.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly",
        "coveralls": "npm run cover && istanbul-coveralls",
        "lint": "eslint . && jscs index.js test/",
        "pretest": "npm run lint",
        "test": "mocha --async-only"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
