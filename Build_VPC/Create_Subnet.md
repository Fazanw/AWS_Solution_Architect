# Creating Subnets
##
1. Back to the VPC Dashboard, then navigate to Subnets in the left panel. ![Dashboard_Subnet](Images/Dashboard_Subnet.png)
2. Let's create a Public subnet. Click on Create Subnet button. ![Create_Subnet](Images/Create_Public_Subnet.png)
3. Configure the Public subnet:
   - VPC ID: Select your desired VPC (For example MyVPC)
   - Subnet Name: Select your desired name for the Subnet (For example MyPublicSubnet)
   - Availability Zone: Select your desired Availability Zone (For example us-east-1a)
   - IPv4 Subnet CIDR block: Select your desired IPv4 CIDR Block (For example 10.0.1.0/24) ![Configure_Subnet](Images/Configure_Public_Subnet.png)
   - Click on Create subnet button. ![Created_Public_Subnet](Images/Created_Public_Subnet.png)
4. Back to Subnets Dashboard then create a private subnet with Click on Create subnet. ![Create_Private_Subnet](Images/Create_Private_Subnet.png)
5. Configure the Private subnet:
   - VPC ID: Select your desired VPC (For example MyVPC)
   - Subnet Name: Select your desired name for the Subnet (For example MyPrivateSubnet)
   - Availability Zone: Select your desired Availability Zone (For example us-east-1b)
   - IPv4 Subnet CIDR block: Select your desired IPv4 CIDR Block (For example 10.0.2.0/24) ![Configure_Private_Subnet](Images/Configure_Private_Subnet.png)
   - Click on Create subnet button. ![Created_Private_Subnet](Images/Created_Private_Subnet.png)
6. Public and Private Subnets have been Created. ![Created_Subnet_Done](Images/Created_Subnet_Done.png)