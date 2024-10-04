# Hash

Creates an algorithmic hash of an object

## Method Signature

```
Hash(input=[any], algorithm=[string], encoding=[string], numIterations=[integer])
```

### Arguments

| Argument        | Type      | Required | Description                                                                    | Default |
| --------------- | --------- | -------- | ------------------------------------------------------------------------------ | ------- |
| `input`         | `any`     | `true`   | The item to be hashed                                                          |         |
| `algorithm`     | `string`  | `false`  | The supported {@link java.security.MessageDigest} algorithm (case-insensitive) | `MD5`   |
| `encoding`      | `string`  | `false`  | Applicable to strings ( default "utf-8" )                                      | `utf-8` |
| `numIterations` | `integer` | `false`  |                                                                                | `1`     |

## Examples

## Related

* [Decrypt](decrypt.md)
* [Encrypt](encrypt.md)
* [EncryptBinary](encryptbinary.md)
* [GeneratePDBKDFKey](generatepdbkdfkey.md)
* [GenerateSecretKey](generatesecretkey.md)
* [Hash40](hash40.md)
* [Hmac](hmac.md)
