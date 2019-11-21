# AWS CLI tools

Useful tools to simplify life with AWS.

## Prerequisites

Have a *ix bash and some configured AWS environments.

## Export AWS environment

It's sometimes useful to export the AWS profile environment
as their corresponding environment variables.

`exportAwsEnvironment.sh` lets the user select one of the existing
AWS profiles found in `~/.aws/credentials` and exports these variables.
