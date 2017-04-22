# npmdoc-node-core-audio

#### api documentation for  [node-core-audio (v0.5.1)](https://github.com/ZECTBynmo/node-core-audio)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-core-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-core-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-core-audio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-core-audio)

#### Core native node.js audio functionality, including sound card access and audio streaming

[![NPM](https://nodei.co/npm/node-core-audio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-core-audio)

- [https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Vegeto",
        "url": "http://mikevegeto.com/"
    },
    "bugs": {
        "url": "https://github.com/ZECTBynmo/node-core-audio/issues"
    },
    "contributors": [
        {
            "name": "Marc J. Schmidt",
            "url": "http://marcjschmidt.de/"
        },
        {
            "name": "Jeremiah Senkpiel",
            "url": "http://searchbeam.jit.su/"
        },
        {
            "name": "Daniel Church",
            "url": "https://github.com/anprogrammer/"
        }
    ],
    "dependencies": {
        "audio-streamer": ">= 0.1.0",
        "fft": "~0.2.1",
        "nan": "^2.1.0",
        "node-waveheader": "git://github.com/mrose17/node-waveheader.git",
        "portfinder": "0.2.1"
    },
    "description": "Core native node.js audio functionality, including sound card access and audio streaming",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "bd7d3edc26bfea8adb659235d54ddfcbc261ef42",
        "tarball": "https://registry.npmjs.org/node-core-audio/-/node-core-audio-0.5.1.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "fead49806f718771b78393421148ed355b246272",
    "gypfile": true,
    "homepage": "https://github.com/ZECTBynmo/node-core-audio",
    "keywords": [
        "audio",
        "dsp",
        "processing",
        "portaudio",
        "sound",
        "synth",
        "signal",
        "streaming",
        "buffer"
    ],
    "license": "MIT",
    "main": "./node-core-audio",
    "maintainers": [
        {
            "name": "mvegeto"
        }
    ],
    "name": "node-core-audio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ZECTBynmo/node-core-audio.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/test.js"
    },
    "version": "0.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
