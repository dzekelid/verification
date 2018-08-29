swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/EmailVerification:
    get:
      summary: Get API Emailverification
      description: Get api emailverification.
      operationId: ApiEmailVerificationGet
      x-api-path-slug: apiemailverification-get
      parameters:
      - in: query
        name: code
      - in: query
        name: email
      - in: query
        name: partnerId
      responses:
        200:
          description: OK
      tags:
      - Emailverification
    post:
      summary: Add API Emailverification
      description: Add api emailverification.
      operationId: ApiEmailVerificationPost
      x-api-path-slug: apiemailverification-post
      parameters:
      - in: body
        name: email
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Emailverification
  /api/signatureVerificationToken/KeyConfirmation:
    get:
      summary: Get API Signatureverificationtoken Keyconfirmation
      description: Get api signatureverificationtoken keyconfirmation.
      operationId: ApiSignatureVerificationTokenKeyConfirmationGet
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-get
      parameters:
      - in: query
        name: email
      responses:
        200:
          description: OK
      tags:
      - Signatureverificationtoken
      - Keyconfirmation
    post:
      summary: Add API Signatureverificationtoken Keyconfirmation
      description: Add api signatureverificationtoken keyconfirmation.
      operationId: ApiSignatureVerificationTokenKeyConfirmationPost
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-post
      parameters:
      - in: body
        name: response
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Signatureverificationtoken
      - Keyconfirmation