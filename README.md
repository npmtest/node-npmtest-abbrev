# npmtest-abbrev

#### basic test coverage for  [abbrev (1.1.1)](https://github.com/isaacs/abbrev-js#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-abbrev.svg)](https://travis-ci.org/npmtest/node-npmtest-abbrev)

#### Like ruby's abbrev module, but in js

[![NPM](https://nodei.co/npm/abbrev.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/abbrev)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-abbrev/tree/alpha)|
|--:|:--|
| coverage : | [![coverage](https://npmtest.github.io/node-npmtest-abbrev/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-abbrev/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-abbrev/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-abbrev/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-abbrev/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-abbrev/build/app) || build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-abbrev/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-abbrev/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-abbrev/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-abbrev/build/coverage.html/index.html)

[![coverage](https://npmtest.github.io/node-npmtest-abbrev/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-abbrev/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-abbrev/build/test-report.html](https://npmtest.github.io/node-npmtest-abbrev/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-abbrev/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-abbrev/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-abbrev/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-abbrev/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-abbrev/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-abbrev/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-abbrev/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-abbrev/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter"
    },
    "bugs": {
        "url": "https://github.com/isaacs/abbrev-js/issues"
    },
    "dependencies": {},
    "description": "Like ruby's abbrev module, but in js",
    "devDependencies": {
        "tap": "^10.1"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-nne9/IiQ/hzIhY6pdDnbBtz7DjPTKrY00P/zvPSm5pOFkl6xuGrGnXn/VtTNNfNtAfZ9/1RtehkszU9qcTii0Q==",
        "shasum": "f8f2c887ad10bf67f634f005b6987fed3179aac8",
        "tarball": "https://registry.npmjs.org/abbrev/-/abbrev-1.1.1.tgz"
    },
    "files": [
        "abbrev.js"
    ],
    "gitHead": "a9ee72ebc8fe3975f1b0c7aeb3a8f2a806a432eb",
    "homepage": "https://github.com/isaacs/abbrev-js#readme",
    "license": "ISC",
    "main": "abbrev.js",
    "maintainers": [
        {
            "name": "gabra"
        },
        {
            "name": "isaacs"
        }
    ],
    "name": "abbrev",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/isaacs/abbrev-js.git"
    },
    "scripts": {
        "postpublish": "git push origin --all; git push origin --tags",
        "postversion": "npm publish",
        "preversion": "npm test",
        "test": "tap test.js --100"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
