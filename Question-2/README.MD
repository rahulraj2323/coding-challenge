#  Online Challenge
## Solution for question-2

This python module makes it easy to query the meta data of an instance within AWS and provide a json formatted output.

## Bonus Points

 The code allows for a particular data key to be retrieved individually.

## PRE-REQUISITES

- Python3.6 or higher
- Requests Module

## Usage
Below are the supported meta-data key words as per AWS Documentations:

- ami-id
- ami-launch-index
- ami-manifest-path
- block-device-mapping/
- events/
- hostname
- iam/
- instance-action
- instance-id
- instance-life-cycle
- instance-type
- local-hostname
- local-ipv4
- mac
- metrics/
- network/
- placement/
- profile
- public-hostname
- public-ipv4
- public-keys/
- reservation-id
- security-groups
- services/

Basic usage of this module is as follows:

```hcl
python3.6 metadata.py ami-id
```

```hcl
python3.6 metadata.py public-ipv4
```
![alt text](https://github.com/rahulraj2323/coding-challenge/blob/master/Question-2/Capture.PNG)
## Author
- [Rahul Raj](https://github.com/rahulraj2323)

##### Credit
- [iMilnb](https://gist.github.com/iMilnb/ab9939e83168d6df6457e50b0ca73c78#file-meta2dict-py-L19)