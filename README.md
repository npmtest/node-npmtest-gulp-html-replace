# npmtest-gulp-html-replace

#### test coverage for  [gulp-html-replace (v1.6.2)](https://github.com/VFK/gulp-html-replace#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-html-replace.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-html-replace) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-html-replace.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-html-replace)

#### Replace build blocks in HTML. Like useref but done right.

[![NPM](https://nodei.co/npm/gulp-html-replace.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-html-replace)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-html-replace/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-html-replace/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-html-replace/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-html-replace/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-html-replace/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-html-replace/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-html-replace/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-html-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-html-replace/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-html-replace/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vladimir Kucherenko"
    },
    "bugs": {
        "url": "https://github.com/VFK/gulp-html-replace/issues"
    },
    "contributors": [
        {
            "name": "Bruce MacNaughton"
        }
    ],
    "dependencies": {
        "bluebird": "^3.1.1",
        "clone": "^1.0.2",
        "object-assign": "^4.0.1",
        "readable-stream": "^2.0.4",
        "slash": "^1.0.0",
        "vinyl-buffer": "^1.0.0"
    },
    "description": "Replace build blocks in HTML. Like useref but done right.",
    "devDependencies": {
        "concat-stream": "^1.5.1",
        "from2-string": "^1.1.0",
        "gulp-util": "^3.0.7",
        "istanbul": "^0.4.0",
        "istanbul-coveralls": "^1.0.3",
        "mocha": "^2.3.4",
        "vinyl": "^1.1.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1e1066fa6f8538c8d199e99a3443472f2bb46242",
        "tarball": "https://registry.npmjs.org/gulp-html-replace/-/gulp-html-replace-1.6.2.tgz"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "files": [
        "lib"
    ],
    "gitHead": "4b99045040b3fbf79a2702a64276ec78a2e2b771",
    "homepage": "https://github.com/VFK/gulp-html-replace#readme",
    "keywords": [
        "gulpplugin",
        "html",
        "replace"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "vfk"
        }
    ],
    "name": "gulp-html-replace",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/VFK/gulp-html-replace.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -R dot",
        "coveralls": "istanbul cover _mocha && istanbul-coveralls",
        "test": "mocha"
    },
    "version": "1.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
