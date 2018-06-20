---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Formats
  description: Gets a format by ID as format.
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