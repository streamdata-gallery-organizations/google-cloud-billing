{
  "info": {
    "name": "Google Cloud Billing API Get Billing Information",
    "_postman_id": "b1b3d4a3-7bc0-4ef2-b6b2-a5f13fac05c0",
    "description": "Gets the billing information for a project. The current authenticated user\nmust have [permission to view the\nproject](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo\n).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "billing",
      "item": [
        {
          "id": "893e5f99-124e-450f-afdf-1dfd469cc2bc",
          "name": "cloudbilling.projects.getBillingInfo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "cloudbilling.googleapis.com",
              "path": [
                "v1/:name/billingInfo"
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
            "description": "Gets the billing information for a project"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "156ad4a6-c237-4119-850d-92ce6a4b290e"
            }
          ]
        }
      ]
    }
  ]
}