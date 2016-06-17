# JavaScript Snippets for Sublime [![Build Status](https://secure.travis-ci.org/zenorocha/sublime-javascript-snippets.svg?branch=master)](https://travis-ci.org/zenorocha/sublime-javascript-snippets)

![Demo](https://cloud.githubusercontent.com/assets/398893/3528110/d55390be-078b-11e4-8587-db23277b50af.gif)

## Install

~~To install through [Package Control](http://wbond.net/sublime_packages/package_control),
search for **JavaScript & NodeJS Snippets**. If you still don't have Package Control in Sublime Text, [go get it](http://wbond.net/sublime_packages/package_control/installation).
It's pure awesomeness.~~

If you prefer to install it manually, you can download the package and put it inside your `Packages` directory. It should work but will not update automatically.

## Console

### [cd] console.dir

```javascript
console.dir(${1:obj});
```

### [ce] console.error

```javascript
console.error(${1:obj});
```

### [cl] console.log

```javascript
console.log(${1:obj});
```

### [cw] console.warn

```javascript
console.warn(${1:obj});
```

### [de] debugger

```javascript
debugger;
```


## Loop

### [fe] forEach

```javascript
${1:myArray}.forEach(function(${2:item}) {
	${3}
});
```

### [fi] for in

```javascript
for (${1:prop} in ${2:obj}) {
	if (${2:obj}.hasOwnProperty(${1:prop})) {
		${3}
	}
}
```

## Function

### [fn] function

```javascript
function ${1:methodName}(${2:arguments}) {
	${3}
}
```

### [afn] anonymous function

```javascript
function(${1:arguments}) {
	${2}
}
```

### [iife] immediately-invoked function expression

```javascript
(function(window, document, undefined) {
	${1}
})(window, document);
```

### [ofn] function as a property of an object

```javascript
${1:functionName}: function(${2:arguments}) {
	${3}
}
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	${2}
}, ${1:delay});
```

### [st] setTimeout

```javascript
setTimeout(function() {
	${2}
}, ${1:delay});
```

## NodeJS

### [me] module.exports

```javascript
module.exports = ${1:name};
```

### [pe] process.exit

```javascript
process.exit(${1:code});
```

### [re] require

```javascript
require('${1:module}');
```
## BDD

### [desc] describe

```javascript
describe('${1:description}', function() {
	${2}
});
```

### [its] it synchronous

```javascript
it('${1:description}', function() {
	${2}
});
```

### [itp] it pending

```javascript
it('${1:description}');
```

## Misc

### [us] use strict

```javascript
'use strict';
```

### [al] alert

```javascript
alert('${1:msg}');
```

### [co] confirm

```javascript
confirm('${1:msg}');
```

### [pm] prompt

```javascript
prompt('${1:msg}');
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Releases](https://github.com/zenorocha/sublime-javascript-snippets/releases) for detailed changelog.

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha
