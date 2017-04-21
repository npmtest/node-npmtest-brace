# npmtest-brace

#### basic test coverage for  [brace (v0.10.0)](https://github.com/thlorenz/brace)  [![npm package](https://img.shields.io/npm/v/npmtest-brace.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-brace) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-brace.svg)](https://travis-ci.org/npmtest/node-npmtest-brace)

#### browserify compatible version of the ace editor.

[![NPM](https://nodei.co/npm/brace.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/brace)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-brace/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-brace/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-brace/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-brace/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-brace/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-brace/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-brace/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-brace/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-brace/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-brace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-brace/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-brace/build/test-report.html](https://npmtest.github.io/node-npmtest-brace/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-brace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-brace/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-brace/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-brace/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brace/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-brace/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-brace/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "brace",
    "version": "0.10.0",
    "description": "browserify compatible version of the ace editor.",
    "main": "index.js",
    "typings": "index.d.ts",
    "scripts": {
        "update": "(cd build && node ./update && node ./update-ts)",
        "test": "browserify test/*.js > test/bundle.js --debug && opener test/index.html"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/brace.git"
    },
    "homepage": "https://github.com/thlorenz/brace",
    "dependencies": {
        "w3c-blob": "0.0.1"
    },
    "devDependencies": {
        "browserify": "~4.2.0",
        "opener": "~1.3.0",
        "shelljs": "~0.2.6",
        "tape": "~4.0.0",
        "uglify-js": "~2.2.5"
    },
    "keywords": [
        "ace",
        "editor",
        "browser",
        "package",
        "bundle",
        "inline",
        "browserify"
    ],
    "author": {
        "name": "Thorsten Lorenz",
        "url": "http://thlorenz.com"
    },
    "license": "MIT",
    "engine": {
        "node": ">=0.6"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "firefox/21..latest",
            "firefox/nightly",
            "chrome/26..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
