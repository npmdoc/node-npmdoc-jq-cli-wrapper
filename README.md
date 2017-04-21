# npmdoc-jq-cli-wrapper

#### api documentation for  [jq-cli-wrapper (v0.4.0)](https://github.com/jamsyoung/jq-cli-wrapper)  [![npm package](https://img.shields.io/npm/v/npmdoc-jq-cli-wrapper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jq-cli-wrapper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jq-cli-wrapper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jq-cli-wrapper)

#### A npm wrapper around the jq cli

[![NPM](https://nodei.co/npm/jq-cli-wrapper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jq-cli-wrapper)

- [https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jq-cli-wrapper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jq-cli-wrapper",
    "version": "0.4.0",
    "description": "A npm wrapper around the jq cli",
    "author": "James Young <jmeyoung@gmail.com> (http://jamsyoung.com/)",
    "main": "",
    "bin": {
        "jq": "./jq-releases/jq"
    },
    "scripts": {
        "generate-changelog": "changelog-maker --group",
        "preinstall": "scripts/link-proper-binary.sh"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jamsyoung/jq-cli-wrapper"
    },
    "bugs": {
        "url": "https://github.com/jamsyoung/jq-cli-wrapper/issues"
    },
    "homepage": "https://github.com/jamsyoung/jq-cli-wrapper",
    "engines": {
        "node": ">=6.9.1"
    },
    "dependencies": {},
    "devDependencies": {
        "changelog-maker": "2.0.0"
    },
    "keywords": [
        "cli-wrapper",
        "jq",
        "json"
    ],
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
