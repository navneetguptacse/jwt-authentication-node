### Jwt Authentication :: Node

`ACCESS_TOKEN_SECRET = 767288a20bae2f20fa9c0478e50ead6ade9cb31c422230bc02f0e02fdaf57787ff6ee07326051047fc81cb69bdd2f5f02272a601da97ac6bf989efa61a05d366`

`REFRESH_TOKEN_SECRET = ce8d9783d82b34371acbbb513bd6a051154ab62eafa4634316b992abbaf671985ab0f27591026a7dde7ba9e7ca247f2ff57caf5f96db08501c4206f5aed4d130`

- create `ACCESS_TOKEN_SECRET`:
    - `const ACCESS_TOKEN_SECRET = require('crypto').randomBytes(64).toString('hex');`
    - `console.log(ACCESS_TOKEN_SECRET)`