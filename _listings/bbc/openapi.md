---
swagger: "2.0"
x-collection-name: BBC
x-complete: 1
info:
  title: BBC Nitro
  description: bbc-nitro-is-the-bbcs-application-programming-interface-api-for-bbc-programmes-metadata-
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/episodes/{pid}/formats/:
    get:
      summary: Get raw formats
      description: Get raw formats
      operationId: Get_Raw_formats
      x-api-path-slug: v1episodespidformats-get
      parameters:
      - in: path
        name: pid
      responses:
        200:
          description: OK
      tags:
      - V1
      - Episodes
      - Pid
      - Formats
---