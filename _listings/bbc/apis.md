---
name: BBC
x-slug: bbc
description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
  educates and entertains - wherever you are, whatever your age.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
x-kinRank: "7"
x-alexaRank: "93"
tags: Formats
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/formats/master/_listings/bbc/apis.md
specificationVersion: "0.14"
apis:
- name: BBC Nitro Get raw formats
  x-api-slug: bbc-nitro
  description: Get raw formats
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api//v1/episodes/{pid}/formats/
  tags: V1,Episodes,Pid,Formats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/formats/master/_listings/bbc/v1episodespidformats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/formats/master/_listings/bbc/v1episodespidformats-get-openapi.md
- name: BBC Nitro
  x-api-slug: bbc-nitro
  description: Breaking news, sport, TV, radio and a whole lot more. The BBC informs,
    educates and entertains - wherever you are, whatever your age.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28554-bbc-nitro.jpg
  humanURL: http://www.bbc.com/
  baseURL: https://programmes.api.bbc.com//nitro/api
  tags: Formats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/formats/master/_listings/bbc/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/bbc-news
- type: x-email
  url: dataprotection@bbc.com
- type: x-email
  url: bbcworldwidelearning@bbc.com
- type: x-twitter
  url: https://twitter.com/BBCNews
- type: x-website
  url: http://www.bbc.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---