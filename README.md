# AWS-VPC-Architecture

## Network Architecture

![AWS VPC Architecture](aws-vpc-architecture.png)

## Project Overview

This project explores the design and configuration of an Amazon Virtual Private Cloud (VPC) with segmented public and private subnets.

The objective is to understand how AWS networking components work together to provide network connectivity, traffic routing, and access control.

## Technologies Used

- Amazon VPC
- Amazon EC2
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network Access Control Lists (NACLs)

## Architecture Design

The architecture separates public-facing resources from private resources using dedicated subnets and routing configurations.

## Implementation

1. Created an Amazon VPC and configured its CIDR block.
2. Configured public and private subnets.
3. Set up an Internet Gateway for internet connectivity.
4. Configured routing for public and private subnets.
5. Configured a NAT Gateway for outbound connectivity from private subnets.
6. Applied security groups and network ACL rules.

## Key Learnings

- VPC architecture and CIDR planning
- Public versus private subnet routing
- Internet Gateway and NAT Gateway functionality
- Stateful security groups and stateless NACLs
- Network isolation and access control

## Future Improvements

Potential improvements include infrastructure automation using Terraform, multi-Availability Zone deployment, VPC endpoints, and monitoring with VPC Flow Logs.
