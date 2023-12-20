# VPC
Virtual Private Cloud
_________________________________________________________________________________________________________________________________________________________________

VPC allows you to customize your networking configuration. VPC is a network that is logically isolated from other network in the cloud. It allows you to have your own IP address range, subnets, internet gateways, NAT gateways and security groups.  

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

![VPC 1](https://github.com/RanguRahul/VPC/assets/120587828/41e910b5-9e31-4237-9ebc-baaf2eee7e3b)



Components of VPC:

A. CIDR and IP address subnets

B. Implied Router and Routing table

C. Internet Gateway

D. Security Group

E. NACL

F. Virtual Private Gateway

G. Peering Connectors

H. Elastic IP
 
Types of VPC:

VPC is of 2 types:    

                                 i. Default VPC
                                 
                                 2. Custom VPC

1). Default VPC:

              ➢ Created in each AWS region when an AWS account is created.

              ➢ Has default CIDR, security group, NACL and route table settings.

              ➢ Has an internet gateway by default.

2). Custom VPC:

               ➢ It is a VPC and AWS account owner creates.
               
               ➢ AWS user creating the Custom VPC can decide the CIDR.

               ➢ It has its own default security group, NACL and route tables.

               ➢ It doesn’t have an internet gateway by default, one needs to be created if needed.

 




               
