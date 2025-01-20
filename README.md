# Three-Tier VPC Architecture on AWS:


This project sets up a Three-Tier VPC Architecture in AWS using Terraform. 
The architecture consists of three layers:

Web Layer: Public subnet with an Elastic Load Balancer (ALB) and EC2 instances running a web application.
Application Layer: Private subnet with EC2 instances for your application logic.
Database Layer: Private subnet with an RDS instance for database management.

Resources Created:
VPC: A Virtual Private Cloud to host the architecture.
Subnets: Public and private subnets for each layer.
EC2 Instances: Web and application servers running in their respective subnets.
RDS: A managed database service (e.g., MySQL or PostgreSQL).
ALB: An Application Load Balancer to route traffic to the web layer.
NAT Gateway: To allow private instances to access the internet
