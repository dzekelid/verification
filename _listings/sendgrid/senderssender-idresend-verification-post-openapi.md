---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Add Senders Sender  Resend Verification
  description: |-
    **This enpdoint allows you to resend a sender identity verification email.**

    Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.
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