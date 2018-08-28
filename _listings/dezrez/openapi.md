swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/cache/{itemKey}:
    put:
      summary: Stores the {objectToPersist} in the cache subsystem.
      description: Stores the {objecttopersist} in the cache subsystem..
      operationId: Cache_SetObjectByobjectToPersistByitemKeyBytimeToLive
      x-api-path-slug: apicacheitemkey-put
      parameters:
      - in: path
        name: itemKey
        description: The item key
      - in: body
        name: objectToPersist
        description: The object to persist
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: timeToLive
        description: The time to live
      responses:
        200:
          description: OK
      tags:
      - Stores
      - ObjectToPersist
      - In
      - Cache
      - Subsystem