# Overview
This repo is a demonstration of Continuous Delivery of a single page application to S3 via CodeBuild and CodePipeline.  To launch, you'll need to specify a unique s3 bucket name for the website bucket that will be created.  Additionally, you'll need to have a [GitHub token](https://github.com/settings/tokens) available to provide to the stack for it to access the GitHub repo.

[![Launch CFN stack](https://s3.amazonaws.com/stelligent-public/media/images/buttons/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#cstack=sn~sample-s3-delivery|turl~https://s3.amazonaws.com/stelligent-public/cloudformation-templates/github/labs/spa/pipeline.yml)

