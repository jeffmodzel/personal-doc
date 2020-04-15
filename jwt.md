# JWT

manual way

https://levelup.gitconnected.com/deriving-signing-and-verifying-a-jwt-json-web-token-with-node-js-f3d0d12b1fc9


```
    const base64 = require('base64url');

    const headerObj = {
        alg: 'RS256',
        typ: 'JWT'
    };
    
    const payloadObj = {
        iss: "client_id here",
        aud: "",
        sub: 'salesforce user',
        exp: 1231231231
    };
  
    const headerObjString = JSON.stringify(headerObj);
    const payloadObjString = JSON.stringify(payloadObj);

    const base64UrlHeader = base64(headerObjString);
    const base64UrlPayload = base64(payloadObjString);

    return base64UrlHeader + "." + base64UrlPayload;
```
