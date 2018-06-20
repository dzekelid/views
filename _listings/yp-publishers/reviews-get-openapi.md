---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 0
info:
  title: US Yellow Pages Get Reviews
  description: Returns all available user reviews for a given business listing.
  version: 1.0.0
host: api2.yp.com
basePath: /content/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reviews:
    parameters:
      summary: Parameters Reviews
      description: Parameters reviews.
      operationId: parametersReviews
      x-api-path-slug: reviews-parameters
      responses:
        200:
          description: OK
      tags:
      - Reviews
    get:
      summary: Get Reviews
      description: Returns all available user reviews for a given business listing.
      operationId: getReviews
      x-api-path-slug: reviews-get
      parameters:
      - in: query
        name: format
        description: Desired format of the response
      - in: query
        name: listingid
        description: The unique identifier for the business listing
      responses:
        200:
          description: OK
      tags:
      - Reviews
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