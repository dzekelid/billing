---
swagger: "2.0"
x-collection-name: Azure Billing API
x-complete: 1
info:
  title: ConsumptionManagementClient
  description: consumption-management-client-provides-access-to-consumption-resources-for-azure-webdirect-subscriptions-other-subscription-types-which-were-not-purchased-directly-through-the-azure-web-portal-are-not-supported-through-this-preview-api
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods:
    get:
      summary: Billing Periods List
      description: Lists the available billing periods for a subscription in reverse
        chronological order.
      operationId: BillingPeriods_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftbillingbillingperiods-get
      parameters:
      - in: query
        name: $filter
        description: May be used to filter billing periods by billingPeriodEndDate
      - in: query
        name: $skiptoken
        description: Skiptoken is only used if a previous operation returned a partial
          result
      - in: query
        name: $top
        description: May be used to limit the number of results to the most recent
          N billing periods
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Billing Period
  /subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}:
    get:
      summary: Billing Periods Get
      description: Gets a named billing period.
      operationId: BillingPeriods_Get
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftbillingbillingperiodsbillingperiodname-get
      parameters:
      - in: path
        name: billingPeriodName
        description: The name of a BillingPeriod resource
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Billing Period
---