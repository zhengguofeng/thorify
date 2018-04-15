## thorjs-provider-http

A simple provider module for VeChain Thor RESTful HTTP API.

## Install

```
npm install --save thorjs-provider-http
```

## Usage

```js
const HttpProvider = require('thorjs-provider-http');
const Web3 = require('web3');
const thor = new Web3(new HttpProvider('http://localhost:8669'));

thor.getBlock();
```

## Current Web3 method supported:

## About

A simple provider module for the HTTP protocol that follows the web3 provider specification. This is purely an HTTP bypass using the XHR2 module.


## Licence

This project is licensed under the MIT license, Copyright (c) 2017 VeChain Foundation. For more information see LICENSE.md.

```
The MIT License

Copyright (c) 2017 VeChain Foundation

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
```
