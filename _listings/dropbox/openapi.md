---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Content API v1
  description: the-dropbox-content-api-is-a-part-of-dropbox-core-api-with-a-separate-endpoint-for-file-content-management-operations-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api-content.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /previews/{root}/{path}:
    get:
      summary: Gets a preview for a file.
      description: |-
        Gets a preview for a file.

        Previews are only generated for the files with the following extensions: .doc, .docx, .docm, .ppt, .pps,
        .ppsx, .ppsm, .pptx, .pptm, .xls, .xlsx, .xlsm, .rtf
      operationId: gets-a-preview-for-a-filepreviews-are-only-generated-for-the-files-with-the-following-extensions-doc
      x-api-path-slug: previewsrootpath-get
      parameters:
      - in: path
        name: path
        description: The absolute path to the file you want to preview
      - in: query
        name: rev
        description: The revision of the file to retrieve
      - in: path
        name: root
        description: 'Root folder: `auto` - automatically determines the appropriate
          root folder using your apps permissionlevel (recommended); `sandbox` - the
          codename for app folder level; `dropbox` - full dropbox access'
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Previews
      - Root
      - Path
---