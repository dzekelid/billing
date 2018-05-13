---
name: Google Cloud Billing
description: The Google Cloud Billing API provides methods that you can use to programmatically
  manage billing for your projects in the Google Cloud Platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Plans
- Monetization
- Google APIs
- Billing
created: "2018-03-27"
modified: "2018-03-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google Cloud Billing API
  description: The Google Cloud Billing API provides methods that you can use to programmatically
    manage billing for your projects in the Google Cloud Platform
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: ""
  baseURL: ://cloudbilling.googleapis.com//
  tags: Billing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/v1-name-billinginfo-put.md
- name: Google Cloud Billing API Update Billing Information
  description: |-
    Sets or updates the billing account associated with a project. You specify
    the new billing account by setting the `billing_account_name` in the
    `ProjectBillingInfo` resource to the resource name of a billing account.
    Associating a project with an open billing account enables billing on the
    project and allows charges for resource usage. If the project already had a
    billing account, this method changes the billing account used for resource
    usage charges.

    *Note:* Incurred charges that have not yet been reported in the transaction
    history of the Google Cloud Console may be billed to the new billing
    account, even if the charge occurred before the new billing account was
    assigned to the project.

    The current authenticated user must have ownership privileges for both the
    [project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
    ) and the [billing
    account](https://support.google.com/cloud/answer/4430947).

    You can disable billing on the project by setting the
    `billing_account_name` field to empty. This action disassociates the
    current billing account from the project. Any billable activity of your
    in-use services will stop, and your application could stop functioning as
    expected. Any unbilled charges to date will be billed to the previously
    associated account. The current authenticated user must be either an owner
    of the project or an owner of the billing account for the project.

    Note that associating a project with a *closed* billing account will have
    much the same effect as disabling billing on the project: any paid
    resources used by the project will be shut down. Thus, unless you wish to
    disable billing, you should always call this method with the name of an
    *open* billing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: http:://cloudbilling.googleapis.com//
  tags: Billing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/google-cloud-billing/v1-name-billinginfo-put.md
x-common:
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