# npmtest-diet

#### basic test coverage for  [diet (v0.15.0)](http://dietjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-diet.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-diet) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-diet.svg)](https://travis-ci.org/npmtest/node-npmtest-diet)

#### A tiny, fast and modular node.js web framework. Good for making fast & scalable apps and apis.

[![NPM](https://nodei.co/npm/diet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/diet)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-diet/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-diet/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-diet/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-diet/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-diet/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-diet/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-diet/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-diet/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-diet/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-diet/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-diet/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-diet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-diet/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-diet/build/test-report.html](https://npmtest.github.io/node-npmtest-diet/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-diet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-diet/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-diet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-diet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-diet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-diet/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-diet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-diet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Halász Ádám",
        "url": "http://adamhalasz.com/"
    },
    "bugs": {
        "url": "http://github.com/adamhalasz/diet/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "callsite": "^1.0.0",
        "clone": "^1.0.2",
        "colors": "^1.0.3",
        "es6-iterator": "^0.1.1",
        "etag": "^1.5.0",
        "eventemitter2": "^0.4.14",
        "ip": "^0.3.3",
        "merge": "^1.2.0",
        "mime": "^1.3.4",
        "nextjs": "0.0.3",
        "path-to-regexp": "^1.0.1",
        "querystrings": ">=0.3.0",
        "sugar": "^1.4.1"
    },
    "description": "A tiny, fast and modular node.js web framework. Good for making fast & scalable apps and apis.",
    "devDependencies": {
        "coveralls": ">=2.11.2",
        "istanbul": "~0.3.2",
        "mocha": "~1.21.4",
        "mocha-lcov-reporter": "0.0.1",
        "request": "^2.48.0",
        "should": "^8.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "05191cbb1a29a8344bc1cb5b8e0eaefbe371e825",
        "tarball": "https://registry.npmjs.org/diet/-/diet-0.15.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "16910b48a4b4bd0c010a71bf16e05ab85bf989a0",
    "homepage": "http://dietjs.com/",
    "keywords": [
        "diet",
        "web",
        "framework",
        "http",
        "https",
        "api",
        "routing",
        "router",
        "page routing",
        "url parse",
        "middleware",
        "connect",
        "plugins",
        "modules",
        "querystring",
        "rest",
        "restful",
        "web server",
        "domains",
        "subdomains",
        "vhost",
        "hosting",
        "virtual hosts",
        "request",
        "response",
        "dietjs",
        "diet.js"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "adamhalasz"
        }
    ],
    "name": "diet",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/adamhalasz/diet.git"
    },
    "scripts": {
        "coveralls": "jscoverage tests tests-cov",
        "test": "mocha tests"
    },
    "version": "0.15.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
