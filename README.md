floatify . Common helper to floatify strings
===
[![Build Status](https://travis-ci.org/pocketrocket/floatify.svg?branch=master)](https://travis-ci.org/pocketrocket/floatify)

## Usage
### Example

```js
var floatify = require("floatify")
floatify.floatify("123123.245346556")
>> 123123.245346556
floatify.floatify("123.242,5346556")
>> 123242.5346556
floatify.floatify("123,242.5346556")
>> 123242.5346556
```

Run Example @runkit:
https://runkit.com/embed/j8f4v433l1wh

for more detailed examples see Mocha Testcases in `test/floatify.js`

## Installation with npm
### with npm
`npm i floatify`
### with yarn
`yarn add floatify`

## Clone repo
### via ssh
`git clone git@github.com:pocketrocket/floatify`
### via https
`git clone https://github.com/pocketrocket/floatify.git`

## Testing
Basic testing done, use `npm run test` or `yarn run test`