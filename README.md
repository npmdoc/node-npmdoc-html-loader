# api documentation for  [html-loader (v0.4.5)](https://github.com/webpack/html-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-html-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-html-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-html-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-html-loader)
#### html loader module for webpack

[![NPM](https://nodei.co/npm/html-loader.png?downloads=true)](https://www.npmjs.com/package/html-loader)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-loader/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-html-loader_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-html-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-html-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/html-loader/issues"
    },
    "dependencies": {
        "es6-templates": "^0.2.2",
        "fastparse": "^1.1.1",
        "html-minifier": "^3.0.1",
        "loader-utils": "^1.0.2",
        "object-assign": "^4.1.0"
    },
    "description": "html loader module for webpack",
    "devDependencies": {
        "beautify-lint": "^1.0.4",
        "codecov.io": "^0.1.6",
        "eslint": "^3.1.1",
        "istanbul": "^0.4.4",
        "js-beautify": "^1.6.3",
        "mocha": "^2.5.3",
        "should": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5fbcd87cd63a5c49a7fce2fe56f425e05729c68c",
        "tarball": "https://registry.npmjs.org/html-loader/-/html-loader-0.4.5.tgz"
    },
    "gitHead": "90c7b60d41a0af76019dbefa91d45dab90fbdd1e",
    "homepage": "https://github.com/webpack/html-loader#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "bebraw",
            "email": "bebraw@gmail.com"
        },
        {
            "name": "d3viant0ne",
            "email": "wiens.joshua@gmail.com"
        },
        {
            "name": "ericclemmons",
            "email": "eric@smarterspam.com"
        },
        {
            "name": "hemanth",
            "email": "hemanth.hm@gmail.com"
        },
        {
            "name": "jhnns",
            "email": "mail@johannesewald.de"
        },
        {
            "name": "peerigon",
            "email": "developers@peerigon.com"
        },
        {
            "name": "sokra",
            "email": "tobias.koppers@googlemail.com"
        },
        {
            "name": "thelarkinn",
            "email": "sean.larkin@cuw.edu"
        }
    ],
    "name": "html-loader",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpack/html-loader.git"
    },
    "scripts": {
        "beautify": "beautify-rewrite lib/**/*.js hot/**/*.js bin/**/*.js benchmark/*.js test/*.js",
        "beautify-lint": "beautify-lint lib/**/*.js hot/**/*.js bin/**/*.js benchmark/*.js test/*.js",
        "cover": "istanbul cover -x *.runtime.js node_modules/mocha/bin/_mocha",
        "lint": "eslint lib bin hot",
        "postcover": "npm run lint && npm run beautify-lint",
        "pretest": "npm run lint && npm run beautify-lint",
        "publish-patch": "npm run lint && npm run beautify-lint && mocha && npm version patch && git push && git push --tags && npm publish",
        "test": "mocha --harmony --full-trace --check-leaks",
        "travis": "npm run cover -- --report lcovonly"
    },
    "version": "0.4.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module html-loader](#apidoc.module.html-loader)



# <a name="apidoc.module.html-loader"></a>[module html-loader](#apidoc.module.html-loader)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
