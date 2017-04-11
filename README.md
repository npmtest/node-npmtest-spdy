# test coverage for  [spdy (v3.4.4)](https://github.com/indutny/node-spdy)  [![npm package](https://img.shields.io/npm/v/npmtest-spdy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spdy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spdy.svg)](https://travis-ci.org/npmtest/node-npmtest-spdy)
#### Implementation of the SPDY protocol on node.js.

[![NPM](https://nodei.co/npm/spdy.png?downloads=true)](https://www.npmjs.com/package/spdy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spdy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spdy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spdy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spdy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spdy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spdy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spdy/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spdy/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-spdy/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-spdy/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-spdy%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spdy/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spdy/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-spdy%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spdy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spdy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spdy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fedor Indutny",
        "email": "fedor.indutny@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/indutny/node-spdy/issues",
        "email": "node-spdy+bugs@indutny.com"
    },
    "contributors": [
        {
            "name": "Chris Storm",
            "email": "github@eeecooks.com"
        },
        {
            "name": "François de Metz",
            "email": "francois@2metz.fr"
        },
        {
            "name": "Ilya Grigorik",
            "email": "ilya@igvita.com"
        },
        {
            "name": "Roberto Peon"
        },
        {
            "name": "Tatsuhiro Tsujikawa"
        },
        {
            "name": "Jesse Cravens",
            "email": "jesse.cravens@gmail.com"
        }
    ],
    "dependencies": {
        "debug": "^2.2.0",
        "handle-thing": "^1.2.4",
        "http-deceiver": "^1.2.4",
        "select-hose": "^2.0.0",
        "spdy-transport": "^2.0.15"
    },
    "description": "Implementation of the SPDY protocol on node.js.",
    "devDependencies": {
        "jscs": "^1.13.1",
        "jshint": "^2.8.0",
        "mocha": "^2.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "e0406407ca90ff01b553eb013505442649f5a819",
        "tarball": "https://registry.npmjs.org/spdy/-/spdy-3.4.4.tgz"
    },
    "engines": [
        "node >= 0.7.0"
    ],
    "gitHead": "52dc157eef87d7d2bb7b39ab25fdcfee45f88dd9",
    "homepage": "https://github.com/indutny/node-spdy",
    "keywords": [
        "spdy"
    ],
    "license": "MIT",
    "main": "./lib/spdy",
    "maintainers": [
        {
            "name": "fedor.indutny",
            "email": "fedor.indutny@gmail.com"
        },
        {
            "name": "indutny",
            "email": "fedor@indutny.com"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        }
    ],
    "name": "spdy",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/indutny/node-spdy.git"
    },
    "scripts": {
        "test": "jscs lib/**/*.js test/*.js && jshint lib/**/*.js && mocha --reporter=spec test/*-test.js"
    },
    "version": "3.4.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
