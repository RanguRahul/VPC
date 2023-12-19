# VPC
Virtual Private Cloud

VPC allows you to customize your networking configuration. VPC is a network that is logically isolated from other network in the cloud. It allows you to have your own IP address range, 

    subnets, internet gateways, NAT gateways and security groups.  

➢ VPC is a virtual network of data center inside AWS for one client.

➢ Maximum 5 VPC can be created in one region and 200 subnets in 1 VPC.

➢ We can allocate maximum 5 Elastic IP.

➢ Once we created VPC, DHCP(Dynamic Host Configuration Portal), NACL and security group will automatically created.

➢ A VPC is confined to an AWS region and does not extend between regions.

➢ Once the VPC is created you cannot change its CIDR block range.

➢ If you need a different CIDR size create a new VPC.

➢ The different subnets within a VPC cannot overlap.

VPC Architecture :


![architecture-of-vpc](https://github.com/RanguRahul/VPC/assets/120587828/2fbb522e-0822-46e5-a409-375e985df580)
