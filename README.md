## \<file-dropzone\>


`<file-dropzone>` is a drag and dropzone. You can drop a file on the dropzone area and the the file will be read using the FileReader API. You can limit the number of accepted file types by using the `accept` property.

### Example
```
  <file-dropzone
    accept="image/jpeg,audio/mpeg,audio/mp3"
    rejection-timeout="750"
    on-file-added="_onfileAdded"
    on-file-removed="_onfileRemoved"
    on-file-rejected="_onfileRejected"
    file-dragged="{{fileDragged}}"
    file-rejected="{{fileRejected}}"
  ></file-dropzone>
```