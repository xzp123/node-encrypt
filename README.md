# node-encrypt-js

## How To Use

`npm install node-encrypt-js`

Then:
```
const JSEncrypt = require('node-encrypt-js')

const encrypt = new JSEncrypt()
```
Use:
```
encrypt.setPublicKey(Public key or Private key)

encrypt.encrypt(text) or encrypt.encryptLong(text)

encrypt.decrypt(text) or encrypt.decryptLong(text)
```
