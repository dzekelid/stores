---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Deactivate a client (store)
  description: Deactivates a client (store) for a sales price. The ID of the sales
    price and the ID of the client (store) must be specified.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/legalinformation/{plentyId}/{lang}/{type}:
    get:
      summary: Get legal information of an online store
      description: Gets legal information of an online store. The plenty ID of the
        store , the language and the type of legal information must be specified.
        The language must be specified as ISO 639-1 code.
      operationId: getRestLegalinformationPlentyLangType
      x-api-path-slug: restlegalinformationplentyidlangtype-get
      parameters:
      - in: path
        name: lang
      - in: path
        name: plentyId
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Legal
      - Information
      - Of
      - Online
      - Store
    put:
      summary: Save legal information for an online store
      description: |-
        Saves a legal information for an online store. The plenty ID of the online store, the language of the legal information and the type of the legal information must be specified. The language must be specified as ISO 639-1 code.
        Existing legal information will be overwritten.
      operationId: putRestLegalinformationPlentyLangType
      x-api-path-slug: restlegalinformationplentyidlangtype-put
      parameters:
      - in: body
        name: /rest/legalinformation/{plentyId}/{lang}/{type}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: lang
      - in: path
        name: plentyId
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Save
      - Legal
      - Informationan
      - Online
      - Store
  /rest/items/sales_prices/{id}/online_stores:
    get:
      summary: List activated clients (stores)
      description: Lists all activated clients (stores) for a sales price. The ID
        of the sales price must be specified.
      operationId: getRestItemsSalesPricesOnlineStores
      x-api-path-slug: restitemssales-pricesidonline-stores-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Clients
      - (stores)
    post:
      summary: Activate a client (store)
      description: Activates a client (store) for a sales price. The ID of the sales
        price must be specified.
      operationId: postRestItemsSalesPricesOnlineStores
      x-api-path-slug: restitemssales-pricesidonline-stores-post
      parameters:
      - in: body
        name: /rest/items/sales_prices/{id}/online_stores
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Client
      - (store)
  /rest/webstores:
    get:
      summary: List clients (stores)
      description: List clients (stores).
      operationId: getRestWebstores
      x-api-path-slug: restwebstores-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Clients
      - (stores)
  /rest/items/sales_prices/{id}/online_stores/{webstoreId}:
    delete:
      summary: Deactivate a client (store)
      description: Deactivates a client (store) for a sales price. The ID of the sales
        price and the ID of the client (store) must be specified.
      operationId: deleteRestItemsSalesPricesOnlineStoresWebstore
      x-api-path-slug: restitemssales-pricesidonline-storeswebstoreid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: webstoreId
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Client
      - (store)
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