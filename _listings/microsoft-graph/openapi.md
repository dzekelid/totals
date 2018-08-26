---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Total Row Range
      description: 'Table: TotalRowRange Gets the range object associated with totals
        row of the table.'
      operationId: Table:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Total
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
---