[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `StructNew`

Creates a new struct of the specified type.

The available types are:
 - casesensitive
 - default
 - ordered-casesensitive
 - ordered
 - soft
 - sorted
 - weak

## Method Signature

```
StructNew(type=[string], sortType=[any], sortOrder=[string], localeSensitive=[any], callback=[function:Comparator])
```

### Arguments


| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `type` | `string` | `false` | The struct type | `default` |
| `sortType` | `any` | `false` | An optional sort type to apply to that type |  |
| `sortOrder` | `string` | `false` | The sort order applicable to the sortType argument | `asc` |
| `localeSensitive` | `any` | `false` |  | `false` |
| `callback` | `function:Comparator` | `false` | An optional callback to use as the sorting function. You can alternatively pass a Java Comparator. |  |

## Examples



## Related

  * [StructAppend](./StructAppend.md)
  * [StructClear](./StructClear.md)
  * [StructCopy](./StructCopy.md)
  * [StructDelete](./StructDelete.md)
  * [StructEach](./StructEach.md)
  * [StructEquals](./StructEquals.md)
  * [StructEvery](./StructEvery.md)
  * [StructFilter](./StructFilter.md)
  * [StructFind](./StructFind.md)
  * [StructFindKey](./StructFindKey.md)
  * [StructFindValue](./StructFindValue.md)
  * [StructGet](./StructGet.md)
  * [StructGetMetadata](./StructGetMetadata.md)
  * [StructInsert](./StructInsert.md)
  * [StructIsCaseSensitive](./StructIsCaseSensitive.md)
  * [StructIsOrdered](./StructIsOrdered.md)
  * [StructKeyArray](./StructKeyArray.md)
  * [StructKeyExists](./StructKeyExists.md)
  * [StructKeyList](./StructKeyList.md)
  * [StructKeyTranslate](./StructKeyTranslate.md)
  * [StructMap](./StructMap.md)
  * [StructReduce](./StructReduce.md)
  * [StructSome](./StructSome.md)
  * [StructSort](./StructSort.md)
  * [StructToQueryString](./StructToQueryString.md)
  * [StructToSorted](./StructToSorted.md)
  * [StructUpdate](./StructUpdate.md)
  * [StructValueArray](./StructValueArray.md)
