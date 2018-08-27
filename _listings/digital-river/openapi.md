swagger: "2.0"
x-collection-name: Digital River
x-complete: 1
info:
  title: Digital River Shopper API
  description: the-dr-connect-shopper-api-operates-on-a-store-and-products-that-are-set-up-in-global-commerce--
  version: v1
host: store.digitalriver.com
basePath: /store/{mysite}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/shoppers/me/carts/active/billing-address:
    get:
      summary: Get Shoppers Me Carts Active Billing Address
      description: Get shoppers me carts active billing address.
      operationId: getV1ShoppersMeCartsActiveBillingAddress
      x-api-path-slug: v1shoppersmecartsactivebillingaddress-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Billing
      - Ress
    put:
      summary: Put Shoppers Me Carts Active Billing Address
      description: Put shoppers me carts active billing address.
      operationId: putV1ShoppersMeCartsActiveBillingAddress
      x-api-path-slug: v1shoppersmecartsactivebillingaddress-put
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Carts
      - Active
      - Billing
      - Ress
  /v1/shoppers/me/orders/{id}/billing-address:
    get:
      summary: Get Shoppers Me Orders Billing Address
      description: Get shoppers me orders billing address.
      operationId: getV1ShoppersMeOrdersBillingAddress
      x-api-path-slug: v1shoppersmeordersidbillingaddress-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Orders
      - Billing
      - Ress