# npmtest-express-mongoose-generator

#### basic test coverage for  express-mongoose-generator (v3.0.2)  [![npm package](https://img.shields.io/npm/v/npmtest-express-mongoose-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-mongoose-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-mongoose-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-express-mongoose-generator)

#### It’s a mongoose model, REST controller and Express router code generator for Express.js 4 application

[![NPM](https://nodei.co/npm/express-mongoose-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-mongoose-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-mongoose-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-mongoose-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-mongoose-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-mongoose-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-mongoose-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-mongoose-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-mongoose-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-mongoose-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-mongoose-generator",
    "version": "3.0.2",
    "description": "It’s a mongoose model, REST controller and Express router code generator for Express.js 4 application",
    "author": "Damien Perrier <damienperrier33@gmail.com>",
    "contributors": [
        "romuloctba"
    ],
    "keywords": [
        "mongodb",
        "mongoose",
        "express",
        "generator",
        "rest",
        "restfull",
        "api",
        "app",
        "web"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/DamienP33/express-mongoose-generator"
    },
    "main": "bin/mongoose-gen",
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "lint": "jshint ./**/*.js ./bin/mongoose-gen",
        "cs": "jscs ./**/*.js ./bin/mongoose-gen"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "license": "MIT",
    "preferGlobal": true,
    "bin": {
        "mongoose-gen": "./bin/mongoose-gen"
    },
    "dependencies": {
        "async": "^0.9.0",
        "commander": "^2.5.0"
    },
    "devDependencies": {
        "jscs": "^2.5.1",
        "jshint": "^2.8.0",
        "mkdirp": "^0.5.0",
        "mocha": "^2.0.1",
        "nexpect": "^0.4.2",
        "rimraf": "^2.2.8"
    },
    "files": [
        "LICENSE",
        "bin/",
        "templates/",
        "lib/"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
