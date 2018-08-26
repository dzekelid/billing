---
name: Google Cloud Billing
x-slug: google-cloud-billing
description: The Google Cloud Billing API provides methods that you can use to programmatically
  manage billing for your projects in the Google Cloud Platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Billing
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Billing - Get Billing Information
  x-api-slug: v1namebillinginfo-get
  description: |-
    Gets the billing information for a project. The current authenticated user
    must have [permission to view the
    project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
    ).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/v1namebillinginfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/v1namebillinginfo-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.classroom.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.billing.stack.network
- type: x-code
  url: https://cloud.google.com/billing/v1/libraries
- type: x-errors
  url: https://cloud.google.com/billing/v1/errors/core_errors
- type: x-getting-started
  url: https://cloud.google.com/billing/v1/getting-started
- type: x-how-to-guides
  url: https://cloud.google.com/billing/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/billing/v1/pricing
- type: x-website
  url: https://cloud.google.com/billing/docs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---