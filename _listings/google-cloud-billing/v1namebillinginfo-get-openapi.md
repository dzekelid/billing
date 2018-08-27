---
swagger: "2.0"
x-collection-name: Google Cloud Billing
x-complete: 0
info:
  title: Google Cloud Billing API Get Billing Information
  description: |-
    Gets the billing information for a project. The current authenticated user
    must have [permission to view the
    project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
    ).
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudbilling.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}/billingInfo:
    get:
      summary: Get Billing Information
      description: |-
        Gets the billing information for a project. The current authenticated user
        must have [permission to view the
        project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
        ).
      operationId: cloudbilling.projects.getBillingInfo
      x-api-path-slug: v1namebillinginfo-get
      parameters:
      - in: path
        name: name
        description: The resource name of the project for which billing information
          isretrieved
      responses:
        200:
          description: OK
      tags:
      - Billing
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