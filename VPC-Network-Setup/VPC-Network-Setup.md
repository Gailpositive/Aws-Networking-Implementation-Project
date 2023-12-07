# Documentation For AWS VIRTUAL PRIVATE CLOUD (VPC) NETWORK SETUP

## PROJECT OVERVIEW: Create A Virtual Private Cloud Network, Using The AWS Cloud Console

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

### STEP 3: On the navigation plane, click on subnet to view subnets colomns

<img width="930" alt="vpc 60" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/a66a5d77-2f0a-42c6-ae55-acbc6d6efee5">

<img width="925" alt="vpc 61" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/3c36eb8b-b05c-4707-9a47-7bd3fd458003">

<img width="924" alt="vpc 62" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/f3dad76a-8d1f-46e9-8f7f-4a9d7ea708b1">

### STEP 4: Create Subnet
<img width="765" alt="vpc 63" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/ef85273b-42eb-4b49-af74-6edf77bef945">

<img width="630" alt="vpc 64" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/0f7a6b3b-3e80-4ba9-bfcf-2fcbdb56e02c">

<img width="765" alt="vpc 65" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/e7e3fd90-1b93-42c9-9ccc-0a2c694ab7c7">

<img width="951" alt="vpc 65 subnet created" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/9297fd37-dc14-4bef-bda0-2729aea281c6">

<img width="930" alt="vpc 67" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/77125cb7-d824-4e91-a408-5e6b0b89797e">

<img width="944" alt="vpc 68" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/8fe86e0f-7b50-4466-8b3c-29dd98b99748">

<img width="923" alt="vpc 69" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/685bdb97-a0e2-4199-b147-3fb02acb0d28">

### STEP 5: On the navigation plane, choose Internet gateway to view columns
* Find the internet gateway attached to the VPC. The columns displays the ID of the VPC


### STEP 6: LAUNCH A VIRTUAL MACHINE IN THE VIRTUAL PRIVATE CLOUD USING AWS EC2
* Spine up an EC2 instance
<img width="927" alt="vpc 71" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/2981141a-a8f5-419e-a27b-33478d69c6d6">

<img width="891" alt="vpc 70" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/54a66b75-5f23-4291-b192-2e680004366e">

<img width="753" alt="vpc 72" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/1b53075e-4a4b-4336-848e-66f1b9b844f5">

### Virtual Private Cloud Created
<img width="913" alt="vpc 73 created" src="https://github.com/Gailpositive/Empty-Repo/assets/111061512/9874e787-6b4e-4608-bc52-d36e574efd62">
