---
swagger: "2.0"
x-collection-name: CloudFlare
x-complete: 1
info:
  title: CloudFlare
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/billing/history:
    get:
      summary: Access your billing history object
      description: Access your billing history object
      operationId: cloudflare-user-billing-history-api
      x-api-path-slug: userbillinghistory-get
      parameters:
      - in: query
        name: action
        description: The billing item actionsubscription
      - in: query
        name: occured_at
        description: When the billing item was created2014-03-01T12:21:59
      - in: query
        name: order
        description: Field to order billing history byoccured_at
      - in: query
        name: page
        description: Page number of paginated results1
      - in: query
        name: per_page
        description: Number of items per page20
      - in: query
        name: type
        description: The billing item typecharge
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Billing History
  /user/billing/profile:
    get:
      summary: Access your billing profile object
      description: Access your billing profile object
      operationId: cloudflare-user-billing-profile-api
      x-api-path-slug: userbillingprofile-get
      responses:
        200:
          description: OK
      tags:
      - Billing Profile
---