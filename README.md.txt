# Azure Multi-Region 3-Tier Architecture Lab

## Project Overview

This project demonstrates a secure multi-region 3-tier architecture implemented in Microsoft Azure.

## Architecture Design

Internet → Web Tier → App Tier → Database Tier

## Components Used

* Azure Virtual Machines
* Virtual Networks
* Network Security Groups
* VNet Peering
* Public IP & Private Subnets

## Security Implementation

* Web Tier exposed to Internet (Port 80)
* App Tier accessible only from Web Tier (Port 8080)
* Database Tier accessible only from App Tier (Port 3306)
* Direct Web-to-DB access blocked using NSG rules

## Key Concepts Demonstrated

* Multi-region architecture
* Network segmentation
* NSG rule priority & evaluation
* Private connectivity using VNet peering
* Secure tier communication

## Testing Performed

* Connectivity validation using Netcat (nc)
* NSG traffic flow verification
* Application-level connectivity checks

## Learning Outcome

This project demonstrates real-world Azure networking, security design, and troubleshooting skills required for Cloud Engineer roles.
