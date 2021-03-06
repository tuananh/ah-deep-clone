# ah-deep-clone [![build status](https://secure.travis-ci.org/thlorenz/ah-deep-clone.png)](http://travis-ci.org/thlorenz/ah-deep-clone)

Creates a deep clone of a [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) of collected async hooks activities.

```js
const deepClone = require('ah-deep-clone')
const copy = deepClone(activities)
```

## Installation

    npm install ah-deep-clone

## API

### `deepClone`

Clones the activities passed to it.

Any modifications applied to the original won't be visible in the copy.
This includes additions/removals to the original Map
 
#### arguments

- `@param {Map.<Number, Object>}` activities to be cloned
- `@return {Map.<Number, Object>}` cloned activities

## License

MIT
