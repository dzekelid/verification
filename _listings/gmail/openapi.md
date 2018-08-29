swagger: "2.0"
x-collection-name: Gmail
x-complete: 1
info:
  title: Gmail
  version: 1.0.0
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