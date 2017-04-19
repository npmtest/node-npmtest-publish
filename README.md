# npmtest-publish

#### test coverage for  [publish (v0.6.0)](https://github.com/cmanzana/node-publish)  [![npm package](https://img.shields.io/npm/v/npmtest-publish.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-publish) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-publish.svg)](https://travis-ci.org/npmtest/node-npmtest-publish)

#### npm auto publishing of your modules

[![NPM](https://nodei.co/npm/publish.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/publish)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-publish/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-publish/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-publish/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-publish/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-publish/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-publish/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-publish/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-publish/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-publish/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-publish/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-publish/build/test-report.html](https://npmtest.github.io/node-npmtest-publish/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-publish/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-publish/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-publish/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-publish/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "publish",
    "version": "0.6.0",
    "description": "npm auto publishing of your modules",
    "main": "index.js",
    "homepage": "https://github.com/cmanzana/node-publish",
    "bin": {
        "publish": "./bin/publish.js"
    },
    "scripts": {
        "test": "mocha --globals name"
    },
    "dependencies": {
        "npm": "2.x.x",
        "npmlog": "1.x.x",
        "semver": "4.x.x",
        "nopt": "3.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/cmanzana/node-publish.git"
    },
    "keywords": [
        "npm",
        "publish",
        "deploy",
        "CI"
    ],
    "devDependencies": {
        "mocha": "^2.4.5"
    },
    "author": {
        "name": "Carlos Manzanares"
    },
    "license": "MIT",
    "gitHead": "cffdab28fb1b813b2076fe5c8c7ff96d037be677",
    "bugs": {
        "url": "https://github.com/cmanzana/node-publish/issues"
    },
    "maintainers": [
        {
            "name": "cmanzana"
        }
    ],
    "dist": {
        "shasum": "ca124c8b9603ee1c7f739f35c12fcefbc3776f68",
        "tarball": "https://registry.npmjs.org/publish/-/publish-0.6.0.tgz"
    },
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
