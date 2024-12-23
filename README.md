# LITA_AWS_EC2_PROJECT
 This is a project documentation of the processes involved in launching an EC2 inatance as well as launching an Apache Web Server on it.
 ### VPC Creation
 VPC was created to house the resources in the AWS environment. The CIDR for the VPC is 10.0.0.0/16
 Below is the image of the VPC created:
 ![vpc details](/VPC-Screenshot.jpeg)
 ### Subnet Creation
 Two subnets were created. They are the public and private subnets.
 #### Private Subnet
 ![Private subnet](/Private-Subnet-Screenshot.jpeg)
 #### Public Subnet
 ![Public subnet](/Public-Subnet-Screenshot.jpeg)
 ### Internet Gateway
 An internet gateway was created.
 ![Internet Gateway](/internet-gateway-Screenshot.jpeg)
 ### NACLs Creation
 A Network Access Control List was created as a security layer.
 ![NACLs Details](/NACLs-Screenshot.jpeg)
 ### Security Group Creation
 Security group was created to allow inbound traffic.
 ![Security group](/Security-Group-Screenshot.jpeg)
 ### Launching of EC2 Instance
Ec2 instance was launched.
![EC2 Instance](/ec2-Instance-Screenshot.jpeg)