# npmdoc-gulp-minify-css

#### api documentation for  gulp-minify-css (v1.2.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-minify-css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-minify-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-minify-css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-minify-css)

#### Minify css with clean-css.

[![NPM](https://nodei.co/npm/gulp-minify-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-minify-css)

- [https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-minify-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "dependencies": {
        "clean-css": "^3.3.3",
        "gulp-util": "^3.0.5",
        "object-assign": "^4.0.1",
        "readable-stream": "^2.0.0",
        "vinyl-bufferstream": "^1.0.1",
        "vinyl-sourcemaps-apply": "^0.2.0"
    },
    "deprecated": "Please use gulp-clean-css",
    "description": "Minify css with clean-css.",
    "devDependencies": {
        "@shinnn/eslint-config-node-legacy": "^1.0.0",
        "chai": "^3.0.0",
        "eslint": "^1.10.2",
        "from2-string": "^1.0.2",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-stylus": "^2.0.5",
        "istanbul": "^0.4.1",
        "istanbul-coveralls": "^1.0.3",
        "mocha": "^2.2.5",
        "stream-combiner2": "^1.1.1",
        "vinyl": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b6164957602ea27f9e5ad88227695dd205778c06",
        "tarball": "https://registry.npmjs.org/gulp-minify-css/-/gulp-minify-css-1.2.4.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "ae54239a273d6ae7bb0234fcde3545f5044aed72",
    "license": "MIT",
    "maintainers": [
        {
            "name": "murphydanger"
        },
        {
            "name": "shinnn"
        }
    ],
    "name": "gulp-minify-css",
    "optionalDependencies": {},
    "scripts": {
        "coverage": "node --harmony_destructuring node_modules/istanbul/lib/cli cover _mocha -- --full-trace",
        "coveralls": "${npm_package_scripts_coverage} && istanbul-coveralls",
        "pretest": "eslint --fix --config @shinnn/node-legacy --env mocha index.js test",
        "test": "node --harmony_destructuring node_modules/mocha/bin/_mocha --full-trace",
        "test-dot": "node --harmony_destructuring node_modules/mocha/bin/_mocha --reporter dot --full-trace"
    },
    "version": "1.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
