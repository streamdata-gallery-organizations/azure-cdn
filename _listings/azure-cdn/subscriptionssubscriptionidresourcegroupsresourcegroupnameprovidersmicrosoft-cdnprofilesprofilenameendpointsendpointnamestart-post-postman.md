{
  "info": {
    "name": "Azure CDN API Endpoints Start",
    "_postman_id": "7ab4694b-ea55-4d62-b6fa-e0554d3997f9",
    "description": "Starts an existing CDN endpoint that is on a stopped state.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "d3e3b7f5-1b31-448b-a1bb-c54b4e5f7a4a",
          "name": "Endpoints_Start",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/start"
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
            "description": "Starts an existing CDN endpoint that is on a stopped state"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00d8a7c7-4d97-42d4-b0ee-f06e1ec2b950"
            }
          ]
        }
      ]
    }
  ]
}