---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Real Time Options Get Equity Option Symbol
  description: Returns the symbol for an equity option based on month, year and strike
    price.
  version: 1.0.0
host: globalrealtimeoptions.xignite.com
basePath: xglobalrealtimeoptions.json/XigniteGlobalRealTimeOptions
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetAllEquityOptionChain:
    get:
      summary: Get All Equity Option Chain
      description: Returns options chains for an equity.
      operationId: GetAllEquityOptionChain
      x-api-path-slug: getallequityoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
      - Chain
  /GetEquityOptionChain:
    get:
      summary: Get Equity Option Chain
      description: Returns options chain for an equity.
      operationId: GetEquityOptionChain
      x-api-path-slug: getequityoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
      - Chain
  /GetEquityOptionBySymbols:
    get:
      summary: Get Equity Option By Symbols
      description: Returns an array of specific equity options.
      operationId: GetEquityOptionBySymbols
      x-api-path-slug: getequityoptionbysymbols-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
      - Symbols
  /GetAllExtendedEquityOptionChain:
    get:
      summary: Get All Extended Equity Option Chain
      description: Returns extended options chains for an equity.
      operationId: GetAllExtendedEquityOptionChain
      x-api-path-slug: getallextendedequityoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
      - Equity
      - Option
      - Chain
  /GetExtendedEquityOptionChain:
    get:
      summary: Get Extended Equity Option Chain
      description: Returns extended options chain for an equity.
      operationId: GetExtendedEquityOptionChain
      x-api-path-slug: getextendedequityoptionchain-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
      - Equity
      - Option
      - Chain
  /GetEquityOption:
    get:
      summary: Get Equity Option
      description: Returns a specific equity option.
      operationId: GetEquityOption
      x-api-path-slug: getequityoption-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
  /GetExtendedEquityOption:
    get:
      summary: Get Extended Equity Option
      description: Returns a specific equity extended option.
      operationId: GetExtendedEquityOption
      x-api-path-slug: getextendedequityoption-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
      - Equity
      - Option
  /GetEquityOptionSymbol:
    get:
      summary: Get Equity Option Symbol
      description: Returns the symbol for an equity option based on month, year and
        strike price.
      operationId: GetEquityOptionSymbol
      x-api-path-slug: getequityoptionsymbol-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
      - Symbol
  /GetEquityOptionBySymbol:
    get:
      summary: Get Equity Option By Symbol
      description: Returns a specific equity option.
      operationId: GetEquityOptionBySymbol
      x-api-path-slug: getequityoptionbysymbol-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Equity
      - Option
      - Symbol
  /GetExtendedEquityOptionBySymbol:
    get:
      summary: Get Extended Equity Option By Symbol
      description: Returns a specific equity extended option.
      operationId: GetExtendedEquityOptionBySymbol
      x-api-path-slug: getextendedequityoptionbysymbol-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
      - Equity
      - Option
      - Symbol
  /GetExtendedEquityOptionBySymbols:
    get:
      summary: Get Extended Equity Option By Symbols
      description: Returns an array of specific equity extended options.
      operationId: GetExtendedEquityOptionBySymbols
      x-api-path-slug: getextendedequityoptionbysymbols-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Extended
      - Equity
      - Option
      - Symbols
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