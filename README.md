# pixi-camera  [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]

## installation

```sh
npm install pixi-camera
```

## usage

```js
var PIXI = require('pixi.js');
var Camera = require('pixi-camera');

var world = new PIXI.Container();

var camera = new Camera(world);

var renderer = PIXI.AutoDetectRenderer();

renderer.render(camera);
```

[npm-url]: https://npmjs.org/package/pixi-camera
[npm-image]: http://img.shields.io/npm/v/pixi-camera.svg?style=flat

[travis-url]: http://travis-ci.org/beeglebug/pixi-camera
[travis-image]: http://img.shields.io/travis/beeglebug/pixi-camera/master.svg?style=flat
