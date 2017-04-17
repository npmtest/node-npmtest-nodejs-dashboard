# test coverage for  [nodejs-dashboard (v0.4.1)](https://github.com/FormidableLabs/nodejs-dashboard#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nodejs-dashboard.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodejs-dashboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodejs-dashboard.svg)](https://travis-ci.org/npmtest/node-npmtest-nodejs-dashboard)
#### Telemetry dashboard for node.js apps from the terminal!

[![NPM](https://nodei.co/npm/nodejs-dashboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodejs-dashboard)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodejs-dashboard/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodejs-dashboard/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodejs-dashboard/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/test-report.html](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodejs-dashboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodejs-dashboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodejs-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodejs-dashboard/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodejs-dashboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Wilson"
    },
    "bin": {
        "nodejs-dashboard": "bin/nodejs-dashboard.js"
    },
    "bugs": {
        "url": "https://github.com/FormidableLabs/nodejs-dashboard/issues"
    },
    "dependencies": {
        "blessed": "^0.1.81",
        "blessed-contrib": "^3.5.5",
        "blocked": "^1.2.1",
        "commander": "^2.9.0",
        "cross-spawn": "^4.0.2",
        "jsonschema": "^1.1.1",
        "lodash": "^4.16.2",
        "pidusage": "^1.0.8",
        "pretty-bytes": "^3.0.1",
        "socket.io": "^1.4.8",
        "socket.io-client": "^1.4.8"
    },
    "description": "Telemetry dashboard for node.js apps from the terminal!",
    "devDependencies": {
        "babel-eslint": "^6.1.2",
        "chai": "^3.5.0",
        "eslint": "^2.10.2",
        "eslint-config-formidable": "^2.0.1",
        "eslint-plugin-filenames": "^1.1.0",
        "eslint-plugin-import": "^1.16.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.1",
        "mock-require": "^2.0.1",
        "object.assign": "^4.0.4",
        "sinon": "^1.17.6",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1ba880b72f8d9bcadde37253b95062c5ec549e57",
        "tarball": "https://registry.npmjs.org/nodejs-dashboard/-/nodejs-dashboard-0.4.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "fa0a42c9d31733c00832262a3bfee90a13a1e2d7",
    "homepage": "https://github.com/FormidableLabs/nodejs-dashboard#readme",
    "keywords": [
        "dashboard",
        "telemetry",
        "terminal",
        "realtime",
        "statistics"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jason.wilson"
        }
    ],
    "name": "nodejs-dashboard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/FormidableLabs/nodejs-dashboard.git"
    },
    "scripts": {
        "coverage": "istanbul cover --include-all-sources _mocha -- -c --recursive --require test/setup.js ./test",
        "lint": "eslint .",
        "test": "npm run lint && npm run test-only",
        "test-app": "./bin/nodejs-dashboard.js node test/app/index.js",
        "test-only": "mocha -c --require test/setup.js --recursive ./test"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
