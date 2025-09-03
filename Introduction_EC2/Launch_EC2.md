# Launch an EC2 Instance with desired specifications
##
1. Back to AWS Management Console Dashboard, then type EC2 in the Search Bar. ![Search_EC2](Images/Search_EC2.png)
2. Or click on Services and select EC2 under the Compute section. ![Services_EC2](Images/Services_EC2.png)
3. In the EC2 dashboard, select the Instances option in the left panel and click Launch Instances. ![Launch_EC2](Images/Launch_EC2.png)
4. Configure your Instance:
   - Name: Enter your desired name for your Instance (For example MyPublicServer)
   - For Amazon Machine Image (AMI): Select your desired Operating System and Version (For example Amazon Linux 2023 kernel-6.1 AMI). ![Configure_EC2_A](Images/Configure_EC2_A.png)
   - Instance Type: Select your desired Instance Type (For example t2.micro).
   - Create a new Key Pair, then Configure it: ![Configure_EC2_B](Images/Configure_EC2_B.png)
     + Key Pair name: MyKey
     + Key Pair type: RSA
     + Private Key file format: .pem 
     + Click on the Create Key Pair button. ![Configure_KeyPair](Images/Configure_KeyPair.png)