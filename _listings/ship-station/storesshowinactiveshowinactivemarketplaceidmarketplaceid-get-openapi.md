---
swagger: "2.0"
x-collection-name: Ship Station
x-complete: 0
info:
  title: Ship Station List Stores
  description: Retrieve the list of installed stores on the account.
  version: 1.0.0
host: ssapi.shipstation.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stores?showInactive={showInactive}&marketplaceId={marketplaceId}:
    get:
      summary: List Stores
      description: Retrieve the list of installed stores on the account.
      operationId: stores_showInactive_showInactive_marketplaceId_marketplaceId.get
      x-api-path-slug: storesshowinactiveshowinactivemarketplaceidmarketplaceid-get
      parameters:
      - in: path
        name: marketplaceId
        description: Returns stores of this marketplace type
      - in: path
        name: showInactive
        description: Determines whether inactive stores will be returned in the list
          of stores
      responses:
        200:
          description: OK
      tags:
      - List
      - Stores
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