# Documentation SETUP For AWS VIRTUAL PRIVATE CLOUD (VPC) NETWORK 

## Create a VPC and Launch an ec2 instance into the VPC using AWS VPC wizard

<img width="714" alt="23B" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/4f5da7ae-7378-42f3-8fd6-42925f073564">

  
 ## This Project shows how to create AWS VPC wizard with the following steps:
### . Creates the VPC with a network of 65,536 privates IP addresses
### . Attach an internet gateway to the vitual private cloud 
### . Create a range of 250 IP addresses in the VPC
### . Create a custom route table and associated with a subnet so traffic can flow within the subnet and the internet gateway
 
## STEP 1: On the AWS management console, type VPC on the search bar
. Next, Click on "Create VPC" to launch VPC wizard 
<img width="957" alt="vpc 52" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/837340f1-3cc5-4121-884a-f0607a5ff140">

. Select VPC only 
<img width="708" alt="vpc 53" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/7d6dd5f7-edd1-4630-abe2-f2088e004694">

<img width="818" alt="vpc 54" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/80453a29-a709-46b8-a3ce-75b31d4507de">
. And click create VPC 

. Defualt VPC displayed
. Two Main tables created: Main route table which is a custom table created by the wizard 
. And the Main network ACL. All VPC has a Main network ACL table by defualt 
. The custom route table is associated with the subnet.
