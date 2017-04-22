# npmdoc-connect-redis

#### api documentation for  [connect-redis (v3.2.0)](https://github.com/visionmedia/connect-redis#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-connect-redis.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-connect-redis) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-connect-redis.svg)](https://travis-ci.org/npmdoc/node-npmdoc-connect-redis)

#### Redis session store for Connect

[![NPM](https://nodei.co/npm/connect-redis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-redis)

- [https://npmdoc.github.io/node-npmdoc-connect-redis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-redis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-redis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-redis/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-connect-redis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-connect-redis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/visionmedia/connect-redis/issues"
    },
    "contributors": [
        {
            "name": "Marc Harter"
        }
    ],
    "dependencies": {
        "debug": "^2.2.0",
        "redis": "^2.1.0"
    },
    "description": "Redis session store for Connect",
    "devDependencies": {
        "blue-tape": "^0.1.8",
        "bluebird": "^2.3.2",
        "eslint": "^1.6.0",
        "express-session": "^1.9.1",
        "ioredis": "^1.7.5",
        "istanbul": "^0.3.2",
        "tape": "^4.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "2d29ea60c8ae8c2c818a710247fdfed158f43388",
        "tarball": "https://registry.npmjs.org/connect-redis/-/connect-redis-3.2.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "da6cf26f22d3af54c2be1f590fa125bd712c6ae3",
    "homepage": "https://github.com/visionmedia/connect-redis#readme",
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "chirag04"
        },
        {
            "name": "wavded"
        }
    ],
    "name": "connect-redis",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/visionmedia/connect-redis.git"
    },
    "scripts": {
        "bench": "node bench/redisbench.js",
        "lint": "eslint index.js test lib bench",
        "test": "DEBUG=* istanbul cover tape \"test/*-test.js\""
    },
    "version": "3.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
