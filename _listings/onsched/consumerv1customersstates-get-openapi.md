---
swagger: "2.0"
x-collection-name: OnSched
x-complete: 0
info:
  title: OnSched Returns a list of state objects
  description: "Returns a list of states with the associated state code and country.
    \r\n\r\nContact us if states for your countries of operation are not currently
    loaded."
  termsOfService: None
  contact:
    name: OnSched.com
    url: https://onsched.com
    email: info@onsched.com
  version: 1.0.0
host: api.onsched.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /consumer/v1/customers/states:
    get:
      summary: Returns a list of state objects
      description: "Returns a list of states with the associated state code and country.
        \r\n\r\nContact us if states for your countries of operation are not currently
        loaded."
      operationId: ConsumerV1CustomersStatesGet
      x-api-path-slug: consumerv1customersstates-get
      parameters:
      - in: query
        name: country
      responses:
        200:
          description: OK
      tags:
      - Customers
      - States
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