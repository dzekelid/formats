---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /formats/:
    get:
      summary: Get Formats
      description: Returns a list of format as formats.
      operationId: getFormats
      x-api-path-slug: formats-get
      responses:
        200:
          description: OK
      tags:
      - Formats
  /formats/{id}/:
    get:
      summary: Get Formats
      description: Gets a format by ID as format.
      operationId: getFormats
      x-api-path-slug: formatsid-get
      responses:
        200:
          description: OK
      tags:
      - Formats
---