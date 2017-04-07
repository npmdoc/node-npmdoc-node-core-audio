# api documentation for  [node-core-audio (v0.5.1)](https://github.com/ZECTBynmo/node-core-audio)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-core-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-core-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-core-audio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-core-audio)
#### Core native node.js audio functionality, including sound card access and audio streaming

[![NPM](https://nodei.co/npm/node-core-audio.png?downloads=true)](https://www.npmjs.com/package/node-core-audio)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-core-audio_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-core-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Vegeto",
        "email": "michael.vegeto@gmail.com",
        "url": "http://mikevegeto.com/"
    },
    "bugs": {
        "url": "https://github.com/ZECTBynmo/node-core-audio/issues"
    },
    "contributors": [
        {
            "name": "Marc J. Schmidt",
            "email": "marc@kryn.org",
            "url": "http://marcjschmidt.de/"
        },
        {
            "name": "Jeremiah Senkpiel",
            "email": "fishrock123@rocketmail.com",
            "url": "http://searchbeam.jit.su/"
        },
        {
            "name": "Daniel Church",
            "email": "CrazyNorman@gmail.com",
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
            "name": "mvegeto",
            "email": "michael.vegeto@gmail.com"
        }
    ],
    "name": "node-core-audio",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ZECTBynmo/node-core-audio.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/test.js"
    },
    "version": "0.5.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-core-audio](#apidoc.module.node-core-audio)
1.  [function <span class="apidocSignatureSpan">node-core-audio.</span>createNewAudioEngine ( options )](#apidoc.element.node-core-audio.createNewAudioEngine)



# <a name="apidoc.module.node-core-audio"></a>[module node-core-audio](#apidoc.module.node-core-audio)

#### <a name="apidoc.element.node-core-audio.createNewAudioEngine"></a>[function <span class="apidocSignatureSpan">node-core-audio.</span>createNewAudioEngine ( options )](#apidoc.element.node-core-audio.createNewAudioEngine)
- description and source-code
```javascript
createNewAudioEngine = function ( options ) {
		newAudioEngine= new AudioEngine( options );
		return newAudioEngine;
	}
```
- example usage
```shell
...
the sound card.

'''javascript
// Create a new instance of node-core-audio
var coreAudio = require("node-core-audio");

// Create a new audio engine
var engine = coreAudio.createNewAudioEngine();

// Add an audio processing callback
// This function accepts an input buffer coming from the sound card,
// and returns an ourput buffer to be sent to your speakers.
//
// Note: This function must return an output buffer
function processAudio( inputBuffer ) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
