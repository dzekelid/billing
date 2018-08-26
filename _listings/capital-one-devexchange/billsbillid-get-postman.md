{
  "info": {
    "name": "Capital One DevExchange Get bill by id",
    "_postman_id": "4e088c7f-54cf-44ea-8bc7-8c8d37313668",
    "description": "Returns the bill with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "6a3ae8ad-6dc2-4b92-a28c-4558a1d9d29b",
          "name": "returns-the-bill-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "bills/:billId"
              ],
              "variable": [
                {
                  "id": "billId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the bill with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92e86905-bde3-42a0-8af6-c1dbb53e217f"
            }
          ]
        }
      ]
    }
  ]
}