# AWS VPC And Networking Demos

This section contains several AWS VPC and Networking demos. Starting from very basic VPC setup to Advanced concepts like VPC peering, Transit gateway, Site To Site VPN etc.

## Author: Girish Jaju
### LinkedIn: https://linkedin.com/in/girishjaju
### Youtube Channel: https://www.youtube.com/channel/UCqGYxFy2OWDvyB84jyNaUvw

#

### VPC Demo
In this demo, we will perform the following tasks, step by step
1. Create a VPC with One Public Subnet. Setup Route table and Launch a EC2 instance, SSH to instance
2. Add a Private Subnet to the VPC, Setup Route table and Launch an EC2 instance, SSH to the instance via Public instance
3. Create NAT Gateway in Public Subnet, Set a route in the Private Subnet's Route table, Now Private instance can access Internet
4. Setup VPC End point to S3 service and attach to the Private Subnet's Route. EC2 instance should be able to access S3 without Internet access.

### Youtube Video For This Tutorial: https://youtu.be/4z_-VkRg_Bs


