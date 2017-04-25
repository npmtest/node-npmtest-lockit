# npmtest-lockit

#### basic test coverage for  lockit (v1.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-lockit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lockit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lockit.svg)](https://travis-ci.org/npmtest/node-npmtest-lockit)

#### Authentication solution for Express

[![NPM](https://nodei.co/npm/lockit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lockit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lockit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lockit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lockit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lockit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lockit/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-lockit/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-lockit/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lockit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lockit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lockit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lockit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lockit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lockit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lockit/build/test-report.html](https://npmtest.github.io/node-npmtest-lockit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lockit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lockit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lockit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lockit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lockit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lockit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lockit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lockit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lockit",
    "version": "1.3.1",
    "description": "Authentication solution for Express",
    "main": "index.js",
    "scripts": {
        "test": "make test"
    },
    "keywords": [
        "express",
        "middleware",
        "user",
        "registration",
        "signup",
        "authorization",
        "authentication"
    ],
    "author": {
        "name": "Mirco Zeiss",
        "twitter": "zemirco"
    },
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/zemirco/lockit"
    },
    "dependencies": {
        "chalk": "^1.1.0",
        "lockit-delete-account": "^1.0.5",
        "lockit-forgot-password": "^1.3.2",
        "lockit-login": "^1.1.5",
        "lockit-signup": "^1.2.2",
        "lockit-sql-adapter": "^0.5.3",
        "lockit-utils": "^0.5.3",
        "node.extend": "^1.1.2",
        "sqlite3": "^3.0.0"
    },
    "devDependencies": {
        "body-parser": "^1.13.2",
        "cookie-parser": "^1.3.3",
        "cookie-session": "^1.2.0",
        "errorhandler": "^1.4.1",
        "eslint": "^0.24.0",
        "express": "^4.13.1",
        "jade": "^1.7.0",
        "lockit-couchdb-adapter": "^0.5.1",
        "lockit-template-blank": "0.0.2",
        "mocha": "^2.2.5",
        "nodemailer-stub-transport": "^1.0.0",
        "should": "^7.0.1",
        "static-favicon": "^2.0.0-alpha",
        "supertest": "^1.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
