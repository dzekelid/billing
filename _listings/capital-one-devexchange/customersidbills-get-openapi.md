---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 0
info:
  title: Capital One DevExchange Get bills by customer id
  description: Returns the bills associated with the specific customer
  version: 1.0.0
host: api.reimaginebanking.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/bills:
    get:
      summary: Get all bills for a specific account
      description: Returns the bills that are tied to the specific account.
      operationId: returns-the-bills-that-are-tied-to-the-specific-account
      x-api-path-slug: accountsidbills-get
      parameters:
      - in: path
        name: id
        description: ID of account to fetch bills for
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Accounts
      - ""
      - Bills
    post:
      summary: Create a bill
      description: Creates a bill for the specific account
      operationId: creates-a-bill-for-the-specific-account
      x-api-path-slug: accountsidbills-post
      parameters:
      - in: body
        name: body
        description: Bill to be created
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of account that the bill will belong to
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Accounts
      - ""
      - Bills
  /bills/{billId}:
    get:
      summary: Get bill by id
      description: Returns the bill with the specific id
      operationId: returns-the-bill-with-the-specific-id
      x-api-path-slug: billsbillid-get
      parameters:
      - in: path
        name: billId
        description: ID of the bill to fetch
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Bills
      - Bill
    put:
      summary: Update a specific existing bill
      description: Updates the specific bill
      operationId: updates-the-specific-bill
      x-api-path-slug: billsbillid-put
      parameters:
      - in: path
        name: billId
        description: ID of the bill to update
      - in: body
        name: body
        description: Bill to be updated
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Bills
      - Bill
    delete:
      summary: Delete a specific existing bill
      description: Deletes the specific bill
      operationId: deletes-the-specific-bill
      x-api-path-slug: billsbillid-delete
      parameters:
      - in: path
        name: billId
        description: ID of the bill to delete
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Bills
      - Bill
  /customers/{id}/bills:
    get:
      summary: Get bills by customer id
      description: Returns the bills associated with the specific customer
      operationId: returns-the-bills-associated-with-the-specific-customer
      x-api-path-slug: customersidbills-get
      parameters:
      - in: path
        name: id
        description: ID of customer to fetch bills for
      responses:
        200:
          description: OK
      tags:
      - Banks
      - Customers
      - ""
      - Bills
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