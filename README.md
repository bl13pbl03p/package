# package
Repository to learn the basics of node modules and npm packages.

## Installation
```shell
npm install repeat-string
```

## Usage
```js
var repeat = require('repeat-string');

/* Expose `vowel` as default function: vowel = require('this package'). */
module.exports = vowel;

/* Add other functions on `vowel`: inner = require('this package').inner. */
vowel.vowel = vowel;
vowel.inner = inner;
vowel.grawlix = grawlix;
```

## Modules
* [`repeat-string`](https://www.npmjs.com/package/repeat-string)

## What I used
* [`mochajs`](https://mochajs.org)
* [`standard`](https://github.com/standard/standard)

## Sources
* [Everything You Wanted To Know About package-lock.json But Were Too Afraid To Ask](https://medium.com/@Quigley_Ja/everything-you-wanted-to-know-about-package-lock-json-b81911aa8ab8)
* [Start your open source career](https://blog.algolia.com/start-your-open-source-career/)
* [Choose an open source license](https://choosealicense.com/)

## License
[MIT](https://github.com/jessiegouw/package/blob/master/LICENSE) © 2018 [Jessie Gouw](https://github.com/jessiegouw)
