{
  "info": {
    "name": "Azure CDN API Endpoints Get",
    "_postman_id": "e37b0422-680e-4baf-8188-c2f06b7a744d",
    "description": "Gets an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "fdc0b3ce-abd4-41ef-8460-4e6a5be1b0f2",
          "name": "Endpoints_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "endpointName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "profileName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da11963c-5f0b-45be-84aa-5f831596ba49"
            }
          ]
        }
      ]
    }
  ]
}