swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 1
info:
  title: Jumpseller
  description: explore-all-our-endpoints-with-your-own-set-of-of-access-tokens--all-changes-affect-your-production-jumpseller-store-
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /store/info.json:
    get:
      summary: Get Store Info
      description: ""
      operationId: getStoreInfo.json
      x-api-path-slug: storeinfo-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Store
      - Info
      - Json
  /store/languages.json:
    get:
      summary: Get Store Languages
      description: ""
      operationId: getStoreLanguages.json
      x-api-path-slug: storelanguages-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Store
      - Languages
      - Json