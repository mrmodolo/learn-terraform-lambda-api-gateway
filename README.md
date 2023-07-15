# Learn Terraform - Lambda functions and API Gateway

AWS Lambda functions and API gateway are often used to create serverless
applications.

This repo is a companion repo to the [AWS Lambda functions and API gateway](https://developer.hashicorp.com/terraform/tutorials/aws/lambda-api-gateway) tutorial.

## Test

[How to urlencode data for curl command?](https://stackoverflow.com/questions/296536/how-to-urlencode-data-for-curl-command)

[Encode to URL-encoded format](https://www.urlencoder.org/)

curl -w "\n" --get "$(tf output --raw base_url)/hello" --data-urlencode "Name=Módolo"


