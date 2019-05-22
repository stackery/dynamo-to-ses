# DynamoDB to SES Tutorial

This is the repository for the [DynamoDB to SES Tutorial](https://docs.stackery.io/docs/tutorials/dynamodb-to-ses/) from Stackery.

This tutorial will show you how to populate a DynamoDB Table with links to images, then randomly select one of those images to send in a daily email.

## Deploy this to your AWS account

You can deploy this application to your own AWS account using the following two Stackery CLI commands:

`stackery create` will initialize a new repo in your GitHub account, initializing it with the contents of the referenced template repository.

```
stackery create --stack-name 'dynamodb-to-ses' \
--git-provider 'github' \
--template-git-url 'https://github.com/stackery/dynamo-to-ses'
```

`stackery deploy` will deploy the newly created stack into your AWS account.

```
stackery deploy --stack-name 'dynamodb-to-ses' \
--env-name 'development' \
--git-ref 'master'
```
