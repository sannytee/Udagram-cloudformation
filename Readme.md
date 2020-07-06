# Udagram CloudFormation
 This template deploys a VPC, with a pair of public and private subnets spread across two Availabilty Zones. It deploys an Internet Gateway, with a default route on the public subnets. It deploys a pair of NAT Gateways (one in each AZ), and default routes for them in the private subnets.


## Running the Script
The command below creates a new stack  
``$ create.sh <stack-name> udagram-infrastructure.yml parameters.json  
 ``
 
The command below updates a stack  
``$ update.sh <stack-name> udagram-infrastructure.yml parameters.json``