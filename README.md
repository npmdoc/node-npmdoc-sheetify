# npmdoc-sheetify

#### basic api documentation for  [sheetify (v6.0.2)](https://github.com/stackcss/sheetify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sheetify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sheetify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sheetify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sheetify)

#### Modular CSS bundler

[![NPM](https://nodei.co/npm/sheetify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sheetify)

- [https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sheetify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sheetify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sheetify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sheetify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "index.js": "./browser.js"
    },
    "bugs": {
        "url": "https://github.com/stackcss/sheetify/issues"
    },
    "dependencies": {
        "falafel": "^1.2.0",
        "insert-css": "^2.0.0",
        "map-limit": "0.0.1",
        "postcss": "^5.0.10",
        "postcss-prefix": "^2.0.0",
        "resolve": "^1.1.7",
        "stack-trace": "0.0.9",
        "static-eval": "^1.1.0",
        "style-resolve": "^1.0.0",
        "through2": "^2.0.0",
        "xtend": "^4.0.1"
    },
    "description": "Modular CSS bundler",
    "devDependencies": {
        "browserify": "^13.0.0",
        "codecov.io": "^0.1.6",
        "concat-stream": "^1.5.1",
        "css-extract": "^1.1.2",
        "css-type-base": "^1.0.2",
        "css-wipe": "^4.2.2",
        "dependency-check": "^2.5.1",
        "domify": "^1.4.0",
        "from2-string": "^1.1.0",
        "istanbul": "^0.4.5",
        "jsdom": "^9.4.2",
        "npm-check-updates": "^2.2.0",
        "rimraf": "^2.5.1",
        "sheetify-cssnext": "^1.0.0",
        "standard": "^8.0.0",
        "tape": "^4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f494161e1cafc1bc02276e930e148acdd3344fd2",
        "tarball": "https://registry.npmjs.org/sheetify/-/sheetify-6.0.2.tgz"
    },
    "gitHead": "124473f04496aa7063338ef2dc14575fd187ee4d",
    "homepage": "https://github.com/stackcss/sheetify#readme",
    "keywords": [
        "modular",
        "css",
        "bundle",
        "browserify",
        "css-modules"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "ahdinosaur"
        },
        {
            "name": "hughsk"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "sheetify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stackcss/sheetify.git"
    },
    "scripts": {
        "deps": "dependency-check . --entry transform.js . && dependency-check . --entry transform.js --extra --no-dev -i insert-css",
        "format": "standard --format",
        "test": "standard && npm run deps && tape test/index.js",
        "test:cov": "standard && npm run deps && NODE_ENV=test istanbul cover test/index.js"
    },
    "version": "6.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
