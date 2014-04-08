*This repository is a mirror of the [component](http://component.io) module [timoxley/offset](http://github.com/timoxley/offset). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/timoxley-offset`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# offset

  Get offset of a dom element within the viewport.

## Installation

    $ component install timoxley/offset

## API

### offset(el)

Get offset of an element within the viewport.

Example:

```js
var offset = require('offset')
var target = document.getElementById('target')
console.log(offset(target))
// => {top: 69, left: 108}
```


## Credit

Code adapted from jQuery.

## License

  MIT
