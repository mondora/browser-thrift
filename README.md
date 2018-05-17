# @mondora/universal-thrift

Patched version of Apache Thrift Node.js library to work either with Webpack /
Browserify or with nodejs. Fork of
[vh/browser-thrift](https://github.com/vh/browser-thrift).

### Usage

It is necessary to replace all `require('thrift')` with
`require('@mondora/universal-thrift')` in the thrift generated files.
