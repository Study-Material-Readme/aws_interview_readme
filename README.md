# aws_interview_readme

## What are the Storage Classes available in Amazon S3?
Storage Classes available with Amazon S3 are:

* Amazon S3 Standard
* Amazon S3 Standard-Infrequent Access
* Amazon S3 Reduced Redundancy Storage
* Amazon Glacier

## Explain what S3 is?
S3 stands for Simple Storage Service. You can use the S3 interface to store and retrieve any amount of data, at any time and from anywhere on the web. For S3, the payment model is “pay as you go”.

## What is the relation between the Availability Zone and Region?
An AWS Availability Zone is a physical location where an Amazon data center is located. On the other hand, an AWS Region is a collection or group of Availability Zones or Data Centers. 

This setup helps your services to be more available as you can place your VMs in different data centers within an AWS Region. If one of the data centers fails in a Region, the client requests still get served from the other data centers located in the same Region. This arrangement, thus, helps your service to be available even if a Data Center goes down.

## What are the advantages of AWS IAM?
AWS IAM enables an administrator to provide granular level access to different users and groups. Different users and user groups may need different levels of access to different resources created. With IAM, you can create roles with specific access-levels and assign the roles to the users. 

It also allows you to provide access to the resources to users and applications without creating the IAM Roles, which is known as Federated Access.

## What is auto-scaling?
Auto-scaling is a function that allows you to provision and launch new instances whenever there is a demand. It allows you to automatically increase or decrease resource capacity in relation to the demand.

## Name some of the AWS services that are not region-specific
AWS services that are not region-specific are:

* IAM
* Route 53
* Web Application Firewall 
* CloudFront

## What is the difference between an IAM role and an IAM user?
The two key differences between the IAM role and IAM user are:

* An IAM role is an IAM entity that defines a set of permissions for making AWS service requests, while an IAM user has permanent long-term credentials and is used to interact with the AWS services directly.  
* In the IAM role, trusted entities, like IAM users, applications, or an AWS service, assume roles whereas the IAM user has full access to all the AWS IAM functionalities.

## How many buckets can you create in AWS by default?
By default, you can create up to 100 buckets in each of your AWS accounts.

## What is AWS Lambda?
Lambda is an Amazon compute service which allows you to run code in the  AWS Cloud without managing servers.

## Name some of the DB engines which can be used in AWS RDS
* MS-SQL DB
* MariaDB
* MYSQL DB
* OracleDB
* PostgreDB

## What is the minimum and maximum size that you can store in S3?
The minimum size of an object that you can store in S3 is 0 bytes and the maximum size of an object that you can store in S3 is 5 TB.

## What is the default storage class in S3?
The default storage class is Standard Frequently Accessed.

## What is Amazon Kinesis Firehose?
An Amazon Kinesis Firehose is a web service used to deliver real-time streaming data to destinations such as Amazon Simple Storage Service, Amazon Redshift, etc.

## Differences between horizontal scaling and vertical scaling?
Vertical scaling means scaling the compute power such as CPU, RAM to your existing machine while horizontal scaling means adding more machines to your server or database. Horizontal scaling means increasing the number of nodes, and distributing the tasks among different nodes.
