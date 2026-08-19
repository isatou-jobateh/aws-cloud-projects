# Elastic Load Balancing (ELB)

## Overview

This project demonstrates my understanding of AWS Elastic Load Balancing (ELB) and how it distributes incoming application traffic across multiple EC2 instances.

## Architecture

![ELB Architecture Diagram](Diagrams/ELB-Architecture-Diagram.png)

## Architecture Components

- **Internet/Users** – Send requests to the application.
- **Application Load Balancer (ALB)** – Receives incoming HTTP/HTTPS traffic and distributes it across healthy EC2 instances.
- **VPC** – Provides the network environment for the resources.
- **Availability Zone A** – Contains EC2 Instance A.
- **Availability Zone B** – Contains EC2 Instance B.
- **EC2 Instances** – Run the application and receive traffic from the load balancer.

## What I Learned

- What Elastic Load Balancing is.
- How an Application Load Balancer distributes traffic.
- Why using multiple Availability Zones improves availability.
- How a load balancer can prevent traffic from being sent to unhealthy instances.
- The relationship between a load balancer, VPC, subnets, and EC2 instances.

## Hands-on Practice

I created an AWS architecture diagram to demonstrate an Application Load Balancer distributing traffic between EC2 instances located in different Availability Zones.

> No AWS console lab was completed for this exercise because a suitable free hands-on ELB lab was not available without requiring an AWS payment card.

## Evidence

- Architecture diagram included in the `Diagrams` folder.