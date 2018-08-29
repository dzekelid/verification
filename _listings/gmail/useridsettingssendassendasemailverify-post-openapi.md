---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 0
info:
  title: Gmail Send Verification Email
  description: |-
    Sends a verification email to the specified send-as alias address. The verification status must be pending.

    This method is only available to service account clients that have been delegated domain-wide authority.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /gmail/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/settings/sendAs/{sendAsEmail}/verify:
    post:
      summary: Send Verification Email
      description: |-
        Sends a verification email to the specified send-as alias address. The verification status must be pending.

        This method is only available to service account clients that have been delegated domain-wide authority.
      operationId: gmail.users.settings.sendAs.verify
      x-api-path-slug: useridsettingssendassendasemailverify-post
      parameters:
      - in: path
        name: sendAsEmail
        description: The send-as alias to be verified
      - in: path
        name: userId
        description: Users email address
      responses:
        200:
          description: OK
      tags:
      - Verification
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