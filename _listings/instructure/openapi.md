---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Users API
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/page_views:
    get:
      summary: List user page views
      description: List user page views.
      operationId: list-user-page-views
      x-api-path-slug: usersuser-idpage-views-get
      parameters:
      - in: query
        name: end_time
        description: The end of the time range from which you want page views
      - in: query
        name: start_time
        description: The beginning of the time range from which you want page views
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Page
      - Views
---