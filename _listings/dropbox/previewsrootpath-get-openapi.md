---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Content Gets a preview for a file.
  description: |-
    Gets a preview for a file.

    Previews are only generated for the files with the following extensions: .doc, .docx, .docm, .ppt, .pps,
    .ppsx, .ppsm, .pptx, .pptm, .xls, .xlsx, .xlsm, .rtf
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---