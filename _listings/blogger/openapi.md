---
swagger: "2.0"
x-collection-name: Blogger
x-complete: 1
info:
  title: Blogger
  description: api-for-access-to-the-data-within-blogger-
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
---