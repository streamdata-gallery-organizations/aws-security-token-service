---
swagger: "2.0"
info:
  title: AWS Security Token Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssumeRoleWithSAML:
    get:
      summary: ' Assume Role With S A M L '
      description: |-
        Returns a set of temporary security credentials for users who have been authenticated
              via a SAML authentication response
      operationId: assumeRoleWithSAML
      parameters:
      - in: query
        name: DurationSeconds
        description: The duration, in seconds, of the role session
        type: string
      - in: query
        name: Policy
        description: An IAM policy in JSON format
        type: string
      - in: query
        name: PrincipalArn
        description: The Amazon Resource Name (ARN) of the SAML provider in IAM that
          describes the      IdP
        type: string
      - in: query
        name: RoleArn
        description: The Amazon Resource Name (ARN) of the role that the caller is
          assuming
        type: string
      - in: query
        name: SAMLAssertion
        description: The base-64 encoded SAML authentication response provided by
          the IdP
        type: string
      responses:
        200:
          description: OK
      tags:
      - roles
definitions: []
x-collection-name: AWS Security Token Service
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