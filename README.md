# test coverage for  [contentful (v4.1.2)](https://www.contentful.com/developers/documentation/content-delivery-api/)  [![npm package](https://img.shields.io/npm/v/npmtest-contentful.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-contentful) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-contentful.svg)](https://travis-ci.org/npmtest/node-npmtest-contentful)
#### Client for Contentful's Content Delivery API

[![NPM](https://nodei.co/npm/contentful.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/contentful)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-contentful/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-contentful/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-contentful/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-contentful/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-contentful/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-contentful/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-contentful/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-contentful/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-contentful/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-contentful/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-contentful/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-contentful/build/test-report.html](https://npmtest.github.io/node-npmtest-contentful/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-contentful/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-contentful/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-contentful/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-contentful/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-contentful/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-contentful/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-contentful/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-contentful/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Contentful"
    },
    "browser": "./dist/contentful.js",
    "bugs": {
        "url": "https://github.com/contentful/contentful.js/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "axios": "~0.15.3",
        "contentful-sdk-core": "^3.8.0",
        "es6-promise": "^4.0.5",
        "json-stringify-safe": "^5.0.1",
        "lodash": "^4.17.4"
    },
    "description": "Client for Contentful's Content Delivery API",
    "devDependencies": {
        "babel-cli": "^6.7.5",
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-rewire": "^1.0.0",
        "babel-plugin-transform-object-assign": "^6.22.0",
        "babel-plugin-transform-runtime": "^6.7.5",
        "babel-preset-env": "^1.1.8",
        "babel-preset-es2015": "^6.6.0",
        "babel-register": "^6.7.2",
        "babel-template": "^6.22.0",
        "babel-types": "^6.22.0",
        "blue-tape": "^1.0.0",
        "contentful-sdk-jsdoc": "^1.2.2",
        "coveralls": "^2.11.9",
        "cz-conventional-changelog": "^1.1.6",
        "esdoc": "^0.5.2",
        "eslint": "^3.16.0",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.2",
        "eslint-plugin-standard": "^2.0.1",
        "husky": "^0.13.1",
        "in-publish": "^2.0.0",
        "istanbul": "^1.0.0-alpha.2",
        "jsdoc": "^3.4.0",
        "json": "^9.0.3",
        "karma": "^1.4.1",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-chrome-launcher": "^2.0.0",
        "karma-sauce-launcher": "^1.1.0",
        "karma-tap": "^3.1.1",
        "karma-webpack": "^2.0.2",
        "lodash-webpack-plugin": "^0.11.2",
        "mkdirp": "^0.5.1",
        "require-all": "^2.2.0",
        "rimraf": "^2.6.0",
        "semantic-release": "^6.3.2",
        "sinon": "^2.0.0-pre",
        "trevor": "^2.2.0",
        "webpack": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5a02e02b694fce860de657122e7c49b96046eca5",
        "tarball": "https://registry.npmjs.org/contentful/-/contentful-4.1.2.tgz"
    },
    "engines": {
        "node": ">=4.7.2"
    },
    "files": [
        "version.js",
        "index.d.ts",
        "dist",
        "tonic-example.js"
    ],
    "gitHead": "8ff6a006d1fe0d3ce20054af66e574d96043474e",
    "homepage": "https://www.contentful.com/developers/documentation/content-delivery-api/",
    "license": "MIT",
    "main": "./dist/contentful.node.js",
    "maintainers": [
        {
            "name": "cf-admin"
        },
        {
            "name": "contentful-ecosystem"
        },
        {
            "name": "farruco.sanjurjo"
        },
        {
            "name": "hungryblank"
        },
        {
            "name": "kgarbaya"
        }
    ],
    "name": "contentful",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/contentful/contentful.js.git"
    },
    "scripts": {
        "browser-coverage": "npm run test:cover && opener coverage/lcov-report/index.html",
        "build": "npm run clean && npm run build:ci",
        "build:ci": "npm run vendor:version && npm run build:standalone",
        "build:standalone": "BABEL_ENV=webpack webpack && BABEL_ENV=webpack NODE_ENV=production webpack -p",
        "build:standalone:log": "BABEL_ENV=webpack npm run build && BABEL_ENV=webpack NODE_ENV=production webpack -p --json --profile > webpack-build-log.json",
        "clean": "rimraf dist && rimraf coverage",
        "devdep:build": "pushd ../contentful-sdk-core && npm run build && popd",
        "devdep:clean": "pushd ../contentful-sdk-core && npm run clean && popd",
        "devdep:install": "npm run devdep:build && rm -rf node_modules/contentful-sdk-core && npm install ../contentful-sdk-core && npm run devdep:clean",
        "devdep:uninstall": "npm run devdep:clean && rimraf node_modules/contentful-sdk-core",
        "docs:build": "esdoc -c esdoc.json",
        "docs:dev": "npm run build && npm run docs:build",
        "docs:publish": "npm run docs:build && ./node_modules/contentful-sdk-jsdoc/bin/publish-docs.sh contentful.js contentful",
        "docs:watch": "watchy -w lib npm run docs:dev",
        "lint": "eslint lib test",
        "postpublish": "npm run docs:publish && npm run clean",
        "precommit": "npm run lint",
        "prepublish": "in-publish && npm run build:ci || not-in-publish",
        "prepush": "npm run test:only",
        "pretest": "npm run lint",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "npm run test:cover && npm run test:integration && npm run test:browser-local",
        "test:browser-local": "BABEL_ENV=test karma start karma.conf.local.js",
        "test:browser-remote": "BABEL_ENV=test karma start karma.conf.saucelabs.js",
        "test:ci": "npm run build && ./node_modules/contentful-sdk-core/bin/test-ci.sh",
        "test:cover": "BABEL_ENV=test babel-node ./node_modules/istanbul/lib/cli.js cover test/runner",
        "test:debug": "BABEL_ENV=test babel-node debug ./test/runner",
        "test:integration": "BABEL_ENV=test babel-node ./test/integration/tests.js",
        "test:integration-debug": "BABEL_ENV=test babel-node debug ./test/integration/tests.js",
        "test:only": "BABEL_ENV=test babel-node ./test/runner",
        "test:simulate-ci": "trevor",
        "vendor:version": "echo \"module.exports = ''cat package.json|json version''\" > version.js"
    },
    "tonicExampleFilename": "tonic-example.js",
    "types": "./index.d.ts",
    "version": "4.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
