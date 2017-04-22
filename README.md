# npmtest-polyjuice

#### basic test coverage for  [polyjuice (v2.2.0)](https://github.com/brenolf/polyjuice)  [![npm package](https://img.shields.io/npm/v/npmtest-polyjuice.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-polyjuice) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-polyjuice.svg)](https://travis-ci.org/npmtest/node-npmtest-polyjuice)

#### A utility to converts JSHint and JSCS files into ESLint and vice-versa

[![NPM](https://nodei.co/npm/polyjuice.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/polyjuice)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-polyjuice/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-polyjuice/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-polyjuice/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-polyjuice/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-polyjuice/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-polyjuice/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-polyjuice/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-polyjuice/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-polyjuice/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-polyjuice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-polyjuice/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-polyjuice/build/test-report.html](https://npmtest.github.io/node-npmtest-polyjuice/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-polyjuice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-polyjuice/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-polyjuice/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-polyjuice/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-polyjuice/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-polyjuice/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-polyjuice/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-polyjuice/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Breno Lima de Freitas",
        "url": "https://breno.io/"
    },
    "bin": {
        "polyjuice": "./lib/bin.js"
    },
    "bugs": {
        "url": "https://github.com/brenolf/polyjuice/issues"
    },
    "dependencies": {
        "eslint": "^2.8.0",
        "object-assign": "^4.1.0",
        "strip-json-comments": "^1.0.4",
        "yargs": "^3.32.0"
    },
    "description": "A utility to converts JSHint and JSCS files into ESLint and vice-versa",
    "devDependencies": {
        "chai": "^3.2.0",
        "coveralls": "^2.11.4",
        "jscs": "^2.0.0",
        "jshint": "^2.8.0",
        "jshint-stylish": "^2.0.1",
        "mocha": "^2.2.5",
        "mocha-lcov-reporter": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c15aff3ff91ef13296bc45aa1ef35cd6c4aa5aa2",
        "tarball": "https://registry.npmjs.org/polyjuice/-/polyjuice-2.2.0.tgz"
    },
    "gitHead": "6e4938d3227cb819a7f90db795691719968b8497",
    "homepage": "https://github.com/brenolf/polyjuice",
    "keywords": [
        "linter",
        "jscs",
        "jshint",
        "eslint",
        "transpiler",
        "converter"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "brenolf"
        }
    ],
    "name": "polyjuice",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/brenolf/polyjuice.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- --opts mocha.opts",
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha -- --opts mocha.opts --report lcovonly && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "lint": "eslint -c ./.eslintrc lib test",
        "mocha": "_mocha --opts mocha.opts",
        "test": "npm run lint && npm run mocha"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
