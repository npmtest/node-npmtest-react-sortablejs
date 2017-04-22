# npmtest-react-sortablejs

#### basic test coverage for  [react-sortablejs (v1.3.3)](https://github.com/cheton/react-sortable)  [![npm package](https://img.shields.io/npm/v/npmtest-react-sortablejs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-sortablejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-sortablejs.svg)](https://travis-ci.org/npmtest/node-npmtest-react-sortablejs)

#### A React component built on top of Sortable (https://github.com/RubaXa/Sortable).

[![NPM](https://nodei.co/npm/react-sortablejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-sortablejs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-sortablejs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-sortablejs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-sortablejs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-sortablejs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-sortablejs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-sortablejs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-sortablejs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-sortablejs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-sortablejs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-sortablejs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-sortablejs/build/test-report.html](https://npmtest.github.io/node-npmtest-react-sortablejs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-sortablejs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-sortablejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-sortablejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-sortablejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-sortablejs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-sortablejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-sortablejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cheton Wu"
    },
    "bugs": {
        "url": "https://github.com/cheton/react-sortable/issues"
    },
    "dependencies": {
        "prop-types": "^15.5.8"
    },
    "description": "A React component built on top of Sortable (https://github.com/RubaXa/Sortable).",
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-eslint": "^7.2.2",
        "babel-loader": "^6.4.1",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "babel-preset-stage-0": "^6.24.1",
        "coveralls": "^2.13.0",
        "eslint": "~3.19.0",
        "eslint-config-trendmicro": "~0.5.1",
        "eslint-loader": "~1.7.1",
        "eslint-plugin-import": "~2.2.0",
        "eslint-plugin-jsx-a11y": "~2.2.3",
        "eslint-plugin-react": "~6.10.3",
        "lodash": "^4.17.4",
        "nib": "^1.1.2",
        "react": "^15.5.4",
        "react-dom": "^15.5.4",
        "sortablejs": "^1.5.1",
        "stylus": "^0.54.5",
        "stylus-loader": "^3.0.1",
        "tap": "^10.3.2",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2",
        "which": "~1.2.14"
    },
    "directories": {},
    "dist": {
        "shasum": "2a786bf91bc87713402bf5cb48a7d29f7ecaac9d",
        "tarball": "https://registry.npmjs.org/react-sortablejs/-/react-sortablejs-1.3.3.tgz"
    },
    "gitHead": "0b11931ad0e9c2696f5e5d1edfb03039756ac5a1",
    "homepage": "https://github.com/cheton/react-sortable",
    "keywords": [
        "react",
        "react-component",
        "sortable",
        "reorder",
        "drag",
        "mixin"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "cheton"
        }
    ],
    "name": "react-sortablejs",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0",
        "sortablejs": "^1.5.1"
    },
    "pre-commit": [
        "precommit-check"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cheton/react-sortable.git"
    },
    "scripts": {
        "build": "babel --out-dir ./lib ./src",
        "build-examples": "cd examples; webpack",
        "coveralls": "./babel-tap --coverage --coverage-report=text-lcov test/*.js | node_modules/.bin/coveralls",
        "dev": "cd examples; webpack-dev-server --hot --inline --host 0.0.0.0 --port 8000 --content-base ../docs",
        "dist": "webpack; BUILD_ENV=dist webpack",
        "lint": "eslint ./src",
        "lint:fix": "eslint --fix ./src",
        "precommit-check": "npm run lint",
        "prepublish": "npm run lint && npm test && npm run build && npm run dist && npm run build-examples && npm run release",
        "release": "mkdir -p releases; cp -f dist/react-sortable.js releases/react-sortable-${npm_package_version}.js; cp -f dist/react-sortable.min.js releases/react-sortable-${npm_package_version}.min.js",
        "test": "./babel-tap --coverage test/*.js"
    },
    "version": "1.3.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
