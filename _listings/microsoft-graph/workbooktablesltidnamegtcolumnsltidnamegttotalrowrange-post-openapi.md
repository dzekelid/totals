---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Column Total Row Range
  description: 'TableColumn: TotalRowRange Gets the range object associated with the
    totals row of the column.'
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