Please use AWS Marketplace templates for the official solution:

https://aws.amazon.com/marketplace/pp/B07DM9MG9L?qid=1555960100502&sr=0-1&ref_=srh_res_product_title
https://aws.amazon.com/marketplace/pp/B07QK2H1M5?qid=1555960100502&sr=0-2&ref_=srh_res_product_title

# Step 1 : Launching a Transit VPC Hub 
Transit VPC all CSR solution for deployment into AWS

[![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/transit-vpc/cisco-transit-vpc-primary-account.template)

# Step 2: Launching a Spoke VPC

[![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/spoke-vpc/spoke-vpc.template)

# Step 3: Optional - Launching DMVPN for Transit VPC

[![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/transit-vpc/dmvpn-spoke/cisco-tvpc-dmvpn-spoke.template)
