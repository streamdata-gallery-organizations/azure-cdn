---
swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 0
info:
  title: Azure CDN API Endpoints Update
  description: Updates an existing CDN endpoint with the specified endpoint name under
    the specified subscription, resource group and profile. Only tags and Origin HostHeader
    can be updated after creating an endpoint. To update origins, use the Update Origin
    operation. To update custom domains, use the Update Custom Domain operation.
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
  /subscriptions/{subscriptionId}/providers/Microsoft.Cdn/profiles:
    get:
      summary: Profiles List
      description: Lists all of the CDN profiles within an Azure subscription.
      operationId: Profiles_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-cdnprofiles-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles:
    get:
      summary: Profiles List By Resource Group
      description: Lists all of the CDN profiles within a resource group.
      operationId: Profiles_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofiles-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}:
    get:
      summary: Profiles Get
      description: Gets a CDN profile with the specified profile name under the specified
        subscription and resource group.
      operationId: Profiles_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
    put:
      summary: Profiles Create
      description: Creates a new CDN profile with a profile name under the specified
        subscription and resource group.
      operationId: Profiles_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: profile
        description: Profile properties needed to create a new profile
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
    patch:
      summary: Profiles Update
      description: Updates an existing CDN profile with the specified profile name
        under the specified subscription and resource group.
      operationId: Profiles_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      - in: body
        name: profileUpdateParameters
        description: Profile properties needed to update an existing profile
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
    delete:
      summary: Profiles Delete
      description: Deletes an existing CDN profile with the specified parameters.
        Deleting a profile will result in the deletion of all of the sub-resources
        including endpoints, origins and custom domains.
      operationId: Profiles_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/generateSsoUri:
    post:
      summary: Profiles Generate Sso Uri
      description: Generates a dynamic SSO URI used to sign in to the CDN supplemental
        portal. Supplemnetal portal is used to configure advanced feature capabilities
        that are not yet available in the Azure portal, such as core reports in a
        standard profile; rules engine, advanced HTTP reports, and real-time stats
        and alerts in a premium profile. The SSO URI changes approximately every 10
        minutes.
      operationId: Profiles_GenerateSsoUri
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamegeneratessouri-post
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/checkResourceUsage
  : post:
      summary: Profiles List Resource Usage
      description: Checks the quota and actual usage of endpoints under the given
        CDN profile.
      operationId: Profiles_ListResourceUsage
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenamecheckresourceusage-post
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Profile
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints:
    get:
      summary: Endpoints List By Profile
      description: Lists existing CDN endpoints.
      operationId: Endpoints_ListByProfile
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpoints-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}
  : get:
      summary: Endpoints Get
      description: Gets an existing CDN endpoint with the specified endpoint name
        under the specified subscription, resource group and profile.
      operationId: Endpoints_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-get
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
    put:
      summary: Endpoints Create
      description: Creates a new CDN endpoint with the specified endpoint name under
        the specified subscription, resource group and profile.
      operationId: Endpoints_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-put
      parameters:
      - in: body
        name: endpoint
        description: Endpoint properties
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
    patch:
      summary: Endpoints Update
      description: Updates an existing CDN endpoint with the specified endpoint name
        under the specified subscription, resource group and profile. Only tags and
        Origin HostHeader can be updated after creating an endpoint. To update origins,
        use the Update Origin operation. To update custom domains, use the Update
        Custom Domain operation.
      operationId: Endpoints_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointname-patch
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: body
        name: endpointUpdateProperties
        description: Endpoint update properties
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Endpoint
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---