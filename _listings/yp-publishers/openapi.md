---
swagger: "2.0"
x-collection-name: YP Publishers
x-complete: 1
info:
  title: Yellow Pages
  description: use-yp-places-api-to-power-your-web-and-mobile-apps-with-business-listings-reviews-maps-and-much-more---
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
---