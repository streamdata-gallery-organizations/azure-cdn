---
swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 0
info:
  title: Azure CDN API Profiles Update
  description: Updates an existing CDN profile with the specified profile name under
    the specified subscription and resource group.
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftcdnprofiles-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcdnprofiles-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcdnprofilesprofilename-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcdnprofilesprofilename-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftcdnprofilesprofilename-patch
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