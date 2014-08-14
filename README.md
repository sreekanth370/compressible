# compressible

[![Build Status](https://travis-ci.org/expressjs/compressible.svg?branch=master)](https://travis-ci.org/expressjs/compressible)
[![NPM Version](https://badge.fury.io/js/compressible.svg)](https://badge.fury.io/js/compressible)

Compressible `Content-Type` / `mime` checking.

```sh
$ npm install compressible
```

## API

### compressible(type)

```js
var compressible = require('compressible')
compressible('text/html') // => true
compressible('image/png') // => false
```

### compressible.get(type)

Returns the specifications object associated with the given `Content-Type`.
Generates an object using the regex if none is found.

## License

The MIT License (MIT)

Copyright (c) 2013 Jonathan Ong me@jongleberry.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
