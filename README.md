# npmtest-babylon

#### basic test coverage for  [babylon (v6.16.1)](https://babeljs.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-babylon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babylon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babylon.svg)](https://travis-ci.org/npmtest/node-npmtest-babylon)

#### A JavaScript parser

[![NPM](https://nodei.co/npm/babylon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babylon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babylon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babylon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babylon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babylon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babylon/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babylon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babylon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babylon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babylon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babylon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babylon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babylon/build/test-report.html](https://npmtest.github.io/node-npmtest-babylon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babylon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babylon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babylon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babylon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babylon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babylon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babylon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babylon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian McKenzie"
    },
    "ava": {
        "files": [
            "test/*.js"
        ],
        "source": [
            "src/**/*.js",
            "bin/**/*.js"
        ]
    },
    "bin": {
        "babylon": "./bin/babylon.js"
    },
    "bugs": {
        "url": "https://github.com/babel/babylon/issues"
    },
    "contributors": [
        {
            "name": "List of Acorn contributors. Updated before every release."
        },
        {
            "name": "Adrian Rakovsky"
        },
        {
            "name": "Alistair Braidwood"
        },
        {
            "name": "Andres Suarez"
        },
        {
            "name": "Aparajita Fishman"
        },
        {
            "name": "Arian Stolwijk"
        },
        {
            "name": "Artem Govorov"
        },
        {
            "name": "Brandon Mills"
        },
        {
            "name": "Charles Hughes"
        },
        {
            "name": "Conrad Irwin"
        },
        {
            "name": "David Bonnet"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Gilad Peleg"
        },
        {
            "name": "impinball"
        },
        {
            "name": "Ingvar Stepanyan"
        },
        {
            "name": "Jesse McCarthy"
        },
        {
            "name": "Jiaxing Wang"
        },
        {
            "name": "Joel Kemp"
        },
        {
            "name": "Johannes Herr"
        },
        {
            "name": "Jürg Lehni"
        },
        {
            "name": "keeyipchan"
        },
        {
            "name": "Kevin Kwok"
        },
        {
            "name": "krator"
        },
        {
            "name": "Marijn Haverbeke"
        },
        {
            "name": "Martin Carlberg"
        },
        {
            "name": "Mathias Bynens"
        },
        {
            "name": "Mathieu 'p01' Henri"
        },
        {
            "name": "Max Schaefer"
        },
        {
            "name": "Max Zerzouri"
        },
        {
            "name": "Mihai Bazon"
        },
        {
            "name": "Mike Rennie"
        },
        {
            "name": "Nick Fitzgerald"
        },
        {
            "name": "Oskar Schöldström"
        },
        {
            "name": "Paul Harper"
        },
        {
            "name": "Peter Rust"
        },
        {
            "name": "PlNG"
        },
        {
            "name": "r-e-d"
        },
        {
            "name": "Rich Harris"
        },
        {
            "name": "Sebastian McKenzie"
        },
        {
            "name": "zsjforcn"
        }
    ],
    "dependencies": {},
    "description": "A JavaScript parser",
    "devDependencies": {
        "ava": "^0.17.0",
        "babel-cli": "^6.14.0",
        "babel-eslint": "^7.0.0",
        "babel-helper-fixtures": "^6.9.0",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-plugin-istanbul": "^3.0.0",
        "babel-plugin-transform-flow-strip-types": "^6.14.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-stage-0": "^6.5.0",
        "chalk": "^1.1.3",
        "codecov": "^1.0.1",
        "cross-env": "^2.0.0",
        "eslint": "^3.7.1",
        "eslint-config-babel": "^6.0.0",
        "eslint-plugin-flowtype": "^2.20.0",
        "flow-bin": "^0.38.0",
        "nyc": "^10.0.0",
        "rimraf": "^2.5.4",
        "rollup": "^0.41.0",
        "rollup-plugin-babel": "^2.6.1",
        "rollup-plugin-node-resolve": "^2.0.0",
        "unicode-9.0.0": "~0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "30c5a22f481978a9e7f8cdfdf496b11d94b404d3",
        "tarball": "https://registry.npmjs.org/babylon/-/babylon-6.16.1.tgz"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "539d345d9b23ae1331a4beb13e2de91b0a9020e6",
    "greenkeeper": {
        "ignore": [
            "cross-env"
        ]
    },
    "homepage": "https://babeljs.io/",
    "keywords": [
        "babel",
        "javascript",
        "parser",
        "babylon"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "amasad"
        },
        {
            "name": "danez"
        },
        {
            "name": "gabelevi"
        },
        {
            "name": "hzoo"
        },
        {
            "name": "jmm"
        },
        {
            "name": "loganfsmyth"
        },
        {
            "name": "sebmck"
        },
        {
            "name": "thejameskyle"
        }
    ],
    "name": "babylon",
    "nyc": {
        "include": [
            "src/**/*.js",
            "bin/**/*.js"
        ],
        "sourceMap": false,
        "instrument": false
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/babel/babylon.git"
    },
    "scripts": {
        "build": "npm run clean && rollup -c",
        "changelog": "git log 'git describe --tags --abbrev=0'..HEAD --pretty=format:' * %s (%an)' | grep -v 'Merge pull request'",
        "clean": "rimraf lib",
        "coverage": "nyc report --reporter=json && codecov -f coverage/coverage-final.json",
        "flow": "flow",
        "lint": "eslint src bin",
        "prepublish": "cross-env BABEL_ENV=production npm run build",
        "preversion": "npm run test && npm run changelog",
        "test": "npm run lint && npm run flow && npm run build -- -m && npm run test-only",
        "test-ci": "nyc npm run test-only",
        "test-only": "ava",
        "watch": "npm run clean && cross-env BABEL_ENV=watch babel src --out-dir lib --watch"
    },
    "version": "6.16.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
