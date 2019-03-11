# Base64 Converter

## Description

[@hadesz/Base64](https://github.com/nestjs/nest) is a javascript tool for base64 encoding/decoding strings.

## Install

    
```base
# USE <npm>
$ npm install @hadesz/base64 --save

# USE <yarn>
$ yarn add @hadesz/base64
```

## Import
```javascript
const BASE64 = require('@hadesz/base64');    // CommonJS
// or
import BASE64 from '@hadesz/base64';         // ECMAScript
// or
import * as BASE64 from '@hadesz/base64';    // TypeScript
```

## Use
```javascript
const str_encode = BASE64.encode('12345');

console.log(str_encode);
// "MTIzNDU="

const str_decode = BASE64.decode(str_encode);

console.log(str_decode);
// "12345"

```
