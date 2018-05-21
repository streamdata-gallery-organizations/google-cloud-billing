{
  "info": {
    "name": "Google Cloud Billing API Get Billing Account",
    "_postman_id": "dab81e8f-0544-47c3-b782-f26f07ff3a32",
    "description": "Gets information about a billing account. The current authenticated user\nmust be an [owner of the billing\naccount](https://support.google.com/cloud/answer/4430947).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "ab63d85f-c50c-4e38-ad55-8b0f8dba11f4",
          "name": "cloudbilling.billingAccounts.list",
          "request": {
            "url": "http://cloudbilling.googleapis.com/v1/billingAccounts?pageSize=%7B%7D&pageToken=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the billing accounts that the current authenticated user\n[owns](https://support.google.com/cloud/answer/4430947)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44278083-ac07-419a-8883-b4826ce084a1"
            }
          ]
        },
        {
          "id": "c6149879-fedc-46df-aee8-e166e286237b",
          "name": "cloudbilling.billingAccounts.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "cloudbilling.googleapis.com",
              "path": [
                "v1/:name"
              ],
              "variable": [
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a billing account. The current authenticated user\nmust be an [owner of the billing\naccount](https://support.google.com/cloud/answer/4430947)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4048b96c-a8ff-43ec-b34a-eb85b3b5b59d"
            }
          ]
        }
      ]
    }
  ]
}