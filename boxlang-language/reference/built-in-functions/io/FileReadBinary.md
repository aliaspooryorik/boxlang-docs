[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `FileReadBinary`

Reads the contents of a file and returns it as a string or binary object

## Method Signature

```
FileReadBinary(filepath=[string], charsetOrBufferSize=[string], charset=[string], buffersize=[string])
```

### Arguments


| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `filepath` | `string` | `true` | The path to the file to read. |  |
| `charsetOrBufferSize` | `string` | `false` | Either the charset to use when reading the file, or the buffer size to use when reading the file. If providing a buffer size, the next argument can be the charset. |  |
| `charset` | `string` | `false` | The explicit charset to use when reading the file. |  |
| `buffersize` | `string` | `false` | The explicit buffer size to use when reading the file. |  |

## Examples



## Related

  * [ContractPath](./ContractPath.md)
  * [CreateTempDirectory](./CreateTempDirectory.md)
  * [CreateTempFile](./CreateTempFile.md)
  * [DirectoryCopy](./DirectoryCopy.md)
  * [DirectoryCreate](./DirectoryCreate.md)
  * [DirectoryDelete](./DirectoryDelete.md)
  * [DirectoryExists](./DirectoryExists.md)
  * [DirectoryList](./DirectoryList.md)
  * [DirectoryMove](./DirectoryMove.md)
  * [DirectoryRename](./DirectoryRename.md)
  * [ExpandPath](./ExpandPath.md)
  * [FileAppend](./FileAppend.md)
  * [FileClose](./FileClose.md)
  * [FileCopy](./FileCopy.md)
  * [FileDelete](./FileDelete.md)
  * [FileExists](./FileExists.md)
  * [FileGetMimeType](./FileGetMimeType.md)
  * [FileInfo](./FileInfo.md)
  * [FileIsEOF](./FileIsEOF.md)
  * [FileMove](./FileMove.md)
  * [FileOpen](./FileOpen.md)
  * [FileRead](./FileRead.md)
  * [FileReadLine](./FileReadLine.md)
  * [FileSeek](./FileSeek.md)
  * [FileSetAccessMode](./FileSetAccessMode.md)
  * [FileSetAttribute](./FileSetAttribute.md)
  * [FileSetLastModified](./FileSetLastModified.md)
  * [FileSkipBytes](./FileSkipBytes.md)
  * [FileWrite](./FileWrite.md)
  * [FileWriteLine](./FileWriteLine.md)
  * [GetCanonicalPath](./GetCanonicalPath.md)
  * [GetDirectoryFromPath](./GetDirectoryFromPath.md)
  * [GetFileInfo](./GetFileInfo.md)
  * [getTempFile](./getTempFile.md)
