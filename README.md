# npmtest-typeset

#### basic test coverage for  [typeset (v0.2.2)](https://github.com/davidmerfield/Typeset.js)  [![npm package](https://img.shields.io/npm/v/npmtest-typeset.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-typeset) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-typeset.svg)](https://travis-ci.org/npmtest/node-npmtest-typeset)

#### Typesetting for the web

[![NPM](https://nodei.co/npm/typeset.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/typeset)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-typeset/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-typeset/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-typeset/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-typeset/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-typeset/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-typeset/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-typeset/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-typeset/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-typeset/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-typeset/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-typeset/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-typeset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-typeset/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-typeset/build/test-report.html](https://npmtest.github.io/node-npmtest-typeset/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-typeset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-typeset/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-typeset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-typeset/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-typeset/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-typeset/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Merfield"
    },
    "bin": {
        "typeset-js": "src/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/davidmerfield/Typeset.js/issues"
    },
    "dependencies": {
        "cheerio": "^0.19.0",
        "commander": "^2.8.1",
        "html-entities": "^1.1.2",
        "hypher": "^0.2.3"
    },
    "description": "Typesetting for the web",
    "devDependencies": {
        "chai": "^3.2.0",
        "html-minifier": "^0.7.2",
        "mocha": "^2.2.5",
        "webpack": "^1.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9804deacff428159d2aabc9e82bd9fbd5236a3ea",
        "tarball": "https://registry.npmjs.org/typeset/-/typeset-0.2.2.tgz"
    },
    "homepage": "https://github.com/davidmerfield/Typeset.js",
    "keywords": [
        "type",
        "typeset",
        "typography",
        "dropcap",
        "smallcap",
        "hyphenation"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "davidmerfield"
        }
    ],
    "name": "typeset",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/davidmerfield/Typeset.js.git"
    },
    "scripts": {
        "build": "npm run clean; npm run build-dev; npm run build-prod",
        "build-dev": "./node_modules/webpack/bin/webpack.js",
        "build-prod": "PROD=1 ./node_modules/webpack/bin/webpack.js",
        "clean": "rm -rf build/",
        "test": "mocha -u bdd -R spec -t 500 --recursive",
        "watch": "mocha src/ test/ -u bdd -R spec -t 500 --recursive --watch"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
