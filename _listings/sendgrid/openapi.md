swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /senders/{sender_id}/resend_verification:
    post:
      summary: Add Senders Sender  Resend Verification
      description: |-
        **This enpdoint allows you to resend a sender identity verification email.**

        Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.
      operationId: senders.sender_id.resend_verification.post
      x-api-path-slug: senderssender-idresend-verification-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Senders
      - Sender
      - ""
      - Resend
      - Verification