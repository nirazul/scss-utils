# scss-utils
A collection of sass utility functions and mixins.

[![Build Status][workflow-image]][workflow-url]
[![NPM version][npm-version-image]][npm-url]
[![NPM downloads][npm-downloads-image]][npm-url]
[![CC0-1.0][license-image]][license-url]

# Installation
```bash
npm i -S @nirazul/scss-utils
```

# Usage
Implement collections, functions and mixins via [sass module syntax](https://sass-lang.com/documentation/at-rules/use) `@use`.
<br>
You have the choice to implement packages, different in size:

- `@use '@nirazul/scss-utils'` loads the whole module
- `@use '@nirazul/scss-utils/mixin'` loads all mixins
- `@use '@nirazul/scss-utils/function'` loads all functions
- `@use '@nirazul/scss-utils/function/list'` loads all list functions
- `@use '@nirazul/scss-utils/function/list/concat'` loads the concat function

# Documentation
<!-- TODO -->

[workflow-image]:https://img.shields.io/github/workflow/status/nirazul/scss-utils/test?style=flat-square
[workflow-url]:https://github.com/nirazul/scss-utils/actions

[license-image]:https://img.shields.io/github/license/nirazul/scss-utils?style=flat-square
[license-url]:LICENSE

[npm-version-image]:https://img.shields.io/npm/v/@nirazul/scss-utils?style=flat-square
[npm-downloads-image]:https://img.shields.io/npm/dm/@nirazul/scss-utils.svg?style=flat-square
[npm-url]:https://npmjs.org/package/@nirazul/scss-utils
