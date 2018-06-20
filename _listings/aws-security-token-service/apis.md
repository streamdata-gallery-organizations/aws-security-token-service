---
name: AWS Security Token Service
x-slug: aws-security-token-service
description: The AWS Security Token Service (STS) is a web service that enables you
  to request temporary, limited-privilege credentials for AWS Identity and Access
  Management (IAM) users or for users that you authenticate (federated users).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Security Token Service
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Security Token Service API Assume Role
  x-api-slug: aws-security-token-service-api
  description: |-
    Returns a set of temporary security credentials (consisting of an access key ID, a
          secret access key, and a security token) that you can use to access AWS resources that you
          might not normally have access to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=AssumeRole
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actionassumerole-get-openapi.md
- name: AWS Security Token Service API Assume Role With S A M L
  x-api-slug: aws-security-token-service-api
  description: |-
    Returns a set of temporary security credentials for users who have been authenticated
          via a SAML authentication response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=AssumeRoleWithSAML
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actionassumerolewithsaml-get-openapi.md
- name: AWS Security Token Service API Assume Role With Web Identity
  x-api-slug: aws-security-token-service-api
  description: |-
    Returns a set of temporary security credentials for users who have been authenticated
          in a mobile or web application with a web identity provider, such as Amazon Cognito, Login with Amazon,
          Facebook, Google, or any OpenID Connect-compatible identity provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=AssumeRoleWithWebIdentity
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actionassumerolewithwebidentity-get-openapi.md
- name: AWS Security Token Service API Decode Authorization Message
  x-api-slug: aws-security-token-service-api
  description: |-
    Decodes additional information about the authorization status of a request from an
          encoded message returned in response to an AWS request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=DecodeAuthorizationMessage
  tags: Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiondecodeauthorizationmessage-get-openapi.md
- name: AWS Security Token Service API Get Caller Identity
  x-api-slug: aws-security-token-service-api
  description: |-
    Returns details about the IAM identity whose credentials are used to call the
          API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=GetCallerIdentity
  tags: Identity
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetcalleridentity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetcalleridentity-get-openapi.md
- name: AWS Security Token Service API Get Federation Token
  x-api-slug: aws-security-token-service-api
  description: |-
    Returns a set of temporary security credentials (consisting of an access key ID, a
          secret access key, and a security token) for a federated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=GetFederationToken
  tags: 'Federation Token '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetfederationtoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetfederationtoken-get-openapi.md
- name: AWS Security Token Service API Get Session Token
  x-api-slug: aws-security-token-service-api
  description: Returns a set of temporary credentials for an AWS account or IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: ://///?Action=GetSessionToken
  tags: 'Session Token '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetsessiontoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/actiongetsessiontoken-get-openapi.md
- name: AWS Security Token Service API
  x-api-slug: aws-security-token-service-api
  description: The AWS Security Token Service (STS) is a web service that enables
    you to request temporary, limited-privilege credentials for AWS Identity and Access
    Management (IAM) users or for users that you authenticate (federated users).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM_AWSSTS.png
  humanURL: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
  baseURL: :///
  tags: AWS Security Token Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-security-token-service/master/_listings/aws-security-token-service/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/STS/latest/APIReference/
- type: x-errors
  url: http://docs.aws.amazon.com/STS/latest/APIReference/CommonErrors.html
- type: x-website
  url: http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---