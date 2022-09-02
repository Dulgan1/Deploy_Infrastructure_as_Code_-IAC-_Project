# Deploy Infrastructure as Code using Cloud Formation AWS project -Cloud DevOp

This repository contains basic files to create a cloud infrastructure.

## Network Infrastructure YAML file (network-Infra-project.yml)

This template file creates the resources necessary for the network of the infrastructure which includes the VPC, Subnets (private and public), Internet gateway and NAT gateways

## Server(Bone) Infrastructure YAML file (server-infra-project.yml) 

This template file creates the 'bone' resources of the cloud infrastructure which includes the EC2 instances auto-scaling group and security group, application load balancer and load balancer security  group, app archive S3 bucket.

## Parameter files for template

- server-parameters.json
- network--parameters.json

## Image File 

The image file shows the representative diagram of the infrastructure

## Script Files 

- create-stack.sh bash script file to create an aws cloudFormation stack

- update-stack.sh bash script file to update created stack