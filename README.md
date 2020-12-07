# Cloudash

A monitoring and troubleshooting app for serverless architectures. Cloudash is a desktop app that allows you quickly access logs and metrics of your Lambda functions (and other services soon!). Think of it as a desktop app for AWS, tailored for the serverless use case.

## [Download v0.1](https://github.com/cloudashdev/app/releases/download/0.1.0/Cloudash-0.1.0-mac.zip)

_The current version (0.1) is free and will work for the next 3 months. Version 1.0 and above will probably be paid._

_Cloudash use AWS SDK to get metrics data. Be warned that [AWS charges for those API calls.](https://aws.amazon.com/cloudwatch/pricing/)_

![Cloudash - overview screen](./images/overview.jpg)

## Features

- Overview screen - the most important metrics for your app
  - number of deployments
  - invocations
  - error rate
  - duration (P95)
  - errors
- Function screen:
  - the most important metrics for your Lambda function (invocations, duration (P95), and errors)
  - logs grouped by invocations
  - logs search
- Support for Serverless Framework and AWS CDK

![Cloudash - function screen](./images/function-screen.jpg)
