# Single File Component Syntax

![riotjs badge](https://img.shields.io/badge/syntax-riot-%23fc0e49.svg) ![vuejs badge](https://img.shields.io/badge/syntax-vue-4fc08d.svg)

Components extend basic HTML elements to encapsulate reusable code. At a high level, components are custom elements that a compiler attaches behavior to. In some cases, they may also appear as a native HTML element extended with the special attributes like `is`, `for`, `if`, `each` etc.

This component syntax for Sublime Text 3 and 2, has been tested to work with  `Riotjs components`, `Web components` and `Polymer components`. Support for `Vuejs components` is a bit wonky; but works.

## Features
 - Additional syntax sugar over the default HTML sublime syntax.
 - CSS is scoped as`source.css.embedded.html` and uses native syntax.
 - JavaScript is scopeed as `scope.js.embedded.html` and uses native syntax.
 - Tag bindindings example: `<virtual each={ item in list } >...</virtual>` are scoped as `scope.js.embedded.html` and content between`{ ... }` is scoped as `meta.entity.block` while `{` and `}` are scoped as tag start and end.
 - Also supports [tagged template literals](https://github.com/sublimehq/Packages/issues/179).

## Installation
Copy the `sfc.sublime-syntax` file into your packages folder.
For Sublime Text 2 compile to tmLanguage using `PackageDev` and copy the `sfc.tmLanguage` file.

## License
MIT &copy; [Rayraegah](https://github.com/rayraegah)
