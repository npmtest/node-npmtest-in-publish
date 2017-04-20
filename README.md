# npmtest-in-publish

#### basic test coverage for  [in-publish (v2.0.0)](https://github.com/iarna/in-publish)  [![npm package](https://img.shields.io/npm/v/npmtest-in-publish.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-in-publish) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-in-publish.svg)](https://travis-ci.org/npmtest/node-npmtest-in-publish)

#### Detect if we were run as a result of `npm publish`

[![NPM](https://nodei.co/npm/in-publish.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/in-publish)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-in-publish/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-in-publish/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-in-publish/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-in-publish/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-in-publish/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-in-publish/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-in-publish/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-in-publish/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-in-publish/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-in-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-in-publish/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-in-publish/build/test-report.html](https://npmtest.github.io/node-npmtest-in-publish/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-in-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-in-publish/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-in-publish/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-in-publish/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-in-publish/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-in-publish/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-in-publish/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-in-publish/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "in-publish",
    "version": "2.0.0",
    "description": "Detect if we were run as a result of 'npm publish'",
    "main": "index.js",
    "bin": {
        "in-publish": "in-publish.js",
        "in-install": "in-install.js",
        "not-in-publish": "not-in-publish.js",
        "not-in-install": "not-in-install.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/iarna/in-publish"
    },
    "author": "Rebecca Turner <me@re-becca.org>",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/iarna/in-publish/issues"
    },
    "homepage": "https://github.com/iarna/in-publish"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
