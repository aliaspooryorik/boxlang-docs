[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `JSONDeserialize`

Converts a JSON (JavaScript Object Notation) string data representation into data, such as a structure or array.

## Method Signature

```
JSONDeserialize(json=[string], strictMapping=[boolean], useCustomSerializer=[string])
```

### Arguments


| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `json` | `string` | `true` | The JSON string to convert to data. |  |
| `strictMapping` | `boolean` | `false` | A Boolean value that specifies whether to convert the JSON strictly. If true, everything becomes structures. | `true` |
| `useCustomSerializer` | `string` | `false` | A string that specifies the name of a custom serializer to use. (Not used) |  |

## Examples



## Related

  * [DataNavigate](./DataNavigate.md)
  * [JSONPrettify](./JSONPrettify.md)
  * [JSONSerialize](./JSONSerialize.md)
  * [LSParseNumber](./LSParseNumber.md)
  * [ParseNumber](./ParseNumber.md)
  * [ToBase64](./ToBase64.md)
  * [ToBinary](./ToBinary.md)
  * [ToModifiable](./ToModifiable.md)
  * [ToNumeric](./ToNumeric.md)
  * [ToScript](./ToScript.md)
  * [ToString](./ToString.md)
  * [ToUnmodifiable](./ToUnmodifiable.md)
