# npmdoc-svg-captcha

#### api documentation for  [svg-captcha (v1.3.4)](https://github.com/steambap/svg-captcha#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-svg-captcha.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-svg-captcha) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-svg-captcha.svg)](https://travis-ci.org/npmdoc/node-npmdoc-svg-captcha)

#### generate svg captcha in node.js or express.js

[![NPM](https://nodei.co/npm/svg-captcha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg-captcha)

- [https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "svg-captcha",
    "version": "1.3.4",
    "description": "generate svg captcha in node.js or express.js",
    "main": "index.js",
    "scripts": {
        "test": "mocha test/test.js",
        "lint": "xo",
        "test:visual": "node test/visual.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/steambap/svg-captcha.git"
    },
    "keywords": [
        "captcha",
        "svg",
        "node captcha",
        "captcha generator",
        "captcha alternative"
    ],
    "author": {
        "name": "Weilin Shi",
        "url": "weilinshi.org"
    },
    "engines": {
        "node": ">=4.x"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/steambap/svg-captcha/issues"
    },
    "homepage": "https://github.com/steambap/svg-captcha#readme",
    "dependencies": {
        "opentype.js": "^0.6.9"
    },
    "devDependencies": {
        "fs-extra": "^2.1.2",
        "mocha": "^3.2.0",
        "xo": "^0.18.1"
    },
    "xo": {
        "esnext": true,
        "envs": [
            "mocha"
        ]
    },
    "typings": "index.d.ts",
    "files": [
        "fonts/*",
        "lib/*",
        "index.d.ts",
        "*.md"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
