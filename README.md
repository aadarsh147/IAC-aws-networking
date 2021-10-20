# IAC-aws-networking

This a terraform code to provision aws networking resources. Code is categorised into modules and envrionment. 

Following networking resources are created via this terraform code

VPC
3 Public Subnet
3 Private Subnet
1 internet Gateway
1 Elastic IP
1 NAT Gateway
1 Public Route Table
1 Private Route Table
Public Route table associations
Private Route teable associations

All these resource code is written in modules section. Main section is only used for passing the variables to modules
Steps to run - 

preqreuisites - 



1. Clone the repository
<Unzip here>
2. CD IAC-aws-networking/networking/Dev/
3. terraform init
4. terraform plan
5. terraform apply

....
