---
name: Google Cloud Billing
x-slug: google-cloud-billing
description: The Google Cloud Billing API provides methods that you can use to programmatically
  manage billing for your projects in the Google Cloud Platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Billing
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Billing - Get Billing Accounts
  x-api-slug: v1billingaccounts-get
  description: |-
    Lists the billing accounts that the current authenticated user
    [owns](https://support.google.com/cloud/answer/4430947).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1billingaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1billingaccounts-get-openapi.md
- name: Google Cloud Billing - Get Billing Account
  x-api-slug: v1name-get
  description: |-
    Gets information about a billing account. The current authenticated user
    must be an [owner of the billing
    account](https://support.google.com/cloud/answer/4430947).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1name-get-openapi.md
- name: Google Cloud Billing - Get Billing Information
  x-api-slug: v1namebillinginfo-get
  description: |-
    Gets the billing information for a project. The current authenticated user
    must have [permission to view the
    project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
    ).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1namebillinginfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1namebillinginfo-get-openapi.md
- name: Google Cloud Billing - Update Billing Information
  x-api-slug: v1namebillinginfo-put
  description: |-
    Sets or updates the billing account associated with a project. You specify
    the new billing account by setting the `billing_account_name` in the
    `ProjectBillingInfo` resource to the resource name of a billing account.
    Associating a project with an open billing account enables billing on the
    project and allows charges for resource usage. If the project already had a
    billing account, this method changes the billing account used for resource
    usage charges.

    *Note:* Incurred charges that have not yet been reported in the transaction
    history of the Google Cloud Console may be billed to the new billing
    account, even if the charge occurred before the new billing account was
    assigned to the project.

    The current authenticated user must have ownership privileges for both the
    [project](https://cloud.google.com/docs/permissions-overview#h.bgs0oxofvnoo
    ) and the [billing
    account](https://support.google.com/cloud/answer/4430947).

    You can disable billing on the project by setting the
    `billing_account_name` field to empty. This action disassociates the
    current billing account from the project. Any billable activity of your
    in-use services will stop, and your application could stop functioning as
    expected. Any unbilled charges to date will be billed to the previously
    associated account. The current authenticated user must be either an owner
    of the project or an owner of the billing account for the project.

    Note that associating a project with a *closed* billing account will have
    much the same effect as disabling billing on the project: any paid
    resources used by the project will be shut down. Thus, unless you wish to
    disable billing, you should always call this method with the name of an
    *open* billing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1namebillinginfo-put-openapi.md
- name: Google Cloud Billing - Get Projects
  x-api-slug: v1nameprojects-get
  description: |-
    Lists the projects associated with a billing account. The current
    authenticated user must be an [owner of the billing
    account](https://support.google.com/cloud/answer/4430947).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Google APIs, Monetization, Stack Network, Billing, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-billing/master/_listings/google-cloud-billing/v1nameprojects-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.classroom.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.billing.stack.network
- type: x-code
  url: https://cloud.google.com/billing/v1/libraries
- type: x-errors
  url: https://cloud.google.com/billing/v1/errors/core_errors
- type: x-getting-started
  url: https://cloud.google.com/billing/v1/getting-started
- type: x-how-to-guides
  url: https://cloud.google.com/billing/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/billing/v1/pricing
- type: x-website
  url: https://cloud.google.com/billing/docs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---