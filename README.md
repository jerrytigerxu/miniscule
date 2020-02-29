## @jeretigerxu/miniscule

![npm (scoped)](https://img.shields.io/npm/v/@jeretigerxu/miniscule)

![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@jeretigerxu/miniscule)

This is my first attempt at creating an `npm` package.

### Install

`$ npm install @jeretigerxu/miniscule`

### Usage

```javascript
const mini = require("@jeretigerxu/miniscule");

mini("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Miniscule wants a string!
//    at miniscule (<anonymous>:2:41)
//    at <anonymous>:1:1
```
