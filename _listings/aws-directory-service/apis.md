---
name: AWS Directory Service
x-slug: aws-directory-service
description: AWS Directory Service for Microsoft Active Directory (Enterprise Edition),
  also known as AWS Microsoft AD, enables your directory-aware workloads and AWS resources
  to use managed Active Directory in the AWS Cloud. The Microsoft AD service is built
  on actual Microsoft Active Directory and does not require you to synchronize or
  replicate data from your existing Active Directory to the cloud. You can use standard
  Active Directory administration tools and take advantage of built-in Active Directory
  features such as Group Policy, trusts, and single sign-on. With Microsoft AD, you
  can easily joinAmazon EC2andAmazon RDS for SQL Serverinstances to a domain, and
  useAWS Enterprise IT applicationssuch asAmazon WorkSpaceswith Active Directory users
  and groups.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Verification
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/aws-directory-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Directory Service API - Verify Trust
  x-api-slug: actionverifytrust-get
  description: AWS Directory Service for Microsoft Active Directory allows you to
    configure and verify trust relationships.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSDirectoryService.png
  humanURL: https://aws.amazon.com/directoryservice/
  baseURL: :///
  tags: Amazon Web Services, Discovery, Authentication, Security, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/aws-directory-service/actionverifytrust-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/verification/master/_listings/aws-directory-service/actionverifytrust-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.direct.connect.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.directory.service.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/ds/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/directoryservice/latest/devguide/api-ref.html
- type: x-faq
  url: https://aws.amazon.com/directoryservice/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/directoryservice/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/directoryservice/pricing/
- type: x-website
  url: https://aws.amazon.com/directoryservice/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---