
# <img src="http://i.imgur.com/yy1sACZ.png" width="100px"/> EcmaScript 7 Tools also known as EcmaScript 2016

## Transpilers

* [Babel](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6+ features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.

## Build-time transpilation

### Grunt Tasks
* Babel: [grunt-babel](https://github.com/babel/grunt-babel) - Turn ES6+ code into vanilla ES5 with no runtime
* Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ES6+ > ES5 transpilation, [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build)

### Gulp Plugins
* Babel: [gulp-babel](https://github.com/babel/gulp-babel)
* Traceur: [gulp-traceur](https://github.com/sindresorhus/gulp-traceur)

### Broccoli Plugins
* Babel: [broccoli-babel-transpiler](https://github.com/babel/broccoli-babel-transpiler)
* Traceur: [broccoli-traceur](https://github.com/sindresorhus/broccoli-traceur)

### Brunch Plugins
* Babel: [babel-brunch](https://github.com/babel/babel-brunch)

## Webpack plugins
* Babel: [babel-loader](https://github.com/babel/babel-loader)
* Traceur: [traceur-compiler-loader](https://github.com/es-shims/es7-shim)

## Duo plugins
* Babel: [duo-babel](https://github.com/babel/duo-babel)

## Connect plugins
* Babel: [babel-connect](https://github.com/babel/babel-connect)

## Gobble plugins
* Babel: [gobble-babel](https://github.com/babel/gobble-babel)
* Traceur: [gobble-es6-transpiler](https://github.com/gobblejs/gobble-es6-transpiler)

## Jade plugins
* Babel: [jade-babel](https://github.com/babel/jade-babel)
* Traceur: [jade-traceur](https://www.npmjs.org/package/jade-traceur)

## Jest plugins
* Babel: [babel-jest](https://github.com/babel/babel-jest)

## Karma plugins
* Babel: [karma-babel-preprocessor](https://github.com/babel/karma-babel-preprocessor)
* Traceur: [karma-traceur-preprocessor](https://github.com/karma-runner/karma-traceur-preprocessor)

## Sprockets plugins
* Babel: [sprockets-es6](https://github.com/josh/sprockets-es6)
* Traceur: [sprockets-traceur](https://github.com/gunpowderlabs/sprockets-traceur)

## Boilerplates

## Code generation

## Polyfills

* [core-js](https://github.com/zloirock/core-js) - Modular and compact polyfills for ES6 including Symbols, Map, Set, Iterators, Promises, setImmediate, Array generics, etc. The standard library used by [Babel](https://github.com/babel/babel).
* [es7-shim](https://github.com/es-shims/es7-shim) - ECMAScript 7 compatibility shims for legacy JavaScript engines

## Editors

* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* ES6 syntax support in [WebStorm](https://www.jetbrains.com/webstorm/) and [PhpStorm](https://www.jetbrains.com/phpstorm/), compilation to ES5 with [Traceur file watcher](https://www.youtube.com/watch?v=jbfkcmxLLKY)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur

## Parsers

* [Esprima Harmony branch](https://github.com/ariya/esprima/tree/harmony) - Experimental branch of the Esprima parser which can parse ES6 features to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [Acorn](https://github.com/marijnh/acorn/) - A small, fast, JavaScript-based JavaScript parser with ES6 support, parses to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [esparse](https://github.com/zenparsing/esparse) - ES6 parser written in ES6.
* [Traceur compiler](https://github.com/google/traceur-compiler) also has built-in parser available under `traceur.syntax.Parser`.

## Other
