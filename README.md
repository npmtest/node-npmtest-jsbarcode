# npmtest-jsbarcode

#### basic test coverage for  [jsbarcode (v3.6.0)](https://github.com/lindell/JsBarcode#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jsbarcode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsbarcode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsbarcode.svg)](https://travis-ci.org/npmtest/node-npmtest-jsbarcode)

#### JsBarcode is a customizable barcode generator with support for multiple barcode formats.

[![NPM](https://nodei.co/npm/jsbarcode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsbarcode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsbarcode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsbarcode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsbarcode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsbarcode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsbarcode/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jsbarcode/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jsbarcode/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsbarcode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsbarcode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsbarcode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsbarcode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsbarcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsbarcode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsbarcode/build/test-report.html](https://npmtest.github.io/node-npmtest-jsbarcode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsbarcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsbarcode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsbarcode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsbarcode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsbarcode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsbarcode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Johan Lindell"
    },
    "bin": {
        "barcodes": "bin/barcodes",
        "Barcode.js": "bin/barcodes/Barcode.js",
        "codabar": "bin/barcodes/codabar",
        "index.js": "bin/renderers/index.js",
        "CODE128": "bin/barcodes/CODE128",
        "CODE128_AUTO.js": "bin/barcodes/CODE128/CODE128_AUTO.js",
        "CODE128.js": "bin/barcodes/CODE128/CODE128.js",
        "CODE128A.js": "bin/barcodes/CODE128/CODE128A.js",
        "CODE128B.js": "bin/barcodes/CODE128/CODE128B.js",
        "CODE128C.js": "bin/barcodes/CODE128/CODE128C.js",
        "CODE39": "bin/barcodes/CODE39",
        "EAN_UPC": "bin/barcodes/EAN_UPC",
        "ean_encoder.js": "bin/barcodes/EAN_UPC/ean_encoder.js",
        "EAN13.js": "bin/barcodes/EAN_UPC/EAN13.js",
        "EAN2.js": "bin/barcodes/EAN_UPC/EAN2.js",
        "EAN5.js": "bin/barcodes/EAN_UPC/EAN5.js",
        "EAN8.js": "bin/barcodes/EAN_UPC/EAN8.js",
        "UPC.js": "bin/barcodes/EAN_UPC/UPC.js",
        "GenericBarcode": "bin/barcodes/GenericBarcode",
        "index.tmp.js": "bin/barcodes/index.tmp.js",
        "ITF": "bin/barcodes/ITF",
        "ITF14": "bin/barcodes/ITF14",
        "MSI": "bin/barcodes/MSI",
        "checksums.js": "bin/barcodes/MSI/checksums.js",
        "MSI.js": "bin/barcodes/MSI/MSI.js",
        "MSI10.js": "bin/barcodes/MSI/MSI10.js",
        "MSI1010.js": "bin/barcodes/MSI/MSI1010.js",
        "MSI11.js": "bin/barcodes/MSI/MSI11.js",
        "MSI1110.js": "bin/barcodes/MSI/MSI1110.js",
        "pharmacode": "bin/barcodes/pharmacode",
        "exceptions": "bin/exceptions",
        "ErrorHandler.js": "bin/exceptions/ErrorHandler.js",
        "exceptions.js": "bin/exceptions/exceptions.js",
        "help": "bin/help",
        "fixOptions.js": "bin/help/fixOptions.js",
        "getOptionsFromElement.js": "bin/help/getOptionsFromElement.js",
        "getRenderProperties.js": "bin/help/getRenderProperties.js",
        "linearizeEncodings.js": "bin/help/linearizeEncodings.js",
        "merge.js": "bin/help/merge.js",
        "optionsFromStrings.js": "bin/help/optionsFromStrings.js",
        "JsBarcode.js": "bin/JsBarcode.js",
        "options": "bin/options",
        "defaults.js": "bin/options/defaults.js",
        "renderers": "bin/renderers",
        "canvas.js": "bin/renderers/canvas.js",
        "object.js": "bin/renderers/object.js",
        "shared.js": "bin/renderers/shared.js",
        "svg.js": "bin/renderers/svg.js"
    },
    "bugs": {
        "url": "https://github.com/lindell/JsBarcode/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                "JsBarcode.js",
                "barcodes"
            ],
            "data-cover-never": [
                "GenericBarcode",
                "node_modules"
            ]
        }
    },
    "dependencies": {},
    "description": "JsBarcode is a customizable barcode generator with support for multiple barcode formats.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.5",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-es2015-classes": "^6.6.5",
        "babel-plugin-transform-runtime": "^6.6.0",
        "babel-preset-es2015": "^6.6.0",
        "blanket": "^1.2.3",
        "canvas": "^1.0.0",
        "coveralls": "^2.11.6",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-bump": "^2.1.0",
        "gulp-clean": "^0.3.2",
        "gulp-concat": "^2.6.0",
        "gulp-eslint": "^3.0.1",
        "gulp-git": "^1.7.1",
        "gulp-header": "^1.7.1",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.5.3",
        "gzip-size": "^3.0.0",
        "mocha": "^3.0.0",
        "mocha-lcov-reporter": "^1.2.0",
        "publish-release": "^1.2.0",
        "request": "^2.72.0",
        "run-sequence": "^1.1.5",
        "webpack": "^2.1.0-beta.5",
        "webpack-stream": "^3.1.0"
    },
    "directories": {
        "example": "example",
        "test": "test",
        "lib": "src",
        "bin": "bin"
    },
    "dist": {
        "shasum": "507b4fb02d9545ddd71aa173e71e92d7805d996f",
        "tarball": "https://registry.npmjs.org/jsbarcode/-/jsbarcode-3.6.0.tgz"
    },
    "gitHead": "c71f5a5e40b240ebbde82c162dfa737d2e7aaa23",
    "homepage": "https://github.com/lindell/JsBarcode#readme",
    "keywords": [
        "barcode",
        "canvas",
        "code128",
        "upc",
        "ean",
        "itf",
        "msi",
        "pharmacode"
    ],
    "license": "MIT",
    "main": "./bin/JsBarcode.js",
    "maintainers": [
        {
            "name": "lindell"
        }
    ],
    "name": "jsbarcode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lindell/JsBarcode.git"
    },
    "scripts": {
        "build": "gulp compile",
        "coverage": "mocha test/node/ -r blanket -R html-cov > test/coverage.html",
        "coveralls": "NODE_ENV=test YOURPACKAGE_COVERAGE=1 ./node_modules/.bin/mocha test/node/ --require blanket --reporter mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js",
        "test": "gulp babel && node_modules/mocha/bin/mocha test/node/ -R spec"
    },
    "typings": "./jsbarcode.d.ts",
    "version": "3.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
