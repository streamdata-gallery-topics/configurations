---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Location API Module configurations retrieval
  description: Retrieves the list of existing module configurations.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /location/v110
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /moduleConfigs:
    get:
      summary: Module configurations retrieval
      description: Retrieves the list of existing module configurations.
      operationId: retrieves-the-list-of-existing-module-configurations
      x-api-path-slug: moduleconfigs-get
      responses:
        200:
          description: OK
      tags:
      - Module
      - Configurations
      - Retrieval
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