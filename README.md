## Table of contents

- [Table of contents](#table-of-contents)
- [Assignment requirement](#assignment-requirement)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [My details](#my-details)

## Assignment requirement

**Requirements:**

We are going to start setting up our AWS infrastructure. This assignment will focus on setting up our networking resources such as Virtual Private Cloud (VPC), Internet Gateway, Route Tables, and Routes. We will use AWS CloudFormation for infrastructure setup and tear down.
## Technologies

*aws

  
## Getting Started

```sh
#clone it
git clone git@github.com:Xinyi-12/infrastructure.git

# AWS CLI
aws configure --profile=<xxxx>

aws cloudformation create-stack --stack-name <thur-vpc5> --template-body 
<file:///home/vpc6.yml>

aws cloudformation list-stack-resources --stack-name <thur-vpc5>

aws cloudformation delete-stack --stack-name <thur-vpc5>


## My details

Name: Xinyi Chen

NUID: 001582439

Email: [chen.xiny@northeastern.edu](mailto:chen.xiny@northeastern.edu)

