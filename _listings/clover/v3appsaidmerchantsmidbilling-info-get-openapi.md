---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Get merchant's billing information for an app
  version: 1.0.0
  description: Gives detailed information about the status of the merchant's billing
    for the app including current subscription tier and trial status. Requires an
    OAuth generated token.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/apps/{aId}/merchants/{mId}/billing_info:
    get:
      summary: Get merchant's billing information for an app
      description: Gives detailed information about the status of the merchant's billing
        for the app including current subscription tier and trial status. Requires
        an OAuth generated token.
      operationId: GetMerchantBillingInfo
      x-api-path-slug: v3appsaidmerchantsmidbilling-info-get
      parameters:
      - in: path
        name: aId
        description: App Id
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Apps
      - Merchants
      - Billing
      - Info
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