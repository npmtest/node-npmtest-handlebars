# npmtest-handlebars

#### basic test coverage for  [handlebars (v4.0.6)](http://www.handlebarsjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-handlebars.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-handlebars) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-handlebars.svg)](https://travis-ci.org/npmtest/node-npmtest-handlebars)

#### Handlebars provides the power necessary to let you build semantic templates effectively with no frustration

[![NPM](https://nodei.co/npm/handlebars.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/handlebars)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-handlebars/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-handlebars/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-handlebars/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-handlebars/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-handlebars/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-handlebars/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-handlebars/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-handlebars/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-handlebars/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-handlebars/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-handlebars/build/test-report.html](https://npmtest.github.io/node-npmtest-handlebars/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-handlebars/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-handlebars/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-handlebars/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-handlebars/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-handlebars/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-handlebars/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-handlebars/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yehuda Katz"
    },
    "barename": "handlebars",
    "bin": {
        "handlebars": "bin/handlebars"
    },
    "bugs": {
        "url": "https://github.com/wycats/handlebars.js/issues"
    },
    "dependencies": {
        "async": "^1.4.0",
        "optimist": "^0.6.1",
        "source-map": "^0.4.4",
        "uglify-js": "^2.6"
    },
    "description": "Handlebars provides the power necessary to let you build semantic templates effectively with no frustration",
    "devDependencies": {
        "aws-sdk": "^2.1.49",
        "babel-loader": "^5.0.0",
        "babel-runtime": "^5.1.10",
        "benchmark": "~1.0",
        "dustjs-linkedin": "^2.0.2",
        "eco": "~1.1.0-rc-3",
        "grunt": "~0.4.1",
        "grunt-babel": "^5.0.0",
        "grunt-cli": "~0.1.10",
        "grunt-contrib-clean": "0.x",
        "grunt-contrib-concat": "0.x",
        "grunt-contrib-connect": "0.x",
        "grunt-contrib-copy": "0.x",
        "grunt-contrib-requirejs": "0.x",
        "grunt-contrib-uglify": "0.x",
        "grunt-contrib-watch": "0.x",
        "grunt-eslint": "^17.1.0",
        "grunt-saucelabs": "8.x",
        "grunt-webpack": "^1.0.8",
        "istanbul": "^0.3.0",
        "jison": "~0.3.0",
        "mocha": "~1.20.0",
        "mock-stdin": "^0.3.0",
        "mustache": "^2.1.3",
        "semver": "^5.0.1",
        "underscore": "^1.5.1",
        "webpack": "^1.12.6",
        "webpack-dev-server": "^1.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2ce4484850537f9c97a8026d5399b935c4ed4ed7",
        "tarball": "https://registry.npmjs.org/handlebars/-/handlebars-4.0.6.tgz"
    },
    "engines": {
        "node": ">=0.4.7"
    },
    "gitHead": "ad3037cf54132fc5f589134d3bef961a5f751973",
    "homepage": "http://www.handlebarsjs.com/",
    "jspm": {
        "main": "handlebars",
        "directories": {
            "lib": "dist/amd"
        },
        "buildConfig": {
            "minify": true
        }
    },
    "keywords": [
        "handlebars",
        "mustache",
        "template",
        "html"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "erisds"
        },
        {
            "name": "kpdecker"
        },
        {
            "name": "lawnsea"
        },
        {
            "name": "wycats"
        }
    ],
    "name": "handlebars",
    "optionalDependencies": {
        "uglify-js": "^2.6"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wycats/handlebars.js.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "4.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
