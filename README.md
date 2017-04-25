# npmtest-knockout

#### basic test coverage for  [knockout (v3.4.2)](http://knockoutjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-knockout.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-knockout) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-knockout.svg)](https://travis-ci.org/npmtest/node-npmtest-knockout)

#### Knockout makes it easier to create rich, responsive UIs with JavaScript

[![NPM](https://nodei.co/npm/knockout.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/knockout)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-knockout/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-knockout/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-knockout/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-knockout/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-knockout/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-knockout/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-knockout/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-knockout/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-knockout/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-knockout/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-knockout/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-knockout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-knockout/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-knockout/build/test-report.html](https://npmtest.github.io/node-npmtest-knockout/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-knockout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-knockout/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-knockout/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-knockout/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-knockout/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-knockout/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-knockout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-knockout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Knockout.js team"
    },
    "bugs": {
        "url": "https://github.com/knockout/knockout/issues"
    },
    "dependencies": {},
    "description": "Knockout makes it easier to create rich, responsive UIs with JavaScript",
    "devDependencies": {
        "closure-compiler": "~0.2.1",
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e87958de77ad1e936f7ce645bab8b5d7c456d937",
        "tarball": "https://registry.npmjs.org/knockout/-/knockout-3.4.2.tgz"
    },
    "gitHead": "4888305843439159bf100bd74e41768fd8650d1d",
    "homepage": "http://knockoutjs.com/",
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "main": "build/output/knockout-latest.debug.js",
    "maintainers": [
        {
            "name": "mtscout6"
        },
        {
            "name": "stevesanderson"
        },
        {
            "name": "mbest"
        }
    ],
    "name": "knockout",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/knockout/knockout.git"
    },
    "scripts": {
        "prepublish": "grunt",
        "test": "node spec/runner.node.js"
    },
    "testling": {
        "preprocess": "build/build.sh",
        "html": "spec/runner.html?src=build/output/knockout-latest.js&testling=true",
        "browsers": [
            "ie/6..latest",
            "chrome/20..latest",
            "firefox/3..latest",
            "safari/5.0.5..latest",
            "opera/11.0..latest",
            "iphone/6..latest",
            "ipad/6..latest"
        ]
    },
    "version": "3.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
