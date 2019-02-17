snapshot.json
=============


Example **snapshot.json**:

```
{
    "stream": {
        "id": {
            "canonical": "",
            "aliases": [
            ]
        },
        "owner": {
            "id": "<canonicalID (e.g. public key hash)>"
        }
    },
    "id": {
        "canonical": "",
        "aliases": [
        ]
    },
    "ts": 123456789,
    "tags": {
        "foo": "bar"
    },
    "items": {
        "<CanonicalID>": {
            ... source, hash, ...
        }
    },
    "signature": {
        ...
    }
}
```
