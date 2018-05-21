---
swagger: "2.0"
x-collection-name: Google Cloud Billing
x-complete: 0
info:
  title: Google Cloud Billing API Get Billing Accounts
  description: |-
    Lists the billing accounts that the current authenticated user
    [owns](https://support.google.com/cloud/answer/4430947).
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudbilling.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/billingAccounts:
    get:
      summary: Get Billing Accounts
      description: |-
        Lists the billing accounts that the current authenticated user
        [owns](https://support.google.com/cloud/answer/4430947).
      operationId: cloudbilling.billingAccounts.list
      x-api-path-slug: v1billingaccounts-get
      parameters:
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results to return
      responses:
        200:
          description: OK
      tags:
      - Account
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---