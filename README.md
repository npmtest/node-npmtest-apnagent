# npmtest-apnagent

#### basic test-coverage for  [apnagent (v1.1.3)](http://apnagent.qualiancy.com)  [![npm package](https://img.shields.io/npm/v/npmtest-apnagent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apnagent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apnagent.svg)](https://travis-ci.org/npmtest/node-npmtest-apnagent)

#### Node adapter for Apple Push Notification (APN) service.

[![NPM](https://nodei.co/npm/apnagent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apnagent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apnagent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apnagent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apnagent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apnagent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apnagent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apnagent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apnagent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apnagent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apnagent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apnagent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apnagent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apnagent/build/test-report.html](https://npmtest.github.io/node-npmtest-apnagent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apnagent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apnagent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apnagent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apnagent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apnagent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apnagent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apnagent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apnagent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake Luer",
        "url": "http://qualiancy.com"
    },
    "bugs": {
        "url": "https://github.com/qualiancy/apnagent/issues"
    },
    "contributors": [
        {
            "name": "Jake Luer"
        }
    ],
    "dependencies": {
        "breeze-async": "0.1.x",
        "breeze-queue": "0.4.x",
        "drip": "1.1.x",
        "facet": "0.4.x",
        "lotus": "~1.0.1",
        "sherlock": "*",
        "tea-error": "0.1.x",
        "tea-extend": "0.2.x",
        "tea-inherits": "0.1.x",
        "tea-ms": "0.1.x"
    },
    "description": "Node adapter for Apple Push Notification (APN) service.",
    "devDependencies": {
        "chai": "*",
        "chai-spies": "*",
        "mocha": "*",
        "serve": "^1.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "da24d1039e3140de61b93f859ebd6784fbf8fb27",
        "tarball": "https://registry.npmjs.org/apnagent/-/apnagent-1.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "d077c58f02b3d754e97a320734de5d135e14c318",
    "homepage": "http://apnagent.qualiancy.com",
    "keywords": [
        "apn",
        "apple",
        "push",
        "notifications",
        "ios",
        "iphone",
        "ipad"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "jakeluer"
        }
    ],
    "name": "apnagent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/qualiancy/apnagent.git"
    },
    "scripts": {
        "serve": "serve -L -D --compress docs/out",
        "test": "make test"
    },
    "version": "1.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
