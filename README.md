### Jwt Authentication :: Node
Generate a random 64-byte (512-bit) hexadecimal string to be used as an access token secret.

- Import the 'crypto' module, which provides cryptographic functionality.
`const crypto = require('crypto');`

- Generate a random sequence of bytes (64 bytes in this case) using a secure cryptographic algorithm.
`const randomBytes = crypto.randomBytes(64);`

- Convert the random bytes into a hexadecimal string.
`const ACCESS_TOKEN_SECRET = randomBytes.toString('hex');`

- Log the generated access token secret to the console.
console.log('Generated Access Token Secret:', ACCESS_TOKEN_SECRET);

- Generated Access Token Secret:
    - Create a .env file in the root directory of your project if you don't already have one.

    - In the .env file, define your ACCESS_TOKEN_SECRET variable and assign it the generated value like this:

    ```
    ACCESS_TOKEN_SECRET = 767288a20bae2f20fa9c0478e50ead6ade9cb31c422230bc02f0e02fdaf57787ff6ee07326051047fc81cb69bdd2f5f02272a601da97ac6bf989efa61a05d366

    REFRESH_TOKEN_SECRET = ce8d9783d82b34371acbbb513bd6a051154ab62eafa4634316b992abbaf671985ab0f27591026a7dde7ba9e7ca247f2ff57caf5f96db08501c4206f5aed4d130
    ```