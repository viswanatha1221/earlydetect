1. VPC with public and private subnets in 2 avaialability zones.
2. An Internet Gateway is used to allow communication between instances in VPC and the internet
3. we are using 2 Availability Zones for high avaialability and fault tolerance.
4. Resources such as Nat Gateways, Bastion Host, and Application Load balancer use Public Subnets.
5. We will put the webservers and database servers in the Private Subents to protect them.
The Public Route Table is associated with the public subnets and routes traffic to the internet through the internet gateway.
6. The Main Route Table is associated with the private subnets.