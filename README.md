# npmdoc-remap-istanbul

#### api documentation for  [remap-istanbul (v0.9.5)](https://github.com/SitePen/remap-istanbul)  [![npm package](https://img.shields.io/npm/v/npmdoc-remap-istanbul.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-remap-istanbul) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-remap-istanbul.svg)](https://travis-ci.org/npmdoc/node-npmdoc-remap-istanbul)

#### A tool for remapping Istanbul coverage via Source Maps

[![NPM](https://nodei.co/npm/remap-istanbul.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/remap-istanbul)

- [https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-remap-istanbul/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "remap-istanbul": "./bin/remap-istanbul.js"
    },
    "bugs": {
        "url": "https://github.com/SitePen/remap-istanbul"
    },
    "dependencies": {
        "amdefine": "^1.0.0",
        "gulp-util": "3.0.7",
        "istanbul": "0.4.5",
        "minimatch": "^3.0.3",
        "source-map": ">=0.5.6",
        "through2": "2.0.1"
    },
    "description": "A tool for remapping Istanbul coverage via Source Maps",
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-core": "^6.17.0",
        "babel-plugin-transform-es2015-modules-amd": "^6.18.0",
        "babel-preset-es2015": "^6.16.0",
        "codecov.io": "0.1.6",
        "eslint": "^3.7.0",
        "eslint-config-airbnb-base": "^10.0.1",
        "eslint-plugin-import": "^2.0.1",
        "grunt": "^1.0.1",
        "gulp": "3.9.1",
        "intern": "^3.3.0",
        "rimraf": "^2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a18617b1f31eec5a7dbee77538298b775606aaa8",
        "tarball": "https://registry.npmjs.org/remap-istanbul/-/remap-istanbul-0.9.5.tgz"
    },
    "gitHead": "1e3046dffc415f0e76528a4ec35a85556c7f2d97",
    "homepage": "https://github.com/SitePen/remap-istanbul",
    "keywords": [
        "gulpplugin",
        "gruntplugin",
        "source-map",
        "istanbul",
        "coverage"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/main.js",
    "maintainers": [
        {
            "name": "sitepen"
        }
    ],
    "name": "remap-istanbul",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SitePen/remap-istanbul.git"
    },
    "scripts": {
        "build": "rimraf lib && babel src --out-dir ./lib --source-maps",
        "lint": "eslint ./src/",
        "prepublish": "npm run build",
        "test": "tests/run.sh"
    },
    "version": "0.9.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
