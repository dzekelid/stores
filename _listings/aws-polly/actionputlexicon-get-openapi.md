---
swagger: "2.0"
x-collection-name: AWS Polly
x-complete: 0
info:
  title: AWS Polly API Put Lexicon
  version: 1.0.0
  description: Stores a pronunciation lexicon in an AWS Region.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutLexicon:
    get:
      summary: Put Lexicon
      description: Stores a pronunciation lexicon in an AWS Region.
      operationId: putLexicon
      x-api-path-slug: actionputlexicon-get
      parameters:
      - in: query
        name: Name
        description: Name of the lexicon
        type: string
      responses:
        200:
          description: OK
      tags:
      - Lexicons
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