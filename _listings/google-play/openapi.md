swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications/{applicationId}/verify:
    get:
      summary: Verify Token
      description: Verifies the auth token provided with this request is for the application
        with the specified ID, and returns the ID of the player it was granted for.
      operationId: games.applications.verify
      x-api-path-slug: applicationsapplicationidverify-get
      parameters:
      - in: path
        name: applicationId
        description: The application ID from the Google Play developer console
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      responses:
        200:
          description: OK
      tags:
      - Token