#  Online Challenge
## Solution for question-1

This module creates a 3-tier environment using AWS CloudFormation Nested Stack.

## PRE-REQUISITES

- Upload 3-tier-vpc-set-up.yml, alb-set-up.yml and master-template.yml to any s3 bucket.
- Update the new template location(s3 url of 3-tier-vpc-set-up.yml and alb-set-up.yml) for VPCStack and PortalStack.
- Execute the master-template.yml

## Architecture
![alt text](https://miro.medium.com/max/1050/1*PDHya_zt_n657nYUAm1OeA.jpeg)
## Usage

Basic usage of this module is as follows:

```hcl
aws cloudformation deploy --stack-name kpmg-online-test-stack --template-file ./master-template.yaml --parameter-overrides EnvironmentName=dev EC2Tenancy=default'
```
## Author
- [Rahul Raj](https://github.com/rahulraj2323)

##### Credit
- [The Andela Way](https://medium.com/the-andela-way/designing-a-three-tier-architecture-in-aws-e5c24671f124)