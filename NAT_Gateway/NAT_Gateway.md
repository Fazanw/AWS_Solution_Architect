# Creating NAT Gateways in AWS
##
This lab guides you through the process of setting up a NAT Gateway to enable internet access for instances in a private subnet within Amazon Web Services (AWS). The lab aims to familiarize users with Network Address Translation (NAT) and provides a step-by-step demonstration of configuring the required resources to establish internet connectivity for instances in a private subnet.
###
Diagram:
![CreateNATGateway](Images/Diagram/Create_NAT_Gateway_Diagram.png)
###
Steps:
1. [Sign In to AWS Management Console](SignIn.md)
2. [Create a VPC](Create_VPC.md)
3. [Create Public and Private Subnets](Create_Subnet.md)
4. [Create Internet Gateway](Create_IGW.md)
5. [Create Public Route Table and Configure](Create_RouteTable.md)
6. [Launch an EC2 Instance in Public Subnet](Launch_Instance_Public_Subnet.md)
7. [Launch an EC2 Instance in Private Subnet](Launch_Instance_Private_Subnet.md)
8. [SSH into Public and Private EC2 Instance and Test Internet Connectivity](SSH_Connect_EC2.md)
9. [Create a NAT Gateway](Create_NAT_Gateway.md)
10. [Update Route table and configure NAT Gateway](Update_RouteTable.md)
11. [Test Internet connection from Instance inside Private Subnet](Test_Connection_Private.md)
