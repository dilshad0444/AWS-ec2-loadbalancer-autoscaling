AWS EC2 with Application Load Balancer and Auto Scaling

Project Overview

This project demonstrates how to build a highly available and scalable web application using Amazon EC2, Application Load Balancer (ALB), and Auto Scaling.

AWS Services Used

* Amazon EC2: Runs web server instances.
* Application Load Balancer: Distributes incoming traffic across healthy EC2 instances.
* Auto Scaling Group: Automatically adjusts the number of EC2 instances according to configured scaling policies.
* Amazon VPC: Provides networking for the resources.

Architecture

Users → Application Load Balancer → EC2 Instances in an Auto Scaling Group

Key Features

* Distributes incoming traffic across multiple EC2 instances.
* Improves availability by routing traffic to healthy instances.
* Automatically adds or removes instances based on scaling policies.
* Supports deployment across multiple Availability Zones.

Implementation Steps

1. Create the required security groups.
2. Create a Launch Template with the web server configuration.
3. Create an Auto Scaling Group.
4. Configure an Application Load Balancer and target group.
5. Verify that the website is accessible through the Load Balancer DNS name.
6. Test scaling and instance health.

Project Status

Documentation prepared. Implementation and testing are to be completed.

Learning Outcomes

Learned the fundamentals of load balancing, automatic scaling, and highly available web applications on AWS.S