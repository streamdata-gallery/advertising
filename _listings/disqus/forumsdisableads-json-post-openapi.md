---
swagger: "2.0"
x-collection-name: Disqus
x-complete: 0
info:
  title: Disqus Forums DisableAds
  description: Forums DisableAds
  termsOfService: https://docs.disqus.com/kb/terms-and-policies/
  version: 1.0.0
host: disqus.com
basePath: api/3.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forums/disableAds.json:
    post:
      summary: Forums DisableAds
      description: Forums DisableAds
      operationId: forums-disableads
      x-api-path-slug: forumsdisableads-json-post
      parameters:
      - in: query
        name: forum
        description: Looks up a forum by ID (aka short name) You must be a moderator
          on the selected forum
        type: string
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Forums
      - Advertising
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