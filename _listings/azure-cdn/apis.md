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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/apis.md
specificationVersion: "0.14"
apis:
- name: Azure CDN API Profiles List
  x-api-slug: azure-cdn-api
  description: Lists all of the CDN profiles within an Azure subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Cdn/profiles
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get-openapi.md
- name: Azure CDN API Profiles List By Resource Group
  x-api-slug: azure-cdn-api
  description: Lists all of the CDN profiles within a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get-openapi.md
- name: Azure CDN API Profiles Get
  x-api-slug: azure-cdn-api
  description: Gets a CDN profile with the specified profile name under the specified
    subscription and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get-openapi.md
- name: Azure CDN API Profiles Create
  x-api-slug: azure-cdn-api
  description: Creates a new CDN profile with a profile name under the specified subscription
    and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}
  tags: CDN,Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-put-openapi.md
- name: Azure CDN API Profiles Update
  x-api-slug: azure-cdn-api
  description: Updates an existing CDN profile with the specified profile name under
    the specified subscription and resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}
  tags: CDN,Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-patch-openapi.md
- name: Azure CDN API Profiles Delete
  x-api-slug: azure-cdn-api
  description: Deletes an existing CDN profile with the specified parameters. Deleting
    a profile will result in the deletion of all of the sub-resources including endpoints,
    origins and custom domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete-openapi.md
- name: Azure CDN API Profiles Generate Sso Uri
  x-api-slug: azure-cdn-api
  description: Generates a dynamic SSO URI used to sign in to the CDN supplemental
    portal. Supplemnetal portal is used to configure advanced feature capabilities
    that are not yet available in the Azure portal, such as core reports in a standard
    profile; rules engine, advanced HTTP reports, and real-time stats and alerts in
    a premium profile. The SSO URI changes approximately every 10 minutes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/generateSsoUri
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post-openapi.md
- name: Azure CDN API Profiles List Resource Usage
  x-api-slug: azure-cdn-api
  description: Checks the quota and actual usage of endpoints under the given CDN
    profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/checkResourceUsage
  tags: CDN,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post-openapi.md
- name: Azure CDN API Endpoints List By Profile
  x-api-slug: azure-cdn-api
  description: Lists existing CDN endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get-openapi.md
- name: Azure CDN API Endpoints Get
  x-api-slug: azure-cdn-api
  description: Gets an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get-openapi.md
- name: Azure CDN API Endpoints Create
  x-api-slug: azure-cdn-api
  description: Creates a new CDN endpoint with the specified endpoint name under the
    specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  tags: CDN,Endpoint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put-openapi.md
- name: Azure CDN API Endpoints Update
  x-api-slug: azure-cdn-api
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  tags: CDN,Endpoint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch-openapi.md
- name: Azure CDN API Endpoints Delete
  x-api-slug: azure-cdn-api
  description: Deletes an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-delete-openapi.md
- name: Azure CDN API Endpoints Start
  x-api-slug: azure-cdn-api
  description: Starts an existing CDN endpoint that is on a stopped state.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/start
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestart-post-openapi.md
- name: Azure CDN API Endpoints Stop
  x-api-slug: azure-cdn-api
  description: Stops an existing running CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/stop
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamestop-post-openapi.md
- name: Azure CDN API Endpoints Purge Content
  x-api-slug: azure-cdn-api
  description: Removes a content from CDN.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/purge
  tags: CDN,Endpoint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamepurge-post-openapi.md
- name: Azure CDN API Endpoints Load Content
  x-api-slug: azure-cdn-api
  description: Pre-loads a content to CDN. Available for Verizon Profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/load
  tags: CDN,Endpoint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameload-post-openapi.md
- name: Azure CDN API Endpoints Validate Custom Domain
  x-api-slug: azure-cdn-api
  description: Validates the custom domain mapping to ensure it maps to the correct
    CDN endpoint in DNS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/validateCustomDomain
  tags: CDN,Endpointv
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamevalidatecustomdomain-post-openapi.md
- name: Azure CDN API Endpoints List Resource Usage
  x-api-slug: azure-cdn-api
  description: Checks the quota and usage of geo filters and custom domains under
    the given endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/checkResourceUsage
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecheckresourceusage-post-openapi.md
- name: Azure CDN API Origins List By Endpoint
  x-api-slug: azure-cdn-api
  description: Lists all of the existing origins within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/origins
  tags: CDN,Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameorigins-get-openapi.md
- name: Azure CDN API Origins Get
  x-api-slug: azure-cdn-api
  description: Gets an existing origin within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/origins/{originName}
  tags: CDN,Orgins
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-get-openapi.md
- name: Azure CDN API Origins Update
  x-api-slug: azure-cdn-api
  description: Updates an existing origin within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/origins/{originName}
  tags: CDN,Orgins
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnameoriginsoriginname-patch-openapi.md
- name: Azure CDN API Custom Domains List By Endpoint
  x-api-slug: azure-cdn-api
  description: Lists all of the existing custom domains within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-openapi.md
- name: Azure CDN API Custom Domains Get
  x-api-slug: azure-cdn-api
  description: Gets an exisitng custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-openapi.md
- name: Azure CDN API Custom Domains Create
  x-api-slug: azure-cdn-api
  description: Creates a new custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-put-openapi.md
- name: Azure CDN API Custom Domains Delete
  x-api-slug: azure-cdn-api
  description: Deletes an existing custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-openapi.md
- name: Azure CDN API Custom Domains Disable Custom Https
  x-api-slug: azure-cdn-api
  description: Disable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/disableCustomHttps
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-openapi.md
- name: Azure CDN API Custom Domains Enable Custom Https
  x-api-slug: azure-cdn-api
  description: Enable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/enableCustomHttps
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-openapi.md
- name: Azure CDN API Check Name Availability
  x-api-slug: azure-cdn-api
  description: Check the availability of a resource name. This is needed for resources
    where name is globally unique, such as a CDN endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////providers/Microsoft.Cdn/checkNameAvailability
  tags: CDN,Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnchecknameavailability-post-openapi.md
- name: Azure CDN API List Resource Usage
  x-api-slug: azure-cdn-api
  description: Check the quota and actual usage of the CDN profiles under the given
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Cdn/checkResourceUsage
  tags: CDN,Resource Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdncheckresourceusage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/subscriptionssubscriptionidprovidersmicrosoft-cdncheckresourceusage-post-openapi.md
- name: Azure CDN API List Operations
  x-api-slug: azure-cdn-api
  description: Lists all of the available CDN REST API operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////providers/Microsoft.Cdn/operations
  tags: CDN,Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnoperations-get-openapi.md
- name: Azure CDN API Edge Nodes List
  x-api-slug: azure-cdn-api
  description: Lists all the edge nodes of a CDN service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////providers/Microsoft.Cdn/edgenodes
  tags: CDN,Edge Node
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnedgenodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/providersmicrosoft-cdnedgenodes-get-openapi.md
- name: Azure CDN API
  x-api-slug: azure-cdn-api
  description: Ensuring a consistent user experience is important. If your websites
    or mobile apps involve streaming media, gaming software, firmware updates (Smart
    TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content
    Delivery Network helps you reduce load times, save bandwidth, and increase responsiveness.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Azure CDN
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-cdn/master/_listings/azure-cdn/openapi.md
x-common:
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