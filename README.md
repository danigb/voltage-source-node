# voltage-source-node [![npm](https://img.shields.io/npm/v/voltage-source-node.svg?style=flat-square)](https://www.npmjs.com/package/voltage-source-node)

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard) [![license](https://img.shields.io/npm/l/voltage-source-node.svg?style=flat-square)](https://www.npmjs.com/package/voltage-source-node)

A web audio voltage source node:

```js
var Voltage = require('voltage-source-node')
var ac = new AudioContext()
var voltage = Voltage(ac)
voltage.start()
```

Used to create control voltage (CV) signals. See [audio-contour](https://github.com/danigb/audio-contour) for an example.
