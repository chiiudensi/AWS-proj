# AWS-proj

## Architecture Overview
The three-tier architecture consists of the following layers:

## Presentation Tier (Web Tier):

## Hosts the frontend of the application.
Uses Amazon EC2 instances behind an Elastic Load Balancer (ELB) to ensure high availability.
Application Tier (Logic Tier):

## Handles the business logic.
EC2 instances are used to process requests from the Web Tier and communicate with the Database Tier.
