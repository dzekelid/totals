---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get an overview of account amounts and totals
  version: 1.0.0
  description: Get an overview of account amounts and totals.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/account/payments/overview:
    get:
      summary: Get an overview of account amounts and totals
      description: Get an overview of account amounts and totals.
      operationId: Account_GetPaymentsOverview
      x-api-path-slug: apiaccountpaymentsoverview-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Overview
      - Of
      - Account
      - Amounts
      - Totals
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