# npmdoc-bower-requirejs

#### api documentation for  bower-requirejs (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-bower-requirejs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bower-requirejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bower-requirejs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bower-requirejs)

#### Automagically wire-up installed Bower components into your RequireJS config

[![NPM](https://nodei.co/npm/bower-requirejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-requirejs)

- [https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bower-requirejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bower-requirejs",
    "version": "1.2.0",
    "description": "Automagically wire-up installed Bower components into your RequireJS config",
    "keywords": [
        "bower",
        "requirejs",
        "rjs",
        "config",
        "wire",
        "inject",
        "install",
        "component",
        "package",
        "module"
    ],
    "license": "BSD-2-Clause",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "maintainers": [
        {
            "name": "Rob Dodson",
            "url": "robdodson.me"
        }
    ],
    "contributors": [
        {
            "name": "Merrick Christensen",
            "url": "merrickchristensen.com"
        }
    ],
    "main": "lib",
    "bin": "bin/bower-requirejs.js",
    "repository": "yeoman/bower-requirejs",
    "scripts": {
        "test": "grunt test"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "file-utils": "^0.2.1",
        "lodash": "^3.3.0",
        "nopt": "^3.0.0",
        "object-assign": "^2.0.0",
        "requirejs": "^2.1.5",
        "slash": "^1.0.0",
        "sudo-block": "^1.0.0",
        "update-notifier": "^0.3.0"
    },
    "devDependencies": {
        "bower": "^1.x",
        "durable-json-lint": "^0.0.1",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-copy": "^0.8.0",
        "grunt-contrib-jshint": "^0.11.0",
        "grunt-contrib-nodeunit": "^0.4.1",
        "grunt-simple-mocha": "^0.4.0",
        "load-grunt-tasks": "^3.1.0",
        "mocha": "*",
        "mockery": "^1.4.0",
        "should": "^5.0.1"
    },
    "peerDependencies": {
        "bower": "^1.x"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin",
        "lib",
        "templates"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
