### drbg.js
---
https://github.com/cryptocoinjs/drbg.js

```js
var drbs = require('drbg.js')
var HashDRBG = drbgs.HashDRBG
var HmacDRBG = drbgs.HmacDRBG

var drbg2 = new HashDRBG('sha256', entropy, nonce, personalization_data)
drbg2.generate(5, additional_data)
drbg2.reseed(entropy, personalization_data)
drbg2.generate(5, additional_data)

var drbg3 = new HmacDRBG('sha256', entropy, nonce, personalization_data)
drbg3.generate(5, additional_data)
drbg3.reseed(entropy, personalization_data)
drbg3.generate(5, additional_data)

```

```sh
npm install drbg.js
```

```
```


