---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
---