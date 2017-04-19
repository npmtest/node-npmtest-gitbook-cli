# npmtest-gitbook-cli

#### basic test coverage for  [gitbook-cli (v2.3.0)](https://www.gitbook.com)  [![npm package](https://img.shields.io/npm/v/npmtest-gitbook-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gitbook-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gitbook-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-gitbook-cli)

#### CLI to generate books and documentation using gitbook

[![NPM](https://nodei.co/npm/gitbook-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gitbook-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gitbook-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitbook-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gitbook-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gitbook-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gitbook-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gitbook-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gitbook-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gitbook-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gitbook-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitbook-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gitbook-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gitbook-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-gitbook-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gitbook-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gitbook-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gitbook-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gitbook-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gitbook-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gitbook-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gitbook-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gitbook-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "FriendCode Inc."
    },
    "bin": {
        "gitbook": "./bin/gitbook.js"
    },
    "bugs": {
        "url": "https://github.com/GitbookIO/gitbook-cli/issues"
    },
    "contributors": [
        {
            "name": "Aaron O'Mullan"
        },
        {
            "name": "Samy Pessé"
        }
    ],
    "dependencies": {
        "bash-color": "0.0.4",
        "commander": "2.9.0",
        "fs-extra": "0.26.5",
        "lodash": "4.5.1",
        "npm": "3.7.5",
        "npmi": "1.0.1",
        "optimist": "0.6.1",
        "q": "1.4.1",
        "semver": "5.1.0",
        "tmp": "0.0.28",
        "user-home": "2.0.0"
    },
    "description": "CLI to generate books and documentation using gitbook",
    "devDependencies": {
        "gitbook": "2.5.0-beta.1",
        "mocha": "2.4.5",
        "should": "8.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "01a360de71a48e53277ed2cb1abf6c60a0901576",
        "tarball": "https://registry.npmjs.org/gitbook-cli/-/gitbook-cli-2.3.0.tgz"
    },
    "gitHead": "e940bb338a0cdee2398d3d9c8a7781e772b947e3",
    "homepage": "https://www.gitbook.com",
    "license": "Apache-2.0",
    "main": "bin/gitbook.js",
    "maintainers": [
        {
            "name": "samypesse"
        }
    ],
    "name": "gitbook-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/GitbookIO/gitbook-cli.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --recursive --bail"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
