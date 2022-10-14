# Terraform
Hello,
I have created Terraform script to create the resources in AWS. Have configure Security group and Load balaner for the resources.
Script is creating 2 web server in public subnet and 1 postgre DB server in private subnet.
Script will create and configure below things:
1.VPC
2.Internet Gateway
3.2 public subnets
4.Private subnet
5.Route table to internet gateway
6.Associate public subnets with route table
7.Security group for Publuc & Private Subnet
8.Security group for ALB
9.Create ALB
10.Create ALB target group
11.Create target attachments
12.Create listener
13.Create ec2 instances and DB server
14.Output
