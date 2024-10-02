# Project-1
Deploying AWS EKS Cluster with Terraform
Hello, in this project I have used IaC to create EKS Cluster on AWS using Terraform.
1. I had to configure Terraform with right configrations to allow this project to happen. This inlcudes giving Terraform my access keys to access AWS. I had to also install kubectl, make sure the right AWS version and Terraform were installed. 
2. I started to create my code using Terraform, this started with defining the provider, the source and version. This can be seen in the provider.tf file.
3. Started to code my resource blocks, cidr blocks and vpc. I have stated the ip address with subnets and availability zones.
4. Next i started to code and define the gateway.
5. I had a few problems getting the right network connection to the subnets so i had to create a route table allowwing the subnet to access the right network connection.
6. next line of code shows the module EKS being used with i imported from the Terraform website. This creates the EKS clusters and nodes. which ive connected the subnets to.
7. "aws eks update--kubeconfig --region eu-west-2 --name project_1" This command in terminal allows us to connect EKS to kubectl.
8. All code ive added to this repo.

Tools Used: Terraform, Visual Studios, AWS, Github and kubernetes 
