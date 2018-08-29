{
  "info": {
    "name": "Azure CDN API Endpoints Stop",
    "_postman_id": "a000c44f-1e42-4c7d-807d-72c3f94e2905",
    "description": "Stops an existing running CDN endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "5133f3be-a3e0-420d-87db-e5fff2f068ae",
          "name": "Endpoints_Stop",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/stop"
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
            "description": "Stops an existing running CDN endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28a1a2e7-43a2-4296-96c2-5ff30c45e89b"
            }
          ]
        }
      ]
    }
  ]
}