# npmdoc-draft-js-export-html

#### api documentation for  [draft-js-export-html (v0.5.2)](https://github.com/sstur/draft-js-export-html#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-draft-js-export-html.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-draft-js-export-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-draft-js-export-html.svg)](https://travis-ci.org/npmdoc/node-npmdoc-draft-js-export-html)

#### DraftJS: Export ContentState to HTML

[![NPM](https://nodei.co/npm/draft-js-export-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/draft-js-export-html)

- [https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-draft-js-export-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "draft-js-export-html",
    "version": "0.5.2",
    "description": "DraftJS: Export ContentState to HTML",
    "main": "lib/main.js",
    "typings": "typings/intex.d.ts",
    "scripts": {
        "build": "babel src --ignore \"_*\" --out-dir lib",
        "lint": "eslint --max-warnings 0 .",
        "typecheck": "flow",
        "prepublish": "npm run build",
        "test": "npm run lint && npm run typecheck && npm run test-src",
        "test-src": "mocha \"src/**/__tests__/*.js\"",
        "watch": "npm run build -- --watch"
    },
    "dependencies": {
        "draft-js-utils": "^0.1.5"
    },
    "peerDependencies": {
        "draft-js": ">=0.7.0",
        "immutable": "3.x.x"
    },
    "devDependencies": {
        "@types/draft-js": "^0.7.33",
        "babel-cli": "^6.10.1",
        "babel-core": "^6.9.1",
        "babel-eslint": "^7.0.0",
        "babel-plugin-transform-class-properties": "^6.9.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "eslint": "^3.7.1",
        "eslint-plugin-babel": "^3.2.0",
        "eslint-plugin-flow-vars": "^0.5.0",
        "eslint-plugin-react": "^6.3.0",
        "expect": "^1.20.1",
        "flow-bin": "^0.32.0",
        "mocha": "^3.1.0",
        "react": "^15.1.0",
        "react-dom": "^15.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/sstur/draft-js-export-html.git"
    },
    "keywords": [
        "draft-js",
        "export-html"
    ],
    "author": "sstur@me.com",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/sstur/draft-js-export-html/issues"
    },
    "homepage": "https://github.com/sstur/draft-js-export-html#readme",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
