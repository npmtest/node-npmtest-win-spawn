# npmtest-win-spawn

#### basic test coverage for  win-spawn (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-win-spawn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-win-spawn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-win-spawn.svg)](https://travis-ci.org/npmtest/node-npmtest-win-spawn)

#### Spawn for node.js but in a way that works regardless of which OS you're using

[![NPM](https://nodei.co/npm/win-spawn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/win-spawn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-win-spawn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-win-spawn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-win-spawn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-win-spawn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-win-spawn/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-win-spawn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-win-spawn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-win-spawn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-win-spawn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-win-spawn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-win-spawn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-win-spawn/build/test-report.html](https://npmtest.github.io/node-npmtest-win-spawn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-win-spawn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-win-spawn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-win-spawn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-win-spawn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-win-spawn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-win-spawn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-win-spawn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-win-spawn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "win-spawn",
    "version": "2.0.0",
    "description": "Spawn for node.js but in a way that works regardless of which OS you're using",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/ForbesLindesay/win-spawn.git"
    },
    "bin": {
        "win-spawn": "./bin/win-spawn"
    },
    "devDependencies": {
        "linify": "~1.0.1"
    },
    "scripts": {
        "prepublish": "linify transform bin"
    },
    "author": "ForbesLindesay",
    "license": "BSD"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
