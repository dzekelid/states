swagger: "2.0"
x-collection-name: OnSched
x-complete: 1
info:
  title: OnSched API
  description: build-secure-and-scalable-custom-apps-for-online-booking--our-flexible-api-provides-many-options-for-availability-and-booking--take-the-api-for-a-test-drive--just-click-on-the-authorize-button-above-and-authenticate---you-can-access-our-demo-company-profile-if-you-are-not-a-customer-or-your-own-profile-by-using-your-assigned-clientid-and-secret---------------------
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