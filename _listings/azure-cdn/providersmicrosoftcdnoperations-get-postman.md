{
  "info": {
    "name": "Azure CDN API List Operations",
    "_postman_id": "88d654d0-f678-4e74-8f1b-1815c407d6d1",
    "description": "Lists all of the available CDN REST API operations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "11a30d61-f0bd-4a88-84f1-bb1ded48a8f3",
          "name": "ListOperations",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.Cdn/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available CDN REST API operations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7879df23-d202-4bf8-af5b-8ddd48cb3f1d"
            }
          ]
        }
      ]
    }
  ]
}