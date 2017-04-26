# npmtest-tether

#### basic test coverage for  [tether (v1.4.0)](https://github.com/HubSpot/tether#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-tether.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tether) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tether.svg)](https://travis-ci.org/npmtest/node-npmtest-tether)

#### A client-side library to make absolutely positioned elements attach to elements in the page efficiently.

[![NPM](https://nodei.co/npm/tether.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tether)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tether/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tether/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tether/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tether/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tether/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tether/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tether/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tether/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tether/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tether/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tether/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tether/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tether/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tether/build/test-report.html](https://npmtest.github.io/node-npmtest-tether/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tether/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tether/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tether/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tether/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tether/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tether/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tether/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tether/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Zack Bloom <zackbloom@gmail.com>",
        "Adam Schwartz <adam.flynn.schwartz@gmail.com>"
    ],
    "bugs": {
        "url": "https://github.com/HubSpot/tether/issues"
    },
    "dependencies": {},
    "description": "A client-side library to make absolutely positioned elements attach to elements in the page efficiently.",
    "devDependencies": {
        "del": "^2.0.2",
        "del-cli": "^0.2.0",
        "gulp": "^3.9.0",
        "gulp-autoprefixer": "^3.0.1",
        "gulp-babel": "^5.2.1",
        "gulp-bump": "^0.3.1",
        "gulp-concat": "^2.6.0",
        "gulp-header": "^1.7.1",
        "gulp-minify-css": "^1.2.1",
        "gulp-plumber": "^1.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-sass": "^2.0.4",
        "gulp-uglify": "^1.4.1",
        "gulp-wrap-umd": "^0.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0f9fa171f75bf58485d8149e94799d7ae74d1c1a",
        "tarball": "https://registry.npmjs.org/tether/-/tether-1.4.0.tgz"
    },
    "gitHead": "3d7119e590661f8c9e9e566c8a7640c189687215",
    "homepage": "https://github.com/HubSpot/tether#readme",
    "license": "MIT",
    "main": "dist/js/tether.js",
    "maintainers": [
        {
            "name": "hs"
        },
        {
            "name": "timmfin"
        },
        {
            "name": "zackbloom"
        }
    ],
    "name": "tether",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/HubSpot/tether.git"
    },
    "scripts": {
        "build": "gulp build",
        "reinstall": "del node_modules && npm install",
        "watch": "gulp watch"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
