## Virtual Private Cloud (VPC)
* Open the Amazon VPC console at: https://console.aws.amazon.com/vpc/.
* Select the VPC dashboard and Launch the VPC Wizard.
* Choose the type of VPC you require.
* On the config page, add a name for the VPC and the subnet names.
* Click Create VPC.
* This will take you to the Your VPC page.
* Click on Security Groups and select Create Security Group.
* Provide a name and a description for the new Security Group and an ID for the VPC.
* On the Inbound Routes tab you can define the security rules you require.
* Create an AMI to run the VPC on from by clicking on Launch Instance and running through the setup wizard.
* On the Configure Instance Details page, select the VPC that you created from the Network list, and the subnet from the Subnet list.
* On the configure Security Group page select the security group you have created.
* On the Review Instance Launch page, click Launch.
* You will have to use a key pair to continue.
* Click Launch Instances.
* Back on the VPC Console, click on Elastic IPs.
* Choose Allocate new address, and then Allocate.
* Select the Elastic IP address click Actions and then choose Associate Address. This will make the Internet Gateway.
* In Resource type, when Instance is selected, select your instance from the list.
* Choose Associate when finished.
