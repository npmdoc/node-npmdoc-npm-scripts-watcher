# npmdoc-npm-scripts-watcher

#### api documentation for  [npm-scripts-watcher (v1.0.2)](https://github.com/wehkamp/npm-scripts-watcher#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-scripts-watcher.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-scripts-watcher) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-scripts-watcher.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-scripts-watcher)

#### Globbing file watcher to automatically run npm scripts from package.json when files change, with pretty colors.

[![NPM](https://nodei.co/npm/npm-scripts-watcher.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-scripts-watcher)

- [https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-scripts-watcher/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-scripts-watcher",
    "description": "Globbing file watcher to automatically run npm scripts from package.json when files change, with pretty colors.",
    "version": "1.0.2",
    "bin": "lib/watcher.js",
    "main": "lib/watcher.js",
    "scripts": {
        "build": "babel -d lib src",
        "prepublish": "npm run build"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wehkamp/npm-scripts-watcher.git"
    },
    "keywords": [
        "npm",
        "scripts",
        "file",
        "watch",
        "watcher"
    ],
    "author": "Gert Hengeveld <info@ghengeveld.nl> (https://github.com/ghengeveld)",
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/wehkamp/npm-scripts-watcher/issues"
    },
    "homepage": "https://github.com/wehkamp/npm-scripts-watcher#readme",
    "dependencies": {
        "colors": "^1.1.2",
        "debounce": "^1.0.0",
        "glob": "^6.0.1",
        "node-watch": "^0.3.4",
        "shelljs": "^0.5.3"
    },
    "devDependencies": {
        "babel-cli": "^6.2.0",
        "babel-preset-es2015": "^6.1.18"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
