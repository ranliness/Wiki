# 编码规范

## 命名规范

* 当我们为变量, 函数和实例命名时, 使用 camelCase 命名法.

```
// bad
var FOOBar = {};
var foo_bar = {};
function FOOBar () {}
  
  
// good
var fooBar = {};
function fooBar () {}
```

* 当我们为类或者模块命名时, 使用 PascalCase 命名法.

```
// bad
var foobar = cc.Class({ 
	foo: 'foo',
	bar:'bar',
});
var foobar = require('foo-bar');


// good
var FooBar = cc.Class({
	foo: 'foo',
	bar: 'bar',
});
var FooBar = require('foo-bar');
```

* 使用前置下划线`_`当我们为私有属性命名

```
// bad
this.firstName = 'foobar';
this.firstName_ = 'foobar';


// good
this._firstName =  'foobar' ;
```

 * 文件名我们采用 dash 命名法
```
// bad
fooBar.js
FooBar.js


// good
foo-bar.js
```
