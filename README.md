# ami

## AMI template for AWS ubuntu EC2 instance

This repository holds packer ami template

## Validate Template

packer validate ami.json

#Build AMI ./packer build -var 'aws_access_key={{access key}}'
-var 'aws_secret_key={{secret key}}'
-var 'aws_region={{region}}'
ami.json


