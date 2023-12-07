# Documentation SETUP For AWS VIRTUAL PRIVATE CLOUD (VPC) NETWORK 

## Create a VPC and Launch an ec2 instance into the VPC using AWS VPC wizard

<img width="714" alt="23B" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/4f5da7ae-7378-42f3-8fd6-42925f073564">

  
 ## This Project shows how to create AWS VPC wizard with the following steps:
### . Creates the VPC with a network of 65,536 privates IP addresses
### . Attach an internet gateway to the vitual private cloud 
### . Create a range of 250 IP addresses in the VPC
### . Create a custom route table and associated with a subnet so traffic can flow within the subnet and the internet gateway
 
### STEP 1: On the AWS management console, type VPC on the search bar
* Next, Click on "Create VPC" to launch VPC wizard 
<img width="957" alt="vpc 52" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/837340f1-3cc5-4121-884a-f0607a5ff140">

* Select VPC only 
<img width="708" alt="vpc 53" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/7d6dd5f7-edd1-4630-abe2-f2088e004694">

<img width="818" alt="vpc 54" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/80453a29-a709-46b8-a3ce-75b31d4507de">
. And click create VPC 

* Defualt VPC created and displayed
<img width="893" alt="vpc 55" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/6e07c862-28b7-47de-b7bf-467d174badfb">

<img width="907" alt="vpc 56" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/b07deba4-d351-4b09-8fe4-4937415c98d8">

<img width="905" alt="vpc 57" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/f0301836-9803-4234-8ab3-555c20312e38">

### STEP 2:  On the navigation plane, Click on VPC, Two Main tables is created , The Main route table and Main network ACL.
* The Main route table is a custom table created by the wizard while the Main network ACL is a defualt table. All VPC has a Main network ACL table by defualt 
* The custom route table is associated with the subnet which means the route on this table is determine how traffic for the subnet flows. 
* If a new subnet is added to my VPC, it uses the main route table by default
<img width="921" alt="vpc 58" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/79bbe2a9-876c-4a80-871f-f78cf42756f4">

<img width="915" alt="vpc 59" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/801ae5e6-b200-4ee2-af5b-1bcce2d21758">

### STEP 3: On the navigation plane, click on subnet to view subnets created

<img width="930" alt="vpc 60" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/a66a5d77-2f0a-42c6-ae55-acbc6d6efee5">

<img width="925" alt="vpc 61" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/3c36eb8b-b05c-4707-9a47-7bd3fd458003">

<img width="924" alt="vpc 62" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/f3dad76a-8d1f-46e9-8f7f-4a9d7ea708b1">
