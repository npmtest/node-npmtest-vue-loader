# test coverage for  [vue-loader (v11.3.4)](https://github.com/vuejs/vue-loader)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-loader)
#### Vue single-file component loader for Webpack

[![NPM](https://nodei.co/npm/vue-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue-loader/issues"
    },
    "dependencies": {
        "consolidate": "^0.14.0",
        "hash-sum": "^1.0.2",
        "js-beautify": "^1.6.3",
        "loader-utils": "^1.1.0",
        "lru-cache": "^4.0.1",
        "postcss": "^5.0.21",
        "postcss-load-config": "^1.1.0",
        "postcss-selector-parser": "^2.0.0",
        "source-map": "^0.5.6",
        "vue-hot-reload-api": "^2.0.11",
        "vue-style-loader": "^2.0.0",
        "vue-template-es2015-compiler": "^1.2.2"
    },
    "description": "Vue single-file component loader for Webpack",
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "chai": "^3.0.0",
        "coffee-loader": "^0.7.2",
        "coffee-script": "^1.10.0",
        "css-loader": "^0.26.0",
        "eslint": "^3.14.1",
        "eslint-config-vue": "^2.0.2",
        "eslint-plugin-vue": "^2.0.0",
        "expose-loader": "^0.7.1",
        "extract-text-webpack-plugin": "^2.0.0-rc.0",
        "file-loader": "^0.10.0",
        "inject-loader": "^2.0.0",
        "js-yaml": "^3.8.2",
        "jsdom": "^9.2.1",
        "marked": "^0.3.6",
        "memory-fs": "^0.4.1",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "node-libs-browser": "^2.0.0",
        "normalize-newline": "^3.0.0",
        "null-loader": "^0.1.1",
        "pug": "^2.0.0-beta6",
        "raw-loader": "^0.5.1",
        "skeleton-loader": "0.0.5",
        "stylus": "^0.54.5",
        "stylus-loader": "^2.0.0",
        "sugarss": "^0.2.0",
        "url-loader": "^0.5.7",
        "vue": "^2.1.0",
        "vue-server-renderer": "^2.1.10",
        "vue-template-compiler": "^2.1.0",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "65e10a44ce092d906e14bbc72981dec99eb090d2",
        "tarball": "https://registry.npmjs.org/vue-loader/-/vue-loader-11.3.4.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "5af00e58bb58329ac353c0e4048a62a33f8dac15",
    "homepage": "https://github.com/vuejs/vue-loader",
    "keywords": [
        "vue",
        "webpack",
        "loader"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "name": "vue-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "css-loader": "*",
        "vue-template-compiler": "^2.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue-loader.git"
    },
    "scripts": {
        "docs": "cd docs && gitbook serve",
        "docs:deploy": "bash ./docs/deploy.sh",
        "lint": "eslint lib",
        "test": "eslint lib && mocha --slow 5000 --timeout 10000"
    },
    "version": "11.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
