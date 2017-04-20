# npmtest-html5-to-pdf

#### basic test coverage for  [html5-to-pdf (v2.2.1)](https://github.com/peterdemartini/html5-to-pdf)  [![npm package](https://img.shields.io/npm/v/npmtest-html5-to-pdf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html5-to-pdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html5-to-pdf.svg)](https://travis-ci.org/npmtest/node-npmtest-html5-to-pdf)

#### HTML5 to PDF converter

[![NPM](https://nodei.co/npm/html5-to-pdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html5-to-pdf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html5-to-pdf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html5-to-pdf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html5-to-pdf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html5-to-pdf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html5-to-pdf/build/test-report.html](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html5-to-pdf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html5-to-pdf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html5-to-pdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html5-to-pdf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html5-to-pdf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Peter DeMartini"
    },
    "bin": {
        "html5-to-pdf": "./command.js"
    },
    "bugs": {
        "url": "https://github.com/peterdemartini/html5-to-pdf/issues"
    },
    "dependencies": {
        "coffee-script": "^1.12.4",
        "colors": "^1.1.2",
        "commander": "^2.8.1",
        "debug": "^2.6.1",
        "express": "^4.14.1",
        "fs-extra": "^2.0.0",
        "lodash": "^4.17.4",
        "nightmare": "^2.10.0",
        "server-destroy": "^1.0.1",
        "tmp": "^0.0.31"
    },
    "description": "HTML5 to PDF converter",
    "devDependencies": {
        "chai": "^3.0.0",
        "mocha": "^3.2.0",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5ba57ed5b6ca91826c9a00c17104a54c73719d53",
        "tarball": "https://registry.npmjs.org/html5-to-pdf/-/html5-to-pdf-2.2.1.tgz"
    },
    "gitHead": "51239bb3d406ca75863cf8b406c96ecf7164c929",
    "homepage": "https://github.com/peterdemartini/html5-to-pdf",
    "keywords": [
        "html5",
        "pdf",
        "convert",
        "template",
        "generator"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/peterdemartini/html5-to-pdf/blob/master/LICENSE"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "peterdemartini"
        }
    ],
    "name": "html5-to-pdf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/peterdemartini/html5-to-pdf.git"
    },
    "scripts": {
        "start": "node index.js",
        "test": "mocha"
    },
    "version": "2.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
