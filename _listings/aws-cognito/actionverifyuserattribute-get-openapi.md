---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API Verify User Attribute
  version: 1.0.0
  description: Verifies the specified user attributes in the user pool.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetUserAttributeVerificationCode:
    get:
      summary: Get User Attribute Verification Code
      description: |-
        Gets the user attribute verification code for the specified attribute
                    name.
      operationId: getUserAttributeVerificationCode
      x-api-path-slug: actiongetuserattributeverificationcode-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token returned by the server response to get the user
          attribute            verification code
        type: string
      - in: query
        name: AttributeName
        description: The attribute name returned by the server response to get the
          user attribute            verification code
        type: string
      responses:
        200:
          description: OK
      tags:
      - Verification Codes
  /?Action=VerifyUserAttribute:
    get:
      summary: Verify User Attribute
      description: Verifies the specified user attributes in the user pool.
      operationId: verifyUserAttribute
      x-api-path-slug: actionverifyuserattribute-get
      parameters:
      - in: query
        name: AccessToken
        description: Represents the access token of the request to verify user attributes
        type: string
      - in: query
        name: AttributeName
        description: The attribute name in the request to verify user attributes
        type: string
      - in: query
        name: Code
        description: The verification code in the request to verify user attributes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
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