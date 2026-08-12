![Seneca](http://senecajs.org/files/assets/seneca-logo.png)
> A [Seneca.js](http://senecajs.org) plugin

# @seneca/doc-spider

[![npm version](https://img.shields.io/npm/v/@seneca/file-spider.svg)](https://npmjs.com/package/@seneca/file-spider)
[![build](https://github.com/senecajs/seneca-file-spider/actions/workflows/build.yml/badge.svg)](https://github.com/senecajs/seneca-file-spider/actions/workflows/build.yml)
[![Coverage Status](https://coveralls.io/repos/github/senecajs/seneca-file-spider/badge.svg?branch=main)](https://coveralls.io/github/senecajs/seneca-file-spider?branch=main)
[![Known Vulnerabilities](https://snyk.io/test/github/senecajs/seneca-file-spider/badge.svg)](https://snyk.io/test/github/senecajs/seneca-file-spider)

| ![Voxgig](https://www.voxgig.com/res/img/vgt01r.png) | This open source module is sponsored and supported by [Voxgig](https://www.voxgig.com). |
|---|---|

Document spider plugin for the Seneca platform.

## Install

```sh
$ npm install @seneca/file-spider
```

## Quick Example

```js
// Setup - get the key value (<SECRET>) separately from a vault or
// environment variable.
Seneca().use('file-spider', {})

TODO
```

## More Examples

See [test/](test/) for more usage examples.

## Motivation

A [Seneca.js](http://senecajs.org) plugin.

## Support

If you're using this module and need help, you can:

- Post a [github issue](https://github.com/senecajs/seneca-doc-spider/issues)
- Tweet to [@senecajs](http://twitter.com/senecajs)
- Ask on the [Gitter](https://gitter.im/senecajs/seneca)

## API

### Options

_None._

### Action Patterns

* [accept:entry,biz:file-spider](#-acceptentrybizrefer-)
* [biz:file-spider,create:entry](#-bizrefercreateentry-)
* [biz:file-spider,ensure:entry](#-bizreferensureentry-)
* [biz:file-spider,give:award](#-bizrefergiveaward-)
* [biz:file-spider,load:entry](#-bizreferloadentry-)
* [biz:file-spider,load:rules](#-bizreferloadrules-)
* [biz:file-spider,lost:entry](#-bizreferlostentry-)
* [biz:file-spider,update:occur](#-bizreferupdateoccur-)
* [biz:file-spider,update:entry](#-bizreferupdateentry-)

### Action Descriptions

### &laquo; `accept:entry,biz:file-spider` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,create:entry` &raquo;

Create referral entry.



----------
### &laquo; `biz:file-spider,ensure:entry` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,give:award` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,load:entry` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,load:rules` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,lost:entry` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,update:occur` &raquo;

No description provided.



----------
### &laquo; `biz:file-spider,update:entry` &raquo;

No description provided.



----------

## Contributing

The [Senecajs org](https://github.com/senecajs/) encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

### Running tests

```sh
npm run test
```

## Background

Part of the [Senecajs org](https://github.com/senecajs/).
