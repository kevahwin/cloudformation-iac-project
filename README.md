# Deploy a high-availability web app using AWS CloudFormation

This project deploys web servers for a highly available web app using CloudFormation. It creates and deploys the infrastructure and application for an Instagram-like app from the ground up. This involves networking components, followed by servers, security roles and software. 

![Infrastructure Diagram](cloudformation-infra-diagram-ka.drawio.png)

## Getting Started

### Dependencies

1. AWS CLI installed and configured in your workspace using an AWS IAM role with Administrator permissions.


### Installation

You can get started by cloning this repo in your local workspace:

```
https://github.com/kevahwin/cloudformation-iac-project.git
```

## Project Instructions

### Spin up instructions
To spin up the infrastructure, run the following command:

```sh
./run.sh deploy <region> <stack-name> <template-file> <parameters-file>
```

Make sure to replace ``` <region>, <stack-name>, <template-file>, and <parameters-file> ``` with your specific region, stack name, template file, and parameters file.

### Tear down instructions
To tear down the infrastructure, run the following command:
```sh
./run.sh delete <region> <stack-name>
```

### Other considerations
Note: Before running the script, ensure it has execute permissions by running:

```sh
chmod +x run.sh
```

## Acknowledgements

This is the final project of course 2 Infrastructure as Code in the Cloud DevOps Engineer Nanodegree.
Please note that all supporting and starter material for this course can be found in [this Github repository](https://github.com/udacity/cd12352-Deploy-Infrastructure-as-Code).
