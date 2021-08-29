# general-cfn-template

## What is this?

general template of cloudformation yaml file for me.

## Description(and todo...)

1. general VPC
   1. general-vpc.yaml
      1. build general VPC and subnet.
2. general EC2 Multi-AZ(public using key-pair)
3. general Aurora Database(MySQL)
   1. aurora_mysql-main.template.yaml
      1. build Aurora MySQL Database with VPC(optional bastion)
   2. aurora_mysql.template.yaml
      1. build Aurora MySQL Database using exsiting VPC
4. CloudWatch Alarm
   1. CloudWatch-for-Lambda.yaml
5. SNS Topic
   1. SNS-topic-for-email.yaml
6. SAM(sample api gateway and lambda)

## general VPC

## general Aurora Database(MySQL)

## CloudWatch Alarm

## SNS Topic