# Custom-Resources-Lambda

In CloudFormation Stack we define Custom Resource and it will invoke a Lambda function anytime the CloudFormation will be created, deleted or updated. The Lambda Function will get invoked only if there is a create, update or delete events not everytime we  run the template. So it could be another service on AWS and it could be an on-premise resource, fetch an AMI id. Hence, Custom Resource is a really powerful in cloudformation.

