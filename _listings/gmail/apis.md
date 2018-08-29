---
name: Gmail
x-slug: gmail
description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
  and send mail. For most web applications (including mobile apps), the Gmail API
  is the best choice for authorized access to a users Gmail data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Verification
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/gmail/apis.md
specificationVersion: "0.14"
apis:
- name: Gmail - Send Verification Email
  x-api-slug: useridsettingssendassendasemailverify-post
  description: |-
    Sends a verification email to the specified send-as alias address. The verification status must be pending.

    This method is only available to service account clients that have been delegated domain-wide authority.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users
  tags: Google APIs, Stack Network, Stack, Productivity, API Provider, Emails, Profiles,
    Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/gmail/useridsettingssendassendasemailverify-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/gmail/useridsettingssendassendasemailverify-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://globalchange.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://gmail.stack.network
- type: x-auth-scopes
  url: https://developers.google.com/gmail/api/auth/scopes
- type: x-authentication
  url: https://developers.google.com/gmail/api/auth/about-auth
- type: x-developer
  url: https://developers.google.com/gmail/api/
- type: x-documentation
  url: https://developers.google.com/gmail/api/v1/reference/
- type: x-twitter
  url: https://twitter.com/gmail
- type: x-website
  url: https://www.google.com/gmail/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---