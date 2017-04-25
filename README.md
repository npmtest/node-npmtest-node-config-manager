# npmtest-node-config-manager

#### basic test coverage for  [node-config-manager (v1.2.0)](https://github.com/Valko54/node-config-manager#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-config-manager.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-config-manager) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-config-manager.svg)](https://travis-ci.org/npmtest/node-npmtest-node-config-manager)

#### A configuration manager for NodeJS. It helps you to organize your project and the different configurations of your environments.

[![NPM](https://nodei.co/npm/node-config-manager.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-config-manager)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-config-manager/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-config-manager/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-config-manager/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-config-manager/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-config-manager/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-config-manager/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-config-manager/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-config-manager/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-config-manager/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-config-manager/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-config-manager/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-config-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-config-manager/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-config-manager/build/test-report.html](https://npmtest.github.io/node-npmtest-node-config-manager/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-config-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-config-manager/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-config-manager/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-config-manager/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Damien Picard",
        "url": "https://github.com/valko54"
    },
    "bugs": {
        "url": "https://github.com/Valko54/node-config-manager/issues"
    },
    "contributors": [
        {
            "name": "Laurine Schuster",
            "url": "https://github.com/lsr57"
        },
        {
            "name": "Antoine Detante",
            "url": "https://github.com/adetante"
        }
    ],
    "dependencies": {
        "debug": "2.6.1",
        "js-yaml": "3.8.1"
    },
    "description": "A configuration manager for NodeJS. It helps you to organize your project and the different configurations of your environments.",
    "devDependencies": {
        "chai": "3.5.0",
        "coveralls": "2.11.16",
        "istanbul": "0.4.5",
        "jshint": "2.9.4",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "rewire": "2.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "52c4128b85a5728117c82f55f7083ccb45ecc547",
        "tarball": "https://registry.npmjs.org/node-config-manager/-/node-config-manager-1.2.0.tgz"
    },
    "gitHead": "60b3cab0c51d6b8e40e45ef6f96d5345a0e91d4b",
    "homepage": "https://github.com/Valko54/node-config-manager#readme",
    "keywords": [
        "util",
        "config",
        "environment",
        "manager"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "valko54"
        }
    ],
    "name": "node-config-manager",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Valko54/node-config-manager.git"
    },
    "scripts": {
        "pretest": "./node_modules/jshint/bin/jshint .",
        "test": "NODE_ENV='test' ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha test",
        "test-on-travis": "NODE_ENV='test' ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha test && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
