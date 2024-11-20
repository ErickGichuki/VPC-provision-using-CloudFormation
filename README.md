Using AWS CloudFormation to create an AWS VPC and Amazon EC2 instance
Create a CloudFormation template with the following components;
 - An Amazon Virtual Private Cloud.
 - An internet gateway attached to the VPC.
 - Security groups for accessing the VPC configured to allow SSH anywhere.
 - A private subnet within the VPC.
 - An Amazon EC2 instance(a t3.micro) within the private subnet.