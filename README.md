# npmtest-grunt-mocha

#### basic test coverage for  [grunt-mocha (v1.0.4)](https://github.com/disqus/grunt-mocha)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-mocha.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-mocha)

#### Grunt task for running client-side Mocha specs in PhantomJS

[![NPM](https://nodei.co/npm/grunt-mocha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-mocha)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-mocha/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mocha/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mocha/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-mocha/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mocha/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-mocha/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-mocha/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-mocha/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-mocha/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-mocha/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-mocha/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-mocha/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-mocha/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-mocha/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-mocha/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-mocha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-mocha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-mocha/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kelly Miyashiro"
    },
    "bugs": {
        "url": "https://github.com/disqus/grunt-mocha/issues"
    },
    "contributors": [
        {
            "name": "Kelly Miyashiro"
        },
        {
            "name": "Tony Narlock"
        }
    ],
    "dependencies": {
        "grunt-lib-phantomjs": "^1.0.2",
        "lodash": "^3.9.0",
        "mocha": ">=2.5.3"
    },
    "description": "Grunt task for running client-side Mocha specs in PhantomJS",
    "devDependencies": {
        "chai": "^3.4.1",
        "grunt": "~0.4",
        "grunt-contrib-connect": "~0.2",
        "grunt-contrib-jshint": "~0.3",
        "mocha": ">=2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ee261dc66a03002e0caa42cb7fd41d16b2956abd",
        "tarball": "https://registry.npmjs.org/grunt-mocha/-/grunt-mocha-1.0.4.tgz"
    },
    "engines": {
        "node": "*"
    },
    "files": [
        "growl",
        "phantomjs",
        "support",
        "tasks"
    ],
    "gitHead": "d551a6a2a04fca72bdf057d9831b91b4c6770290",
    "homepage": "https://github.com/disqus/grunt-mocha",
    "keywords": [
        "gruntplugin",
        "mocha",
        "test",
        "phantomjs"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/disqus/grunt-mocha/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "byk"
        },
        {
            "name": "disqus"
        },
        {
            "name": "kmiyashiro"
        }
    ],
    "name": "grunt-mocha",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/disqus/grunt-mocha.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
