# npmtest-stylelint-scss

#### test coverage for  [stylelint-scss (v1.4.4)](https://github.com/kristerkari/stylelint-scss#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-stylelint-scss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stylelint-scss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stylelint-scss.svg)](https://travis-ci.org/npmtest/node-npmtest-stylelint-scss)

#### A collection of SCSS specific rules for stylelint

[![NPM](https://nodei.co/npm/stylelint-scss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stylelint-scss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stylelint-scss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylelint-scss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stylelint-scss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stylelint-scss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stylelint-scss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stylelint-scss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stylelint-scss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stylelint-scss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stylelint-scss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylelint-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stylelint-scss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stylelint-scss/build/test-report.html](https://npmtest.github.io/node-npmtest-stylelint-scss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stylelint-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stylelint-scss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stylelint-scss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stylelint-scss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylelint-scss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylelint-scss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stylelint-scss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stylelint-scss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Krister Kari"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "bugs": {
        "url": "https://github.com/kristerkari/stylelint-scss/issues"
    },
    "dependencies": {
        "lodash": "^4.11.1",
        "postcss-media-query-parser": "^0.2.3",
        "postcss-resolve-nested-selector": "^0.1.1",
        "postcss-selector-parser": "^2.0.0",
        "postcss-value-parser": "^3.3.0",
        "stylelint": "^7.0.3"
    },
    "description": "A collection of SCSS specific rules for stylelint",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-register": "^6.14.0",
        "coveralls": "^2.11.14",
        "eslint": "^2.3.0",
        "eslint-config-stylelint": "^1.0.0",
        "npmpub": "^3.0.3",
        "nyc": "^8.3.1",
        "postcss": "^5.0.21",
        "postcss-scss": "^0.1.7",
        "replace": "^0.3.0",
        "request": "^2.72.0",
        "rimraf": "^2.5.2",
        "semver": "^5.1.0",
        "stylelint-test-rule-tape": "^0.2.0",
        "table": "3.7.9",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "091fcbd8b648c78ec3899853e54b975e0256cd4a",
        "tarball": "https://registry.npmjs.org/stylelint-scss/-/stylelint-scss-1.4.4.tgz"
    },
    "engines": {
        "node": ">=4.2.1"
    },
    "eslintConfig": {
        "extends": "stylelint",
        "rules": {
            "arrow-spacing": 2,
            "no-var": 2,
            "object-shorthand": 2,
            "prefer-const": 2,
            "template-curly-spacing": 2
        }
    },
    "files": [
        "dist",
        "docs",
        "src/**/README.md",
        "!**/__tests__"
    ],
    "gitHead": "4eac7b3a4cfbb78abd3af97378218102adb13dc9",
    "homepage": "https://github.com/kristerkari/stylelint-scss#readme",
    "keywords": [
        "css",
        "csslint",
        "lint",
        "linter",
        "stylelint",
        "stylelint-plugin"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "dryoma"
        },
        {
            "name": "kristerkari"
        }
    ],
    "name": "stylelint-scss",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kristerkari/stylelint-scss.git"
    },
    "scripts": {
        "build": "babel src --out-dir dist",
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "lint": "eslint . --ignore-path .gitignore",
        "milestone": "node scripts/update-milestone.js",
        "prebuild": "rimraf dist",
        "prepublish": "npm run build",
        "pretest": "npm run lint",
        "release": "npmpub",
        "test": "nyc tape -r babel-register \"src/**/__tests__/*.js\" | tap-spec",
        "test-rule": "node ./scripts/test-rule.js",
        "test-util": "node ./scripts/test-util.js"
    },
    "version": "1.4.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
