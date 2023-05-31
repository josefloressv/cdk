# Welcome to your CDK TypeScript project
https://catalog.us-east-1.prod.workshops.aws/workshops/c15012ac-d05d-46b1-8a4a-205e7c9d93c9/en-US/30-cdk\
https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

* `npm install -g aws-cdk` Install the AWS CDK
* `npm run build`   compile typescript to js
* `npm run watch`   watch for changes and compile
* `npm run test`    perform the jest unit tests
* `cdk bootstrap`   bootstraping
* `cdk deploy`      deploy this stack to your default AWS account/region
* `cdk diff`        compare deployed stack with current state
* `cdk synth`       emits the synthesized CloudFormation template
* `cdk destroy`     destroy the stack

more commands: https://docs.aws.amazon.com/cdk/v2/guide/cli.html