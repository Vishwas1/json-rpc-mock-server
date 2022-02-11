# JSON RPC mock server

## installation & run

```
npm i
npm run mock-server
```

The server will run on port `3333`

## `resolve_did` 

Use this playground (https://playground.open-rpc.org/) to try the mock server out

RPC request

```json
{
    "jsonrpc": "2.0",
    "method": "resolve_did",
    "params": [
        "did:v2:hs:c379647a-7a07-4a4c-8a47-1de96f843085"
    ],
    "id": 0
}
```

Response

```json
{
    "jsonrpc": "2.0",
    "result": {
        "@context": [
            "ut dolor aliqua",
            "minim do ad deserunt incididunt"
        ],
        "type": "ut",
        "id": "did:v5:hs:",
        "name": "reprehenderit dolor sunt esse",
        "publicKey": [
            {
                "id": "culpa Lorem cillum",
                "context": "amet sit sed",
                "type": "ea tempor",
                "publicKeyBase58": "fugiat",
                "consequat8": "ex nostrud",
                "proidentfd": false,
                "magna_0fb": -95062415,
                "est_66": false
            },
            {
                "context": "in amet",
                "type": "laborum consequat commodo occaecat",
                "publicKeyBase58": "irure minim dolore velit",
                "consectetur6": -51689568,
                "reprehenderit_8bd": "in Excepteur quis pariatur",
                "pariatur_f9": false,
                "minimfc": 1898455.0166549385
            },
            {
                "id": "ea ut aliquip",
                "publicKeyBase58": "mollit"
            }
        ],
        "authentication": [
            "in Ut",
            "quis eu proident enim voluptate",
            "sint nulla adipisicing",
            "pariatur sed non in veniam",
            "qui nulla veniam Duis"
        ],
        "assertionMethod": [
            "quis Duis",
            "dolore officia",
            "cillum nulla exercitation consequat mollit"
        ],
        "keyAgreement": [
            "ut minim magna laborum",
            "veniam quis",
            "et",
            "reprehenderit laborum cillum ad irure",
            "aute"
        ],
        "capabilityInvocation": [
            "culpa minim tempor sunt nostrud"
        ],
        "created": "ipsum irure",
        "updated": "ea Lorem sit"
    },
    "id": 0
}
```



## Reference

- https://medium.com/@stevan.blog/using-openrpc-mock-server-to-test-against-an-ethereum-json-rpc-api-50b86b6d02d6


