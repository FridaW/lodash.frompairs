# lodash.frompairs
How to figure out the problem with the type error of "_.object is not a function"

lodash v4.0.0 removed _.object

Use _.fromPairs instead of _.object.

The lodash method _.fromPairs exported as a Node.js module.

You can figure this out by 

Installation

Using npm:

$ npm i -g npm
$ npm i --save lodash.frompairs

In Node.js:

var fromPairs = require('lodash.frompairs')


There are some details on this link:

https://www.npmjs.com/package/lodash.frompairs
