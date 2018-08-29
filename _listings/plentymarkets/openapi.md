swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/listings/markets/verify/{id?}:
    post:
      summary: Verify listing markets
      description: Verifies the listing markets.
      operationId: postRestListingsMarketsVerify
      x-api-path-slug: restlistingsmarketsverifyid-post
      parameters:
      - in: query
        name: id
        description: The ID of the listing market that need to be verified
      - in: path
        name: id?
      responses:
        200:
          description: OK
      tags:
      - Verify
      - Listing
      - Markets