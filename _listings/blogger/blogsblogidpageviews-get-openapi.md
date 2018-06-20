---
swagger: "2.0"
x-collection-name: Blogger
x-complete: 0
info:
  title: Blogger API Get Blog Page Views
  description: Retrieve pageview stats for a Blog.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /blogger/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /blogs/{blogId}/pageviews:
    get:
      summary: Get Blog Page Views
      description: Retrieve pageview stats for a Blog.
      operationId: blogger.pageViews.get
      x-api-path-slug: blogsblogidpageviews-get
      parameters:
      - in: path
        name: blogId
        description: The ID of the blog to get
      - in: query
        name: range
      responses:
        200:
          description: OK
      tags:
      - Page Views
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