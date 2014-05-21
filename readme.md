#hello-world-classic
An [npm](https://www.npmjs.org) module that prints the classic [1974](http://en.wikipedia.org/wiki/Hello_world_program#History) version of 'hello, world'

Here is the entire code:
```js
module.exports = function() {
  console.log('hello, world')
}
```

#Install
```
$ npm install hello-world-classic
```

#Usage
```js
var hello = require('hello-world-classic')
hello()
```

#License
MIT
