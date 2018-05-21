{
  "info": {
    "name": "Azure CDN API Endpoints Delete",
    "_postman_id": "347a1241-f564-4c66-be28-fcd8d37ab98f",
    "description": "Deletes an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "bbeacd7b-4568-427d-b80d-af8a1cc6f867",
          "name": "Endpoints_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an existing CDN endpoint with the specified endpoint name under the specified subscription, resource group and profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "632be924-b55e-4653-8e0f-e6a856dbc940"
            }
          ]
        }
      ]
    }
  ]
}