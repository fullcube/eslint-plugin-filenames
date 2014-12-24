# eslint-plugin-filenames

[![NPM Version](https://img.shields.io/npm/v/eslint-plugin-filenames.svg?style=flat-square)](https://www.npmjs.org/package/eslint-plugin-filenames)
[![Build Status](https://img.shields.io/travis/selaux/eslint-plugin-filenames.svg?style=flat-square)](https://travis-ci.org/selaux/eslint-plugin-filenames)
[![Coverage Status](https://img.shields.io/coveralls/selaux/eslint-plugin-filenames.svg?style=flat-square)](https://coveralls.io/r/selaux/eslint-plugin-filenames?branch=master)
[![Dependencies](https://img.shields.io/david/selaux/eslint-plugin-filenames.svg?style=flat-square)](https://david-dm.org/selaux/eslint-plugin-filenames)

Adds [eslint](http://eslint.org/) rules to ensure consistent filenames for your javascript files.

## Rules

### Consistent Filenames (filenames)

A rule to enforce a certain file naming convention.

The convention can be configured using a regular expression (the default is `camelCase.js`):

```
"filenames": [2, "^[a-z_]$"]
```