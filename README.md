# npmtest-sails-migrations

#### basic test coverage for  [sails-migrations (v2.0.10)](https://github.com/BlueHotDog/sails-migrations)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-migrations.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-migrations) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-migrations.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-migrations)

#### The missing, migrations, arm of the octopus

[![NPM](https://nodei.co/npm/sails-migrations.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-migrations)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-migrations/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-migrations/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-migrations/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-migrations/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-migrations/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sails-migrations/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sails-migrations/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-migrations/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-migrations/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-migrations/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-migrations/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-migrations/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-migrations/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-migrations/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-migrations/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-migrations/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-migrations/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-migrations/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-migrations/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-migrations/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-migrations/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-migrations/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-migrations/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "BlueHotDog"
    },
    "bin": {
        "sails-migrations": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/BlueHotDog/sails-migrations/issues"
    },
    "contributors": [
        {
            "name": "BlueHotDog"
        },
        {
            "name": "Itay Adler"
        }
    ],
    "dependencies": {
        "bluebird": "1.1.1",
        "chalk": "0.5.1",
        "cli-table": "0.3.1",
        "commander": "2.6.0",
        "interpret": "0.3.7",
        "knex": "^0.11.3",
        "liftoff": "^2.2.1",
        "lodash": "2.4",
        "mysql": "2.5.4",
        "optimist": "0.6.1",
        "pg": "4.5.5",
        "tildify": "1.0.0"
    },
    "description": "The missing, migrations, arm of the octopus",
    "devDependencies": {
        "chai": "~1.8",
        "coffee-script": "^1.8.0",
        "mocha": "~1.16",
        "shelljs": "^0.3.0",
        "should": "~2.1",
        "sinon": "~1.7"
    },
    "directories": {},
    "dist": {
        "shasum": "e911cafed73ed7e584ecc29a91a52a6517e31e2c",
        "tarball": "https://registry.npmjs.org/sails-migrations/-/sails-migrations-2.0.10.tgz"
    },
    "files": [
        "index.js",
        "lib",
        "bin",
        "tasks",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "2f75f4cc027c0cd02d6df0501d3b72aecaec42db",
    "homepage": "https://github.com/BlueHotDog/sails-migrations",
    "keywords": [
        "sails",
        "sailsjs",
        "sails.js",
        "migrations",
        "waterline"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://sails.mit-license.org/"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "bluehotdog"
        },
        {
            "name": "itayadler"
        },
        {
            "name": "joaosa"
        }
    ],
    "name": "sails-migrations",
    "optionalDependencies": {
        "mysql": "2.5.4",
        "pg": "4.5.5"
    },
    "peerDependencies": {
        "sails": ">= 0.9 < 1"
    },
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/BlueHotDog/sails-migrations.git"
    },
    "scripts": {
        "start": "node index.js",
        "test": "./bin/run_tests.js"
    },
    "version": "2.0.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
