# mixin-object [![NPM version](https://badge.fury.io/js/mixin-object.svg)](http://badge.fury.io/js/mixin-object)
> Mixin the own and inherited properties of other objects onto the first object. Pass an empty object as the first arg to shallow clone.

If you only want to combine own-properties, use [extend-shallow](https://github.com/jonschlinkert/extend-shallow).

## Install with [npm](npmjs.org)

```bash
npm i mixin-object --save
```

## Usage

```js
var mixin = require('mixin-object');

var obj = {c: 'c'};
var foo = mixin({a: 'a'}, {b: 'b'});
console.log(foo);
//=> {c: 'c', a: 'a', b: 'b'}
console.log(obj);
//=> {c: 'c'}

mixin({}, {a: 'a'}, {b: 'b'});
//=> {a: 'a', b: 'b'}
```

## Running tests
Install dev dependencies.

```bash
npm i -d && npm test
```


## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

### Other javascript/node.js utils

Other projects that I maintain:

  - [arr](https://github.com/jonschlinkert/arr)
  - [arr-diff](https://github.com/jonschlinkert/arr-diff)
  - [array-last](https://github.com/jonschlinkert/array-last)
  - [array-slice](https://github.com/jonschlinkert/array-slice)
  - [array-sum](https://github.com/jonschlinkert/array-sum)
  - [arrayify-compact](https://github.com/jonschlinkert/arrayify-compact)
  - [compact-object](https://github.com/jonschlinkert/compact-object)
  - [delete](https://github.com/jonschlinkert/delete)
  - [extend-shallow](https://github.com/jonschlinkert/extend-shallow)
  - [for-in](https://github.com/jonschlinkert/for-in)
  - [for-own](https://github.com/jonschlinkert/for-own)
  - [has-any](https://github.com/jonschlinkert/has-any)
  - [has-value](https://github.com/jonschlinkert/has-value)
  - [is-number](https://github.com/jonschlinkert/is-number)
  - [is-plain-object](https://github.com/jonschlinkert/is-plain-object)
  - [mixin-deep](https://github.com/jonschlinkert/mixin-deep)
  - [mixin-object](https://github.com/jonschlinkert/mixin-object)
  - [object-length](https://github.com/jonschlinkert/object-length)
  - [omit-empty](https://github.com/jonschlinkert/omit-empty)
  - [reduce-object](https://github.com/jonschlinkert/reduce-object)

## License
Copyright (c) 2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on February 25, 2015._