# serverless-saga-pattern


https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/implement-the-serverless-saga-pattern-by-using-aws-step-functions.html

https://aws.amazon.com/es/blogs/compute/building-a-serverless-distributed-application-using-a-saga-orchestration-pattern/


# Welcome to Saga Serverless with Step Functions!

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkServerlessSagaStack`)
which contains an AWS Step Functions, Amazon API Gateway ,AWS Lambda, Amazon DynamoDB and Amazon SNS Topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template
