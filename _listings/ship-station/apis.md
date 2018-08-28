---
name: Ship Station
x-slug: ship-station
description: ShipStation is a web-based shipping solution that streamlines the order
  fulfillment process for your online business. ShipStation consolidates orders from
  over 70 ecommerce channels, creates shipping labels, packing slips, and pick lists
  in batch, communicates tracking information to your customers, provides endless
  automation, filters, and views, wireless printing, a mobile app, and a lot more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Stores
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/apis.md
specificationVersion: "0.14"
apis:
- name: Ship Station Developer Portal - List Stores
  x-api-slug: storesshowinactiveshowinactivemarketplaceidmarketplaceid-get
  description: Retrieve the list of installed stores on the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesshowinactiveshowinactivemarketplaceidmarketplaceid-get-openapi.md
- name: Ship Station Developer Portal - Deactivate Store
  x-api-slug: storesdeactivate-post
  description: |-
    Deactivates the specified store.

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to deactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesdeactivate-post-openapi.md
- name: Ship Station Developer Portal - Get Store Refresh Status
  x-api-slug: storesgetrefreshstatusstoreidstoreid-get
  description: Retrieves the refresh status of a given store.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesgetrefreshstatusstoreidstoreid-get-openapi.md
- name: Ship Station Developer Portal - Reactivate Store
  x-api-slug: storesreactivate-post
  description: |-
    Reactivates the specified store. Note: stores are active by default

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to reactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesreactivate-post-openapi.md
- name: Ship Station Developer Portal - Refresh Store
  x-api-slug: storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post
  description: Initiates a store refresh.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post-openapi.md
- name: Ship Station Developer Portal - Get Store
  x-api-slug: storesstoreid-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-get-openapi.md
- name: Ship Station Developer Portal - Update Store
  x-api-slug: storesstoreid-put
  description: Updates an existing store. This call does not currently support partial
    updates. The entire resource must be provided in the body of the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-put-openapi.md
- name: Ship Station Developer Portal - Deactivate Store
  x-api-slug: storesdeactivate-post
  description: |-
    Deactivates the specified store.

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to deactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesdeactivate-post-openapi.md
- name: Ship Station Developer Portal - Get Store Refresh Status
  x-api-slug: storesgetrefreshstatusstoreidstoreid-get
  description: Retrieves the refresh status of a given store.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesgetrefreshstatusstoreidstoreid-get-openapi.md
- name: Ship Station Developer Portal - Reactivate Store
  x-api-slug: storesreactivate-post
  description: |-
    Reactivates the specified store. Note: stores are active by default

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to reactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesreactivate-post-openapi.md
- name: Ship Station Developer Portal - Refresh Store
  x-api-slug: storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post
  description: Initiates a store refresh.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post-openapi.md
- name: Ship Station Developer Portal - Get Store
  x-api-slug: storesstoreid-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-get-openapi.md
- name: Ship Station Developer Portal - Update Store
  x-api-slug: storesstoreid-put
  description: Updates an existing store. This call does not currently support partial
    updates. The entire resource must be provided in the body of the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-put-openapi.md
- name: Ship Station Developer Portal - Update Store
  x-api-slug: storesstoreid-put
  description: Updates an existing store. This call does not currently support partial
    updates. The entire resource must be provided in the body of the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-put-openapi.md
- name: Ship Station Developer Portal - Get Store
  x-api-slug: storesstoreid-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesstoreid-get-openapi.md
- name: Ship Station Developer Portal - Refresh Store
  x-api-slug: storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post
  description: Initiates a store refresh.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesrefreshstorestoreidstoreidrefreshdaterefreshdate-post-openapi.md
- name: Ship Station Developer Portal - Reactivate Store
  x-api-slug: storesreactivate-post
  description: |-
    Reactivates the specified store. Note: stores are active by default

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to reactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesreactivate-post-openapi.md
- name: Ship Station Developer Portal - Get Store Refresh Status
  x-api-slug: storesgetrefreshstatusstoreidstoreid-get
  description: Retrieves the refresh status of a given store.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesgetrefreshstatusstoreidstoreid-get-openapi.md
- name: Ship Station Developer Portal - Deactivate Store
  x-api-slug: storesdeactivate-post
  description: |-
    Deactivates the specified store.

    The body of this request has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``storeId``  | number, required | ID of the store to deactivate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/stores/master/_listings/ship-station/storesdeactivate-post-openapi.md
x-common:
- type: x-website
  url: http://bit.ly/_ShipStation
- type: x-api-gallery
  url: http://server.density.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ship.station.stack.network
- type: x-blog
  url: https://www.shipstation.com/blog/
- type: x-developer
  url: https://shipstation.docs.apiary.io/#
- type: x-github
  url: https://github.com/shipstation
- type: x-partners
  url: https://www.shipstation.com/partners/
- type: x-pricing
  url: https://www.shipstation.com/pricing/
- type: x-twitter
  url: https://twitter.com/ShipStation
- type: x-website
  url: http://shipstation.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---