# npmtest-cssnext

#### basic test coverage for  [cssnext (v1.8.4)](http://cssnext.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-cssnext.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cssnext) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cssnext.svg)](https://travis-ci.org/npmtest/node-npmtest-cssnext)

#### Use tomorrow's CSS syntax, today

[![NPM](https://nodei.co/npm/cssnext.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cssnext)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cssnext/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnext/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cssnext/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cssnext/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cssnext/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cssnext/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cssnext/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cssnext/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cssnext/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cssnext/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cssnext/build/test-report.html](https://npmtest.github.io/node-npmtest-cssnext/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cssnext/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cssnext/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cssnext/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssnext/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssnext/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cssnext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cssnext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxime Thirouin"
    },
    "bin": {
        "cssnext": "dist/bin.js"
    },
    "bugs": {
        "url": "https://github.com/cssnext/cssnext/issues"
    },
    "dependencies": {
        "autoprefixer-core": "^5.0.0",
        "caniuse-api": "^1.3.1",
        "chalk": "^1.0.0",
        "chokidar": "^1.0.0",
        "commander": "^2.3.0",
        "cssnano": "^2.6.1",
        "exit": "^0.1.2",
        "mkdirp": "^0.5.1",
        "pixrem": "^1.1.0",
        "pleeease-filters": "^1.0.0",
        "postcss": "^4.0.2",
        "postcss-calc": "^4.0.0",
        "postcss-color-function": "^1.1.0",
        "postcss-color-gray": "^2.0.0",
        "postcss-color-hex-alpha": "^1.1.0",
        "postcss-color-hwb": "^1.1.0",
        "postcss-color-rebeccapurple": "^1.1.0",
        "postcss-color-rgba-fallback": "^1.0.0",
        "postcss-custom-media": "^4.0.0",
        "postcss-custom-properties": "^4.0.0",
        "postcss-custom-selectors": "^2.3.0",
        "postcss-font-variant": "^1.0.0",
        "postcss-import": "^6.0.0",
        "postcss-media-minmax": "^1.1.0",
        "postcss-messages": "^0.2.2",
        "postcss-pseudo-class-any-link": "^0.2.1",
        "postcss-pseudoelements": "^2.1.1",
        "postcss-reporter": "^0.1.0",
        "postcss-selector-matches": "^1.2.1",
        "postcss-selector-not": "^1.0.1",
        "postcss-url": "^4.0.1",
        "read-file-stdin": "^0.2.0",
        "to-slug-case": "^0.1.2",
        "to-space-case": "^0.1.3",
        "write-file-stdout": "0.0.2"
    },
    "deprecated": "cssnext is now postcss-cssnext. cssnext is deprecated. See postcss-cssnext migration guide http://cssnext.io/postcss/",
    "description": "Use tomorrow's CSS syntax, today",
    "devDependencies": {
        "babel": "^5.4.7",
        "babel-core": "^5.4.7",
        "babel-eslint": "^3.1.17",
        "babel-loader": "^5.1.3",
        "babel-tape-runner": "^1.1.0",
        "classnames": "^2.1.1",
        "css-loader": "^0.13.1",
        "cssnext-loader": "^1.0.1",
        "cssrecipes-custom-media-queries": "^0.3.0",
        "cssrecipes-defaults": "^0.5.0",
        "cssrecipes-grid": "^0.4.0",
        "cssrecipes-utils": "^0.5.0",
        "cssrecipes-vertical-rhythm": "^0.6.0",
        "eslint": "^1.0.0",
        "eslint-loader": "^1.0.0",
        "eslint-plugin-react": "^3.0.0",
        "extract-text-webpack-plugin": "^0.8.0",
        "file-loader": "^0.8.3",
        "highlight.js": "^8.6.0",
        "isogram": "^0.5.0",
        "js-yaml": "^3.3.1",
        "json-loader": "^0.5.2",
        "markdown-it": "^4.2.1",
        "markdown-it-toc-and-anchor": "^1.0.1",
        "metalsmith": "^2.0.1",
        "metalsmith-collections": "^0.7.0",
        "metalsmith-filenames": "^1.0.0",
        "metalsmith-md": "^2.0.1",
        "metalsmith-react": "^1.1.0",
        "metalsmith-rename": "^1.0.0",
        "metalsmith-rss": "^1.0.0",
        "metalsmith-url": "^1.0.0",
        "metalsmith-watch": "^1.0.1",
        "microtime": "^1.2.0",
        "nano-logger": "^1.0.0",
        "node-libs-browser": "^0.5.0",
        "normalize.css": "^3.0.3",
        "object-assign": "^3.0.0",
        "opn": "^1.0.2",
        "react": "^0.13.3",
        "rimraf": "^2.3.4",
        "style-loader": "^0.12.2",
        "tape": "^4.0.0",
        "webpack": "^1.9.7",
        "webpack-dev-server": "^1.8.2",
        "webpack-nano-logs": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c1ec22a95c20ea0b7441f3af2f664adc6721e181",
        "tarball": "https://registry.npmjs.org/cssnext/-/cssnext-1.8.4.tgz"
    },
    "gitHead": "b5ece99c1e1b5e4cdfd6c25f856946bbcbc2247c",
    "homepage": "http://cssnext.io/",
    "keywords": [
        "css",
        "w3c",
        "cssnext",
        "preprocessor",
        "postprocessor",
        "rework",
        "postcss",
        "postcss-plugin",
        "autoprefixer",
        "babel",
        "transpiler"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "moox"
        },
        {
            "name": "bloodyowl"
        }
    ],
    "name": "cssnext",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cssnext/cssnext.git"
    },
    "scripts": {
        "#lint": "even if there is a .eslintignore symlink, we use an explicit command because windows don't like unix symlink",
        "#tape": "to avoid really slow tests, we run babel once & run tests on the result",
        "_docs-deploy": "GIT_DEPLOY_DIR=docs/dist ./docs/scripts/deploy-to-gh-pages.sh -v",
        "babelify": "babel src --out-dir dist",
        "docs-build": "babel-node docs/scripts/build",
        "docs-deploy": "npm run docs-test && npm run _docs-deploy",
        "docs-start": "npm run docs-build -- --dev --dev-server --open",
        "docs-test": "npm run docs-build -- --production",
        "lint": "eslint --ignore-path .gitignore .",
        "prebabelify": "rimraf dist",
        "prepublish": "npm run babelify",
        "standalone": "webpack --output-library-target umd --output-library cssnext dist/index.js dist/cssnext.js",
        "tape": "tape 'dist/__tests__/*.js'",
        "test": "npm run lint && npm run babelify && npm run standalone && npm run tape"
    },
    "version": "1.8.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
