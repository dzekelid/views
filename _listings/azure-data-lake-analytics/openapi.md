---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 1
info:
  title: DataLakeAnalyticsJobManagementClient
  description: creates-an-azure-data-lake-analytics-job-client-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /catalog/usql/databases/{databaseName}/schemas/{schemaName}/views:
    get:
      summary: Catalog List Views
      description: Retrieves the list of views from the Data Lake Analytics catalog.
      operationId: Catalog_ListViews
      x-api-path-slug: catalogusqldatabasesdatabasenameschemasschemanameviews-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: path
        name: databaseName
        description: The name of the database containing the views
      - in: query
        name: No Name
      - in: path
        name: schemaName
        description: The name of the schema containing the views
      responses:
        200:
          description: OK
      tags:
      - Catalog Views
---