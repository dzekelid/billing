---
swagger: "2.0"
x-collection-name: Capital One DevExchange
x-complete: 1
info:
  title: Capital One DevExchange
  description: nessie-is-capital-ones-hackathon-api-that-gives-you-access-to-a-multitude-of-real-publicfacing-data--such-as-atm-and-bank-branch-locations--along-with-mock-customer-account-data--use-http-requests-to-set-up-peertopeer-transactions-simulate-a-weekly-paycheck-or-even-schedule-bills-for-customers-this-is-all-structured-in-a-way-that-resembles-how-we-actually-run-things-here-at-capital-one-
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
---