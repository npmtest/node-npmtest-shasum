# npmtest-shasum

#### basic test coverage for  [shasum (v1.0.2)](https://github.com/dominictarr/shasum)  [![npm package](https://img.shields.io/npm/v/npmtest-shasum.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shasum) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shasum.svg)](https://travis-ci.org/npmtest/node-npmtest-shasum)

#### Single function that return the sha1sum. Installing this is just a little bit quicker than reading the crypto documentation.

[![NPM](https://nodei.co/npm/shasum.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shasum)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shasum/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shasum/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shasum/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shasum/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shasum/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shasum/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shasum/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shasum/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shasum/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shasum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shasum/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shasum/build/test-report.html](https://npmtest.github.io/node-npmtest-shasum/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shasum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shasum/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shasum/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shasum/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shasum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shasum/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shasum/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shasum/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "'Dominic Tarr'",
        "url": "http://dominictarr.com"
    },
    "browser": {
        "./index.js": "./browser.js"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/shasum/issues"
    },
    "dependencies": {
        "json-stable-stringify": "~0.0.0",
        "sha.js": "~2.4.4"
    },
    "description": "Single function that return the sha1sum. Installing this is just a little bit quicker than reading the crypto documentation.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "e7012310d8f417f4deb5712150e5678b87ae565f",
        "tarball": "https://registry.npmjs.org/shasum/-/shasum-1.0.2.tgz"
    },
    "gitHead": "7cf9cac58f72da0a85d184162ae3dd1176d8e86b",
    "homepage": "https://github.com/dominictarr/shasum",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "shasum",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/shasum.git"
    },
    "scripts": {
        "test": "node test/index.js && node test/index.js browser"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
