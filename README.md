# PC_AWS_FARGATE_Clouformation

## This repo provide a manual mockup on how to protect a fargate task on AWS Cloudformation Yaml.


### Objective

This repo has 2 files:
 - Sample_Task.yaml
 - Sample_Protected_Task.yaml


### Parameters used in the Example (Should be customzide to your configuration)


TASK_NAME_TO_BE_PROTECTED = twistlock-fargate-task

CONTAINER_NAME_TO_BE_PROTECTED = twistlock-fargate-task

IMAGE_NAME_TO_BE_PROTECTED = matthewabq/twistlock-fargate-auto

INSTALL_BUNDLE_STRING = On Prisma Conole choose Single Defender -> Defender Type -> Manual from Compute -> Manage -> Defenders -> Deploy -> Defenders

(images/AppEmbedded.png)

WS_CONSOLE_ADDRESS = 

PATH_IMAGE_TWISTLOCK_LOCAL_REGISTRY =
