{
  "info": {
    "name": "Capital One DevExchange Delete a specific existing bill",
    "_postman_id": "fe5cce93-692a-476c-8e2d-4452dd3cc48a",
    "description": "Deletes the specific bill",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "602dd897-56ff-4d6e-93b9-ec0685ac4013",
          "name": "deletes-the-specific-bill",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specific bill"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "459e8547-d703-4844-bd31-887835d65f62"
            }
          ]
        }
      ]
    }
  ]
}