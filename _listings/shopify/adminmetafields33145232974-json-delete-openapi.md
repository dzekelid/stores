---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Delete a store metafield
  description: Delete a store metafield.
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/metafields.json:
    get:
      summary: Get all metafields that belong to a store
      description: Get all metafields that belong to a store.
      operationId: getAdminMetafields.json
      x-api-path-slug: adminmetafields-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Metafields
      - That
      - Belong
      - To
      - Store
    post:
      summary: Create a new metafield for a store.
      description: Create a new metafield for a store..
      operationId: postAdminMetafields.json
      x-api-path-slug: adminmetafields-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Metafielda
      - Store
  /admin/metafields/33145232974.json:
    get:
      summary: Get a single store metafield by ID
      description: Get a single store metafield by id.
      operationId: getAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Store
      - Metafield
      - By
      - ID
    put:
      summary: Update an existing store metafield.
      description: Update an existing store metafield..
      operationId: putAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Existing
      - Store
      - Metafield
    delete:
      summary: Delete a store metafield
      description: Delete a store metafield.
      operationId: deleteAdminMetafields33145232974.json
      x-api-path-slug: adminmetafields33145232974-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Store
      - Metafield
  /admin/metafields/count.json:
    get:
      summary: Get a count of all metafields for a store
      description: Get a count of all metafields for a store.
      operationId: getAdminMetafieldsCount.json
      x-api-path-slug: adminmetafieldscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Metafieldsa
      - Store
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