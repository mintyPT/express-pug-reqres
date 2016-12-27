# Express Pug Req Res

## Synopsis

Simply injects the request `req` and response `res` objects into pug's locals so you can use them inside your templates.

## Code Example

### JS code

    const express        = require('express');
    const expressPugReqRes = require('express-pug-reqres');

    var app = express();

    app.use(expressPugReqRes);

    // ...

### Inside your templates

    //- For example, to print the host
    = req.get('host')

## Installation

    npm install --save express-pug-reqres


## Tests

Sorry, none.

## License

MIT License

Copyright (c) 2016 mintyPT

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

0Looking
