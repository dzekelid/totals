---
swagger: "2.0"
x-collection-name: Neblio
x-complete: 1
info:
  title: Neblio REST API Suite
  description: apis-for-interacting-with-ntp1-tokens--the-neblio-blockchain
  version: 1.0.0
host: ntp1node.nebl.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ins/addr/{address}/totalReceived:
    get:
      summary: Returns total received by address in sats
      description: Returns total NEBL received by address in satoshis
      operationId: getAddressTotalReceived
      x-api-path-slug: insaddraddresstotalreceived-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Total
      - Received
      - By
      - Address
      - In
      - Sats
  /ins/addr/{address}/totalSent:
    get:
      summary: Returns total sent by address in sats
      description: Returns total NEBL sent by address in satoshis
      operationId: getAddressTotalSent
      x-api-path-slug: insaddraddresstotalsent-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Total
      - Sent
      - By
      - Address
      - In
      - Sats
  /testnet/ins/addr/{address}/totalReceived:
    get:
      summary: Returns total received by address in sats
      description: Returns total NEBL received by address in satoshis
      operationId: testnet_getAddressTotalReceived
      x-api-path-slug: testnetinsaddraddresstotalreceived-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Total
      - Received
      - By
      - Address
      - In
      - Sats
  /testnet/ins/addr/{address}/totalSent:
    get:
      summary: Returns total sent by address in sats
      description: Returns total NEBL sent by address in satoshis
      operationId: testnet_getAddressTotalSent
      x-api-path-slug: testnetinsaddraddresstotalsent-get
      parameters:
      - in: path
        name: address
        description: Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Returns
      - Total
      - Sent
      - By
      - Address
      - In
      - Sats
---