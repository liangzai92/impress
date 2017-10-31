# impress
a web framework for node, like express, but more easier

抄一下express，学习一下

# node_modules

## Mime

A comprehensive, compact MIME type module.

```javascript
const mime = require('mime');

mime.getType('txt');                    // ⇨ 'text/plain'
mime.getExtension('text/plain');        // ⇨ 'txt'

```