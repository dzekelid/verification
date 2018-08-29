swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 1
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=VerifyTrust:
    get:
      summary: Verify Trust
      description: AWS Directory Service for Microsoft Active Directory allows you
        to configure and verify trust relationships.
      operationId: verifyTrust
      x-api-path-slug: actionverifytrust-get
      parameters:
      - in: query
        name: TrustId
        description: The unique Trust ID of the trust relationship to verify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust