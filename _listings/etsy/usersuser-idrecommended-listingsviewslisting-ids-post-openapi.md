---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Post Users User Recommended Listings Views Listing S
  description: Register viewings of recommended listings. Affects future recommended
    listings.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/recommended_listings/views/{listing_ids}:
    post:
      summary: Post Users User Recommended Listings Views Listing S
      description: Register viewings of recommended listings. Affects future recommended
        listings.
      operationId: postUsersUserRecommendedListingsViewsListingS
      x-api-path-slug: usersuser-idrecommended-listingsviewslisting-ids-post
      parameters:
      - in: path
        name: listing_ids
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Recommended
      - Listings
      - Views
      - Listings
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