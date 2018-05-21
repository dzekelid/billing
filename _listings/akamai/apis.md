---
name: Akamai
x-slug: akamai
description: Akamai Technologies, Inc. is a content delivery network or CDN and cloud
  services provider headquartered in Cambridge, Massachusetts, in the United States.
  Akamais content delivery network is one of the worlds largest distributed computing
  platforms, responsible for serving between 15 and 30 percent of all web traffic.
  The company operates a network of servers around the world and rents capacity on
  these servers to customers who want their websites to work faster by distributing
  content from locations close to the user
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Billing
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/apis.md
specificationVersion: "0.14"
apis:
- name: Akamai API List Statistics per Contract
  x-api-slug: akamai-api
  description: List Statistics per Contract
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/contracts/{contractId}/products/{productId}/statistics
  tags: Billing, Center, Contracts, Contract, Products, Product, Statistics, Year,month,fromyear,frommonth,toyear,tomonth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/billingcenterapiv2contractscontractidproductsproductidstatistics-get-openapi.md
- name: Akamai API List Usage per Contract
  x-api-slug: akamai-api
  description: List Usage per Contract
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/contracts/{contractId}/products/{productId}/measures
  tags: Billing, Center, Contracts, Contract, Products, Product, Measures, Year,month,fromyear,frommonth,toyear,tomonth,statisticname,billingdayonly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/billingcenterapiv2contractscontractidproductsproductidmeasures-get-openapi.md
- name: Akamai API List Statistics per Reporting Group
  x-api-slug: akamai-api
  description: List Statistics per Reporting Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/statistics
  tags: Billing, Center, Reporting, Groups, Reportinggroup, Products, Product, Statistics,
    Year,month,fromyear,frommonth,toyear,tomonth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatistics-get-openapi.md
- name: Akamai API List Usage per Reporting Group
  x-api-slug: akamai-api
  description: List Usage per Reporting Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/measures
  tags: Billing, Center, Reporting, Groups, Reportinggroup, Products, Product, Measures,
    Year,month,fromyear,frommonth,toyear,tomonth,statisticname,billingdayonly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasures-get-openapi.md
- name: Akamai API Download Geobilling Files
  x-api-slug: akamai-api
  description: Download Geobilling Files
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/contracts/{contractId}/products/{productId}/geo-billing-files
  tags: Invoicing, Contracts, Contract, Products, Product, Geo, Billing, Files, Year,month,day
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/invoicingapiv2contractscontractidproductsproductidgeobillingfiles-get-openapi.md
- name: Akamai API
  x-api-slug: akamai-api
  description: Akamai Technologies, Inc. is a content delivery network or CDN and
    cloud services provider headquartered in Cambridge, Massachusetts, in the United
    States. Akamais content delivery network is one of the worlds largest distributed
    computing platforms, responsible for serving between 15 and 30 percent of all
    web traffic. The company operates a network of servers around the world and rents
    capacity on these servers to customers who want their websites to work faster
    by distributing content from locations close to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com//
  tags: Billing
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/billing/master/_listings/akamai/openapi.md
x-common:
- type: x-base
  url: https://api.ccu.akamai.com
- type: x-blog
  url: https://blogs.akamai.com
- type: x-blog-rss
  url: http://blogs.akamai.com/feeds.html
- type: x-crunchbase
  url: http://www.crunchbase.com/company/akamai-technologies
- type: x-developer
  url: https://developer.akamai.com/
- type: x-email
  url: open-developer@akamai.com
- type: x-github
  url: https://github.com/akamai
- type: x-twitter
  url: https://twitter.com/Akamai
- type: x-website
  url: https://akamai.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---