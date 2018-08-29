{
  "info": {
    "name": "Azure CDN API Endpoints List Resource Usage",
    "_postman_id": "e2e35b25-fa61-4e99-ba00-3e9e801ab237",
    "description": "Checks the quota and usage of geo filters and custom domains under the given endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "0137d382-936c-436f-91ef-781a4f0400a1",
          "name": "Endpoints_ListResourceUsage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/checkResourceUsage"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Checks the quota and usage of geo filters and custom domains under the given endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce0b7b9e-8b68-421a-9b0c-e76ec793cd3c"
            }
          ]
        }
      ]
    }
  ]
}