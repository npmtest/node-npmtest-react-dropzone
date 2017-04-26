# npmtest-react-dropzone

#### basic test coverage for  [react-dropzone (v3.13.0)](https://github.com/okonet/react-dropzone)  [![npm package](https://img.shields.io/npm/v/npmtest-react-dropzone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-dropzone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-dropzone.svg)](https://travis-ci.org/npmtest/node-npmtest-react-dropzone)

#### Simple HTML5 drag-drop zone with React.js

[![NPM](https://nodei.co/npm/react-dropzone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-dropzone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-dropzone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dropzone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-dropzone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-dropzone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-dropzone/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-dropzone/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-dropzone/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-dropzone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-dropzone/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-dropzone/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-dropzone/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dropzone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-dropzone/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-dropzone/build/test-report.html](https://npmtest.github.io/node-npmtest-react-dropzone/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-dropzone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-dropzone/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-dropzone/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-dropzone/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-dropzone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-dropzone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-dropzone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-dropzone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Param Aggarwal"
    },
    "bugs": {
        "url": "https://github.com/okonet/react-dropzone/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Andrey Okonetchnikov",
            "url": "http://okonet.ru"
        },
        {
            "name": "Mike Olson"
        },
        {
            "name": "Param Aggarwal"
        }
    ],
    "dependencies": {
        "attr-accept": "^1.0.3",
        "prop-types": "^15.5.7"
    },
    "description": "Simple HTML5 drag-drop zone with React.js",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.9.1",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^18.0.0",
        "babel-loader": "^6.2.2",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "babel-register": "^6.9.0",
        "css-loader": "^0.26.1",
        "cz-conventional-changelog": "^1.2.0",
        "enzyme": "^2.6.0",
        "eslint": "^3.11.0",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.7.1",
        "imagemin-cli": "^3.0.0",
        "imagemin-pngquant": "^5.0.0",
        "jest": "^18.0.0",
        "lint-staged": "^3.2.1",
        "markdownlint-cli": "^0.2.0",
        "npm-check": "^5.2.1",
        "pre-commit": "^1.1.3",
        "react": "^15.4.1",
        "react-addons-test-utils": "^15.4.1",
        "react-dom": "^15.4.1",
        "react-styleguidist": "^5.0.6",
        "rimraf": "^2.5.2",
        "semantic-release": "^6.3.2",
        "sinon": "^1.17.4",
        "style-loader": "^0.13.1",
        "webpack": "^1.13.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a6a438df289971f909d498583d67ab0c4f214b17",
        "tarball": "https://registry.npmjs.org/react-dropzone/-/react-dropzone-3.13.0.tgz"
    },
    "gitHead": "08be46c3d7ede275ae375738e8eb469e269347e5",
    "homepage": "https://github.com/okonet/react-dropzone",
    "jest": {
        "setupTestFrameworkScriptFile": "<rootDir>/testSetup.js"
    },
    "keywords": [
        "react-component",
        "react",
        "drag",
        "drop",
        "upload"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "eslint:fix",
            "git:add"
        ],
        "*.{svg,png}": [
            "imagemin",
            "git add"
        ]
    },
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "okonet"
        },
        {
            "name": "paramaggarwal"
        }
    ],
    "name": "react-dropzone",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0"
    },
    "pre-commit": [
        "lint-staged"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/okonet/react-dropzone.git"
    },
    "scripts": {
        "build": "npm run clean && webpack",
        "clean": "rimraf ./dist",
        "deps": "npm-check -s",
        "deps:update": "npm-check -u",
        "eslint:fix": "eslint --fix",
        "eslint:src": "eslint ./src ./*.js",
        "git:add": "git add",
        "imagemin": "imagemin --out-dir=logo --plugin=pngquant --plugin=svgo",
        "lint-staged": "lint-staged",
        "logo": "cd logo && sketchtool export artboards logo.sketch",
        "prepublish": "NODE_ENV=production npm run build && jest",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "start": "styleguidist server",
        "styleguide": "styleguidist build",
        "test": "npm run eslint:src && jest --coverage"
    },
    "version": "3.13.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
