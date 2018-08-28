swagger: "2.0"
x-collection-name: AWS Polly
x-complete: 1
info:
  title: AWS Polly API
  version: 1.0.0
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