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

