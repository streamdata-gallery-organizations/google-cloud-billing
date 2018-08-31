{
  "info": {
    "name": "Google Cloud Billing API Get Billing Accounts",
    "_postman_id": "0659c464-00b3-47a5-8c3c-76b22e8e49f7",
    "description": "Lists the billing accounts that the current authenticated user\n[owns](https://support.google.com/cloud/answer/4430947).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "041c3d05-3ea7-463e-8396-6248fe7b03f4",
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
              "id": "de12a0ea-f7cc-4b68-b225-caef1d6c279a"
            }
          ]
        }
      ]
    }
  ]
}