# npmtest-zerorpc

#### basic test coverage for  zerorpc (v0.9.7)  [![npm package](https://img.shields.io/npm/v/npmtest-zerorpc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zerorpc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zerorpc.svg)](https://travis-ci.org/npmtest/node-npmtest-zerorpc)

#### A port of ZeroRPC to node.js

[![NPM](https://nodei.co/npm/zerorpc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zerorpc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zerorpc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zerorpc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zerorpc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zerorpc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zerorpc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zerorpc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zerorpc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zerorpc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zerorpc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zerorpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zerorpc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zerorpc/build/test-report.html](https://npmtest.github.io/node-npmtest-zerorpc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zerorpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zerorpc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zerorpc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zerorpc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zerorpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zerorpc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zerorpc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zerorpc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "zerorpc",
    "version": "0.9.7",
    "main": "./index.js",
    "author": "François-Xavier Bourlet <bombela+zerorpc@gmail.com>",
    "description": "A port of ZeroRPC to node.js",
    "contributors": [
        {
            "name": "Francois-Xavier Bourlet"
        },
        {
            "name": "Yusuf Simonson"
        }
    ],
    "scripts": {
        "test": "./node_modules/.bin/nodeunit test"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/0rpc/zerorpc-node"
    },
    "keywords": [
        "zerorpc",
        "rpc",
        "distributed",
        "communication"
    ],
    "dependencies": {
        "msgpack": "1.0.2",
        "underscore": "1.3.3",
        "uuid": "^3.0.0",
        "zmq": "2.x"
    },
    "devDependencies": {
        "nodeunit": "0.9.1",
        "temp": "0.8.1"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
