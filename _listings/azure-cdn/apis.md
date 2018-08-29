---
name: Azure CDN
x-slug: azure-cdn
description: Ensuring a consistent user experience is important. If your websites
  or mobile apps involve streaming media, gaming software, firmware updates (Smart
  TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content Delivery
  Network helps you reduce load times, save bandwidth, and increase responsiveness.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure CDN
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/apis.md
specificationVersion: "0.14"
apis:
- name: CdnManagementClient - Profiles List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get
  description: Lists all of the CDN profiles within an Azure subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get-openapi.md
- name: CdnManagementClient - Profiles List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get
  description: Lists all of the CDN profiles within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get-openapi.md
- name: CdnManagementClient - Profiles Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get
  description: Gets a CDN profile with the specified profile name under the specified
    subscription and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get-openapi.md
- name: CdnManagementClient - Profiles Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-put
  description: Creates a new CDN profile with a profile name under the specified subscription
    and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-put-openapi.md
- name: CdnManagementClient - Profiles Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-patch
  description: Updates an existing CDN profile with the specified profile name under
    the specified subscription and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-patch-openapi.md
- name: CdnManagementClient - Profiles Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete
  description: Deletes an existing CDN profile with the specified parameters. Deleting
    a profile will result in the deletion of all of the sub-resources including endpoints,
    origins and custom domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete-openapi.md
- name: CdnManagementClient - Profiles Generate Sso Uri
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post
  description: Generates a dynamic SSO URI used to sign in to the CDN supplemental
    portal. Supplemnetal portal is used to configure advanced feature capabilities
    that are not yet available in the Azure portal, such as core reports in a standard
    profile; rules engine, advanced HTTP reports, and real-time stats and alerts in
    a premium profile. The SSO URI changes approximately every 10 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post-openapi.md
- name: CdnManagementClient - Profiles List Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post
  description: Checks the quota and actual usage of endpoints under the given CDN
    profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post-openapi.md
- name: CdnManagementClient - Endpoints List By Profile
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
  description: Lists existing CDN endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-openapi.md
- name: CdnManagementClient - Endpoints Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
  description: Gets an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-openapi.md
- name: CdnManagementClient - Endpoints Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
  description: Creates a new CDN endpoint with the specified endpoint name under the
    specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put-openapi.md
- name: CdnManagementClient - Endpoints Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch-openapi.md
- name: CdnManagementClient - Endpoints Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete
  description: Deletes an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-openapi.md
- name: CdnManagementClient - Endpoints Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post
  description: Starts an existing CDN endpoint that is on a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-openapi.md
- name: CdnManagementClient - Endpoints Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post
  description: Stops an existing running CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-openapi.md
- name: CdnManagementClient - Endpoints Purge Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post
  description: Removes a content from CDN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post-openapi.md
- name: CdnManagementClient - Endpoints Load Content
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post
  description: Pre-loads a content to CDN. Available for Verizon Profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post-openapi.md
- name: CdnManagementClient - Endpoints Validate Custom Domain
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamevalidatecustomdomain-post
  description: Validates the custom domain mapping to ensure it maps to the correct
    CDN endpoint in DNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamevalidatecustomdomain-post-openapi.md
- name: CdnManagementClient - Endpoints List Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post
  description: Checks the quota and usage of geo filters and custom domains under
    the given endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-openapi.md
- name: CdnManagementClient - Origins List By Endpoint
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get
  description: Lists all of the existing origins within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-openapi.md
- name: CdnManagementClient - Origins Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-get
  description: Gets an existing origin within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-get-openapi.md
- name: CdnManagementClient - Origins Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-patch
  description: Updates an existing origin within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-patch-openapi.md
- name: CdnManagementClient - Custom Domains List By Endpoint
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get
  description: Lists all of the existing custom domains within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-openapi.md
- name: CdnManagementClient - Custom Domains Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get
  description: Gets an exisitng custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-openapi.md
- name: CdnManagementClient - Custom Domains Create
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-put
  description: Creates a new custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-put-openapi.md
- name: CdnManagementClient - Custom Domains Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete
  description: Deletes an existing custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-openapi.md
- name: CdnManagementClient - Custom Domains Disable Custom Https
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post
  description: Disable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-openapi.md
- name: CdnManagementClient - Custom Domains Enable Custom Https
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post
  description: Enable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-openapi.md
- name: CdnManagementClient - Check Name Availability
  x-api-slug: providersmicrosoft-cdnchecknameavailability-post
  description: Check the availability of a resource name. This is needed for resources
    where name is globally unique, such as a CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnchecknameavailability-post-openapi.md
- name: CdnManagementClient - List Resource Usage
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-cdncheckresourceusage-post
  description: Check the quota and actual usage of the CDN profiles under the given
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdncheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdncheckresourceusage-post-openapi.md
- name: CdnManagementClient - List Operations
  x-api-slug: providersmicrosoft-cdnoperations-get
  description: Lists all of the available CDN REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnoperations-get-openapi.md
- name: CdnManagementClient - Edge Nodes List
  x-api-slug: providersmicrosoft-cdnedgenodes-get
  description: Lists all the edge nodes of a CDN service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Microsoft, CDN, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnedgenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnedgenodes-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.blockchain.workbench.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.cdn.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---