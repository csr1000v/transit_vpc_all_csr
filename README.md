# Step 1 : Launch transit_vpc_all_csr
Transit VPC all CSR solution for deployment into AWS

| Region | Link to Launch |
| ---|---|
| us-east-1 |  [![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/transit-vpc/cisco-transit-vpc-primary-account.template)
| us-east-2 |  [![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-2/latest/transit-vpc/cisco-transit-vpc-primary-account.template)
| us-west-1 | [![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-west-1/latest/transit-vpc/cisco-transit-vpc-primary-account.template)
| us-west-2 | [![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-west-2/latest/transit-vpc/cisco-transit-vpc-primary-account.template)

# Step 2: Spoke template launch

[![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/spoke-vpc/spoke-vpc.template)

# Step 3: Optional - DMVPN template launch

[![Click Here to Launch the template](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=AllCSRTransitVPCStack&templateURL=https://s3.amazonaws.com/cisco-csr-tvpc-dmvpn-us-east-1/latest/transit-vpc/dmvpn-spoke/cisco-tvpc-dmvpn-spoke.template)
