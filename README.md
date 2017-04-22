# npmtest-office-ui-fabric-react

#### basic test coverage for  office-ui-fabric-react (v2.21.0)  [![npm package](https://img.shields.io/npm/v/npmtest-office-ui-fabric-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-office-ui-fabric-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-office-ui-fabric-react.svg)](https://travis-ci.org/npmtest/node-npmtest-office-ui-fabric-react)

#### Reusable React components for building experiences for Office 365.

[![NPM](https://nodei.co/npm/office-ui-fabric-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/office-ui-fabric-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-office-ui-fabric-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-office-ui-fabric-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/test-report.html](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-office-ui-fabric-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-office-ui-fabric-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-office-ui-fabric-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-office-ui-fabric-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-office-ui-fabric-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "office-ui-fabric-react",
    "version": "2.21.0",
    "description": "Reusable React components for building experiences for Office 365.",
    "main": "lib/index.js",
    "typings": "lib/index.d.ts",
    "repository": {
        "type": "git",
        "url": "https://github.com/OfficeDev/office-ui-fabric-react"
    },
    "license": "MIT",
    "scripts": {
        "build": "gulp",
        "clean": "gulp clean",
        "start": "node node_modules/webpack-dev-server/bin/webpack-dev-server.js --config webpack.serve.config.js --open",
        "test": "gulp"
    },
    "devDependencies": {
        "@microsoft/load-themed-styles": "^1.2.2",
        "@microsoft/web-library-build": ">=3.0.0-0 <4.0.0-0",
        "@types/chai": "^3.4.35",
        "@types/enzyme": "^2.7.5",
        "@types/es6-promise": "^0.0.32",
        "@types/mocha": "^2.2.39",
        "@types/react": "^15.0.16",
        "@types/react-addons-test-utils": "^0.14.17",
        "@types/react-dom": "^0.14.23",
        "@types/webpack-env": "^1.13.0",
        "@uifabric/example-app-base": "1.3.10",
        "autoprefixer": "^6.7.6",
        "chai": "^3.5.0",
        "css-loader": "^0.26.2",
        "enzyme": "^2.7.0",
        "es6-promise": "3.2.1",
        "git-rev": "0.2.1",
        "gulp": "~3.9.1",
        "gulp-prompt": "^0.2.0",
        "gulp-util": "3.0.7",
        "gutil": "1.6.4",
        "highlight.js": "^9.6.0",
        "load-themed-styles-loader": "^0.0.3",
        "mocha": "^3.2.0",
        "mocha-loader": "^1.1.1",
        "node-sass": "^4.5.0",
        "office-ui-fabric-core": ">=5.0.0 <6.0.0",
        "postcss-loader": "^1.3.3",
        "raw-loader": "^0.5.1",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-highlight": "0.8.0",
        "sass-loader": "^6.0.3",
        "source-map-loader": "0.1.5",
        "style-loader": "^0.13.2",
        "ts-loader": "^2.0.1",
        "typescript": "^2.2.2",
        "vinyl-ftp": "0.4.5",
        "webpack": "^2.2.1",
        "webpack-bundle-analyzer": "^2.2.1",
        "webpack-split-by-path": "0.0.10",
        "resemblejs": "~2.2.3",
        "@types/resemblejs": "~1.3.28",
        "gulp-phantomcss": "~0.3.0",
        "webpack-dev-server": "^2.4.1",
        "webpack-notifier": "^1.5.0"
    },
    "dependencies": {
        "@microsoft/load-themed-styles": "^1.2.2",
        "@uifabric/utilities": ">=1.8.3 <2.0.0"
    },
    "peerDependencies": {
        "react": "^0.14 || ^15.0.1-0 || ^16.0.0-0",
        "react-dom": "^0.14 || ^15.0.1-0 || ^16.0.0-0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
