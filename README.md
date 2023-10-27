# Banking-system
VIDEO PRESENTATION - https://drive.google.com/file/d/1ZIOVlux4xDckeFJgPJPOr9VCPNOJgcAe/view?usp=drive_link   (click this link to see the video presentation)
This program is a simple prsesentation of a banking system that allow users to create account,log in, deposit and withdrawal.
This are the key components in this program first i had 
1.Data Storage(account dictionary):this program uses a python dictionary called accounts to store user account information. Each user account is represented as a key a value pair,where the key is the username,and the value is a dictionary containing the password and account balance.
2.Account Creation(create_account): This function allow user to create a new account . it prompt the user to enter a username and password which are stored in the account dictionary 
3.Login: The login function allows user to log into thier existing accounts. it prompts for a username and password annd checks whether the entered credentials match an existing account in the account dictionary
4.Deposit:Users can deposit money into thier accounts using this function.
5.Withdraw:This function enables users to withdraw money from thier accounts.it checks if the amount is valid and does not exceed the acccounts balance before allowing the withdrawal.
6.Main programming loop: The main program loop presents a menu to the user,offering options for account creation,login,deposit,withdrawal,and exiting the program.The user can navigate through the program
