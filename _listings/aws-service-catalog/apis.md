---
name: AWS Service Catalog
x-slug: aws-service-catalog
description: AWS Service Catalog allows organizations to create and manage catalogs
  of IT services that are approved for use on AWS. These IT services can include everything
  from virtual machine images, servers, software, and databases to complete multi-tier
  application architectures. AWS Service Catalog allows you to centrally manage commonly
  deployed IT services, and helps you achieve consistent governance and meet your
  compliance requirements, while enabling users to quickly deploy only the approved
  IT services they need.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Paths
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/paths/master/_listings/aws-service-catalog/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Service Catalog API List Launch Paths
  x-api-slug: aws-service-catalog-api
  description: Returns a paginated list of all paths to a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ListLaunchPaths
  tags: Launch Paths
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/paths/master/_listings/aws-service-catalog/actionlistlaunchpaths-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/paths/master/_listings/aws-service-catalog/actionlistlaunchpaths-get-openapi.md
- name: AWS Service Catalog API
  x-api-slug: aws-service-catalog-api
  description: AWS Service Catalog allows organizations to create and manage catalogs
    of IT services that are approved for use on AWS. These IT services can include
    everything from virtual machine images, servers, software, and databases to complete
    multi-tier application architectures. AWS Service Catalog allows you to centrally
    manage commonly deployed IT services, and helps you achieve consistent governance
    and meet your compliance requirements, while enabling users to quickly deploy
    only the approved IT services they need.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: :///
  tags: Paths
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/paths/master/_listings/aws-service-catalog/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/servicecatalog/latest/dg/service-catalog-api-overview.html
- type: x-faq
  url: https://aws.amazon.com/servicecatalog/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/servicecatalog/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/servicecatalog/pricing/
- type: x-website
  url: https://aws.amazon.com/servicecatalog/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---