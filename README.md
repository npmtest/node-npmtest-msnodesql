# npmtest-msnodesql

#### basic test coverage for  [msnodesql (v0.2.1)](https://github.com/WindowsAzure/node-sqlserver)  [![npm package](https://img.shields.io/npm/v/npmtest-msnodesql.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-msnodesql) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-msnodesql.svg)](https://travis-ci.org/npmtest/node-npmtest-msnodesql)

#### Microsoft Driver for Node.js for SQL Server

[![NPM](https://nodei.co/npm/msnodesql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/msnodesql)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-msnodesql/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-msnodesql/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-msnodesql/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-msnodesql/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-msnodesql/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-msnodesql/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-msnodesql/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-msnodesql/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-msnodesql/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-msnodesql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-msnodesql/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-msnodesql/build/test-report.html](https://npmtest.github.io/node-npmtest-msnodesql/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-msnodesql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-msnodesql/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-msnodesql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-msnodesql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-msnodesql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-msnodesql/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-msnodesql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-msnodesql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "msnodesql",
    "description": "Microsoft Driver for Node.js for SQL Server",
    "author": "Microsoft Corp.",
    "contributors": [
        "Jonathan Guerin <jguerin@microsoft.com>",
        "Jay Kint <jkint@microsoft.com>",
        "Warren Read <wread@microsoft.com>",
        "George Yan <georgeya@microsoft.com>",
        "Inga Verbitskaya <ingave@microsoft.com>"
    ],
    "version": "0.2.1",
    "keywords": [
        "sql",
        "database",
        "mssql",
        "azure",
        "sqlserver",
        "tds",
        "microsoft",
        "msnodesql",
        "node-sqlserver"
    ],
    "homepage": "https://github.com/WindowsAzure/node-sqlserver",
    "bugs": "https://github.com/WindowsAzure/node-sqlserver/issues",
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "https://raw.github.com/WindowsAzure/node-sqlserver/master/LICENSE"
        }
    ],
    "main": "./lib/sql.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/WindowsAzure/node-sqlserver.git"
    },
    "engines": {
        "node": ">=0.6"
    },
    "devDependencies": {
        "mocha": "0.14.x",
        "async": "0.1.x"
    },
    "os": [
        "win32"
    ],
    "scripts": {
        "install": "node scripts/install.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
