# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : your name   Reg no : yours   Date :

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.


### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 

![WhatsApp Image 2026-03-19 at 10 10 39 AM](https://github.com/user-attachments/assets/ef7edfef-b874-4ea7-bdb9-0696a9f808dc)

![WhatsApp Image 2026-03-19 at 10 17 10 AM](https://github.com/user-attachments/assets/194bf5a2-5963-4aa3-9f0a-4e2092440861)

![WhatsApp Image 2026-03-19 at 10 17 10 AM](https://github.com/user-attachments/assets/511f1d41-0b91-4793-ba5f-a99a119ec8d7)

![WhatsApp Image 2026-03-19 at 10 23 59 AM](https://github.com/user-attachments/assets/ca26a668-1cc2-4fcd-b876-2e6bd91082f5)

![WhatsApp Image 2026-03-19 at 10 26 29 AM](https://github.com/user-attachments/assets/0e9e01a9-714e-4f60-8543-60306a0e8927)

![WhatsApp Image 2026-03-19 at 10 37 10 AM](https://github.com/user-attachments/assets/a0b5e12a-73e6-4c79-b2c2-04dda52ceb3b)

![WhatsApp Image 2026-03-19 at 10 37 54 AM](https://github.com/user-attachments/assets/54a58109-783c-43a4-831b-c196bd9c2b19)




## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
