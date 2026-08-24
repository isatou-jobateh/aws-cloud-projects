# Amazon EC2 Auto Scaling

## Overview

This project demonstrates how **Amazon EC2 Auto Scaling** can be used to maintain application availability by automatically managing the number of EC2 instances running in an application environment.

The architecture uses an **Application Load Balancer (ALB)** to distribute incoming traffic across EC2 instances running in multiple Availability Zones. An Auto Scaling Group manages the EC2 instances and can add or remove instances based on demand.

## Architecture

The architecture includes:

* Amazon VPC
* Two Availability Zones
* Two public subnets
* Application Load Balancer
* Target Group
* EC2 instances
* EC2 Auto Scaling Group
* Internet access

### Traffic Flow

```text
Internet
   ↓
Application Load Balancer

   Target Group
   ↓
 ┌───────────────┐
 │               │
AZ-A            AZ-B
 │               │
EC2-A           EC2-B
 ↑               ↑
 └──── Auto Scaling ────┘
```
Tools Used 
draw.io / diagrams.net with offical AWS architecture icons , used to drsign and document the architecture shown above
## What I Learned

Through this project, I learned:

* What Amazon EC2 Auto Scaling is
* How an Auto Scaling Group manages EC2 instances
* How Auto Scaling can increase or decrease the number of instances based on demand
* Why running instances across multiple Availability Zones improves availability
* How an Application Load Balancer distributes traffic across multiple EC2 instances
* How Auto Scaling and load balancing work together
* The difference between handling application traffic and managing instance capacity

## Project Diagram

![Auto Scaling ](Diagrams/Auto-Scaling-Diagram.png)

## Key Concepts

### Auto Scaling Group

An Auto Scaling Group maintains a desired number of EC2 instances and can automatically launch or terminate instances according to configured conditions.

### Application Load Balancer

The Application Load Balancer receives incoming application traffic and distributes it across healthy EC2 instances.

### Availability Zones

The EC2 instances are placed across two Availability Zones. This helps reduce the impact of a failure affecting a single Availability Zone.

## Skills Practiced

* AWS EC2
* EC2 Auto Scaling
* Application Load Balancer
* VPC networking
* Availability Zones
* High availability
* Cloud architecture
* AWS infrastructure diagrams

## Project Outcome

This project helped me understand how AWS services can work together to create a **scalable and highly available application architecture**.

The diagram represents the architecture and the relationship between the Load Balancer, Auto Scaling Group, EC2 instances, Availability Zones, and VPC.

## Hands-on Practice

> No AWS console lab was completed for this exercise because a suitable free hands-on EC2 Auto Scaling lab was not available without requiring an AWS payment card.

