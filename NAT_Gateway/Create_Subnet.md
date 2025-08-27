# Create Public and Private Subnets
##
1. Back to the VPC Dashboard, then navigate to Subnets in the left panel. ![VPC_Dashboard](Images/Dashboard_Subnet.png)
2. Let's create a Public subnet. Click on Create Subnet button. ![Create_Subnet](Images/Create_Subnet.png)
3. Configure the Public subnet:
   - VPC ID: Select your desired VPC (For example MyVPC)
   - Subnet Name: Select your desired name for the Subnet (For example MyPublicSubnet)
   - Availability Zone: Select your desired Availability Zone (For example No Reference)
   - IPv4 Subnet CIDR block: Select your desired IPv4 CIDR Block (For example 10.0.0.0/24) ![Configure_Subnet](Images/Configure_Subnet.png)
   - Click on Create subnet button. ![Created_Subnet](Images/Created_Subnet.png)
4. Enable Auto Assign public IP to Instances created within this subnet:
   - Select you desired Subnet (For example MyPublicSubnet), Click on Actions.
   - Click on Edit subnet settings. ![AutoAssignIP](Images/AutoAssignIP.png)
   - Enable auto-assign public IPv4 address: Check
   - Click on Save.![AutoAssignIP_Done](Images/AutoAssignIP_Done.png)
5. Now, the Instances launched inside the MyPublicSubnet will have Public IPs assigned to them by default.
6. Let’s create a private subnet. Click on Create subnet. ![Create_Private_Subnet](Images/Create_Private_Subnet.png)
7. Configure the Private subnet:
   - VPC ID: Select your desired VPC (For example MyVPC)
   - Subnet Name: Select your desired name for the Subnet (For example MyPrivateSubnet)
   - Availability Zone: Select your desired Availability Zone (For example No Reference)
   - IPv4 Subnet CIDR block: Select your desired IPv4 CIDR Block (For example 10.0.1.0/24) ![Configure_Subnet](Images/Configure_Private_Subnet.png)
   - Click on Create subnet button. ![Created_Subnet](Images/Created_Private_Subnet.png)
8. Public and Private Subnets have been Created. ![Created_Subnet_Done](Images/Created_Subnet_Done.png)
