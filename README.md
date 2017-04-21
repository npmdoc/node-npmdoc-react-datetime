# npmdoc-react-datetime

#### api documentation for  [react-datetime (v2.8.9)](https://github.com/YouCanBookMe/react-datetime)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-datetime.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-datetime) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-datetime.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-datetime)

#### A lightweight but complete datetime picker React.js component.

[![NPM](https://nodei.co/npm/react-datetime.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-datetime)

- [https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-datetime/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-datetime/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-datetime",
    "version": "2.8.9",
    "description": "A lightweight but complete datetime picker React.js component.",
    "homepage": "https://github.com/YouCanBookMe/react-datetime",
    "repository": {
        "type": "git",
        "url": "https://github.com/YouCanBookMe/react-datetime"
    },
    "main": "./DateTime.js",
    "files": [
        "DateTime.js",
        "react-datetime.d.ts",
        "typings/index.d.ts",
        "src",
        "css",
        "dist"
    ],
    "types": "./typings/index.d.ts",
    "scripts": {
        "build:mac": "./node_modules/.bin/gulp",
        "build:win": "./node_modules/.bin/gulp.cmd",
        "dev": "./node_modules/.bin/webpack-dev-server --config example/webpack.config.js --devtool eval --progress --colors --hot --content-base example",
        "lint": "./node_modules/.bin/eslint src/ DateTime.js tests/",
        "test": "./node_modules/.bin/jest",
        "test:all": "npm run test:typings && npm run test",
        "test:typings": "./node_modules/.bin/tsc -p ./typings",
        "test:watch": "./node_modules/.bin/jest --watch"
    },
    "keywords": [
        "react",
        "react-component",
        "datepicker",
        "timepicker",
        "datetimepicker",
        "datetime"
    ],
    "author": "Javier Marquez",
    "license": "MIT",
    "peerDependencies": {
        "moment": ">=2.16.0",
        "react": ">=0.13",
        "react-dom": ">=0.13"
    },
    "devDependencies": {
        "@types/react": "^0.14.49",
        "babel-core": "^6.22.1",
        "babel-jest": "^18.0.0",
        "babel-loader": "^6.2.1",
        "babel-plugin-transform-remove-strict-mode": "0.0.2",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.22.0",
        "enzyme": "^2.7.1",
        "eslint": "^3.1.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1",
        "gulp-insert": "^0.4.0",
        "gulp-plumber": "^1.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^2.4.0",
        "gulp-uglify": "^1.2.0",
        "jest": "^18.1.0",
        "jest-cli": "^18.1.0",
        "jsdom": "^7.0.2",
        "mocha": "^3.2.0",
        "moment": ">=2.16.0",
        "pre-commit": "^1.1.3",
        "react": ">=0.13",
        "react-addons-test-utils": ">=0.13",
        "react-dom": ">=0.13",
        "react-test-renderer": "^15.4.2",
        "through2": "^2.0.3",
        "typescript": "^2.0.10",
        "webpack": "^2.2.1",
        "webpack-dev-server": "^1.7.0",
        "webpack-stream": "^3.2.0"
    },
    "dependencies": {
        "object-assign": "^3.0.0",
        "react-onclickoutside": "^5.9.0"
    },
    "pre-commit": [
        "lint",
        "test:all"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
