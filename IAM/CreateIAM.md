# Create IAM
##
1. AWS Management Console Dashboard. ![Console_Dashboard](Images/Console_Dashboard.png)
2. Type IAM in the Search Bar. ![Search_IAM](Images/Search_IAM.png)
3. Or click on Services and select IAM under the Security, Identity, & Compliance section. ![Services_IAM](Images/Services_IAM.png)
4. In the IAM dashboard, select the Users option in the left panel. ![IAM_Dashboard](Images/IAM_Dashboard.png)
5. Click on the Create User button to create a new IAM user. ![Users_Dashboard](Images/Users_Dashboard.png)
6. In the Add Users page, fill in the User Details section as follows:![Username](Images/Username.png)
   - User name: Enter the desired name for the user.
   - Check the Provide user access to the AWS Management Console - optional checkbox.
   - Select Custom password under Console Password and enter the desired Password for the User.
   - Uncheck the Users must create a new password at the next sign-in (recommended) checkbox.
   - Click the Next button.
7. In the Set permissions section, keep things as the default. Click on the Next button. ![Set_Permissions](Images/SetPermissions.png)
8. Review the configuration that you created before. Find Tags and click the Add New Tag button. ![Review_Create](Images/ReviewCreate.png)
   - Key: Enter your desired Key (For example Dev-Team)
   - Value: Enter your desired Value (For example Developers)
   - Click Create User ![Review_CreateTags](Images/ReviewCreateTags.png)
9. Note: Ignore the above error if it appears while creating Users.
   - Click Close, then Click on the Return to users list button. ![CreatedUser](Images/CreatedUser.png)
   - Lastly Click Continue button. ![CreatedUserContinue](Images/CreatedUserContinue.png)
10. User Creation has been Done. ![UserCreatedDone](Images/UserDoneCreated.png)
