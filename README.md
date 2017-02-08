# Overview
This repo is a demonstration of Continuous Delivery of a single page application to S3 via CodeBuild and CodePipeline

[![Launch CFN stack](https://s3.amazonaws.com/stelligent-training-public/public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#cstack=sn~sample-s3-delivery|turl~https://s3.amazonaws.com/stelligent-templates/sample-s3-delivery/pipeline.yml)

# Development
To update the template in the Stelligent templates bucket, run:
```
aws s3 cp --acl public-read pipeline.yml s3://stelligent-templates/sample-s3-delivery/pipeline.yml
```
