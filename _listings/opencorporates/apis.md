---
name: OpenCorporates
x-slug: opencorporates
description: OpenCorporates is a website which shares data on corporate entities as
  open data under the share-alike attribution Open Database License. It was created
  by Chris Taggart and Rob McKinnon, under the auspices of their company, Chrinon
  Ltd, and launched on 20 December 2010. It has the aims of creating a URL with such
  data for every corporate entity in the world, importing government data relating
  to companies and matching it to specific companies. The site also shows groups of
  companies which are legally part of the same conglomerate. Basic company information
  is available as open data in XML or JSON format.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: OpenCorporates
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/apis.md
specificationVersion: "0.14"
apis:
- name: OpenCorporates Account Status
  x-api-slug: opencorporates
  description: nThis returns the status of your API Account (this information may
    also be retrieved at https://OpenCorporates
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///account_status
  tags: Businesses,Account,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/account-status-get-openapi.md
- name: OpenCorporates Companies  Jurisdiction Code  Company Number Data
  x-api-slug: opencorporates
  description: nThis returns the data held for the given company
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///companies/:jurisdiction_code/:company_number/data
  tags: Businesses,Companies,:jurisdiction,Code,:company,Number,Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/companiesjurisdiction-codecompany-numberdata-get-openapi.md
- name: OpenCorporates Companies  Jurisdiction Code  Company Number Network
  x-api-slug: opencorporates
  description: nThis returns the immediate &#39;computed corporate network&#39; for
    the given company as a set of control relationships (i
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///companies/:jurisdiction_code/:company_number/network
  tags: Businesses,Companies,:jurisdiction,Code,:company,Number,Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/companiesjurisdiction-codecompany-numbernetwork-get-openapi.md
- name: OpenCorporates Companies Search
  x-api-slug: opencorporates
  description: nThis returns a collection of companies whose name matches the given
    search term (submitted as :q in the query parameters)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///companies/search
  tags: Businesses,Companies,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/companiessearch-get-openapi.md
- name: OpenCorporates Corporate Groupings Search
  x-api-slug: opencorporates
  description: nThis returns a collection of corporate_groupings whose name matches
    the given search term (submitted as :q in the query parameters)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///corporate_groupings/search
  tags: Businesses,Corporate,Groupings,Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/corporate-groupingssearch-get-openapi.md
- name: OpenCorporates Data  ID
  x-api-slug: opencorporates
  description: nThis returns information on a given datum
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///data/:id
  tags: Businesses,Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/dataid-get-openapi.md
- name: OpenCorporates Industry Codes  Code Scheme ID
  x-api-slug: opencorporates
  description: nThis call returns further details about the code_scheme, together
    with the list of industry codes associated with it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///industry_codes/:code_scheme_id
  tags: Businesses,Industry,Codes,:code,Scheme,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/industry-codescode-scheme-id-get-openapi.md
- name: OpenCorporates Jurisdictions Match
  x-api-slug: opencorporates
  description: nThis matches the name of a jurisdiction to the jurisdiction
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///jurisdictions/match
  tags: Businesses,Jurisdictions,Match
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/jurisdictionsmatch-get-openapi.md
- name: OpenCorporates Officers  ID
  x-api-slug: opencorporates
  description: nThis returns information on a particular officer (a director or an
    agent for a company)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///officers/:id
  tags: Businesses,Officers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/officersid-get-openapi.md
- name: OpenCorporates Placeholder  ID
  x-api-slug: opencorporates
  description: nA placeholder is we call something we believe is probably a company
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///placeholder/:id
  tags: Businesses,Placeholder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/placeholderid-get-openapi.md
- name: OpenCorporates Placeholders  ID Statements
  x-api-slug: opencorporates
  description: nThis returns the statements associated with a given placeholder
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///placeholders/:id/statements
  tags: Businesses,Placeholders,Statements
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/placeholdersidstatements-get-openapi.md
- name: OpenCorporates Versions
  x-api-slug: opencorporates
  description: nThis returns the current version of the API and supported versions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4///versions
  tags: Businesses,Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/versions-get-openapi.md
- name: OpenCorporates
  x-api-slug: opencorporates
  description: OpenCorporates is a database of corporate data. OpenCorporates offers
    users the ability to search for information on 30 million corporations from around
    the world. Users can also search by type of corporation. The OpenCorporates API
    allows developers to access and integrate the data and functionality of OpenCorporates
    with other applications. Some example API methods include searching and retrieving
    information on corporation by type, jurisdiction, and company ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/OpenCorporates.jpg
  humanURL: https://opencorporates.com/
  baseURL: ://api.opencorporates.com/v0.4/
  tags: OpenCorporates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/opencorporates/master/_listings/opencorporates/openapi.md
x-common:
- type: x-base
  url: https://api.opencorporates.com/
- type: x-blog
  url: http://blog.opencorporates.com/
- type: x-blog-rss
  url: http://blog.opencorporates.com/feed/
- type: x-developer
  url: http://api.opencorporates.com/
- type: x-github
  url: https://github.com/openc
- type: x-pricing
  url: https://opencorporates.com/info/pricing
- type: x-status
  url: http://status.opencorporates.com/
- type: x-terms-of-service
  url: https://opencorporates.com/info/licence
- type: x-twitter
  url: https://twitter.com/opencorporates
- type: x-website
  url: https://opencorporates.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---