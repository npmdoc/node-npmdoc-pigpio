# npmdoc-pigpio

#### api documentation for  pigpio (v0.5.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-pigpio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pigpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pigpio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pigpio)

#### Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi

[![NPM](https://nodei.co/npm/pigpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pigpio)

- [https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pigpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pigpio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pigpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pigpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pigpio",
    "version": "0.5.1",
    "description": "Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi",
    "main": "pigpio.js",
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "test": "echo \"Tests can only be run manually from the command line.\" && exit 1",
        "install": "node-gyp rebuild"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/fivdi/pigpio.git"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "~2.6.2"
    },
    "keywords": [
        "gpio",
        "pwm",
        "servo",
        "interrupt",
        "raspberry",
        "pi"
    ],
    "author": "fivdi",
    "license": "MIT",
    "gypfile": true,
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
