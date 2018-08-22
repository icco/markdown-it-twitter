# markdown-it-twitter

> Plugin for [markdown-it](https://github.com/markdown-it/markdown-it) markdown parser, adding links for @username and #hashtag.

[![Build Status](https://img.shields.io/travis/icco/markdown-it-twitter/master.svg?style=flat)](https://travis-ci.org/icco/markdown-it-twitter)
[![NPM version](https://img.shields.io/npm/v/markdown-it-twitter.svg?style=flat)](https://www.npmjs.org/package/markdown-it-twitter)
[![Coverage Status](https://coveralls.io/repos/icco/markdown-it-twitter/badge.svg?branch=master&service=github)](https://coveralls.io/github/icco/markdown-it-twitter?branch=master)

## Install

node.js, browser:

```bash
npm install markdown-it-twitter --save
```

## Use

### init

```js
var md = require('markdown-it')();
var mdtw = require('markdown-it-twitter');
md.use(mdtw [, options]);
```
