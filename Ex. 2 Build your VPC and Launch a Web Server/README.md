# Build Your VPC and Launch a Web Server (AWS) 

## Author

* **Name**: A CHANDHNA
* **Register Number**: 212224040051
* **Date of Submission**: 24/02/2026

---

## Objective

The objective of this experiment is to understand how to design and configure a basic network infrastructure in AWS using a Virtual Private Cloud (VPC). This lab focuses on creating a VPC with a public subnet, configuring an Internet Gateway and route table, launching an EC2 instance, and hosting a simple web server that can be accessed over the internet.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity

---

## Tools Used

* AWS Management Console
* Amazon VPC
* Amazon EC2
* Internet Gateway
* Route Table
* Security Groups

---

## Tasks Performed

### Task 1: Create a VPC

Create a new Virtual Private Cloud (VPC) with a private IP address range. The VPC acts as a logically isolated network in AWS where all other resources will be deployed.

Students should create a VPC with an appropriate CIDR block (for example, 10.0.0.0/16) and assign a meaningful name.


### Task 2: Create a Public Subnet

Create a subnet inside the VPC to host public resources. Enable auto-assign public IPv4 so that instances launched in this subnet receive a public IP address.

The subnet should use a smaller CIDR range (for example, 10.0.1.0/24).


### Task 3: Create and Attach Internet Gateway

Create an Internet Gateway (IGW) and attach it to the VPC. This allows communication between resources in the VPC and the internet.


### Task 4: Configure Route Table

Create a route table and add a default route (0.0.0.0/0) pointing to the Internet Gateway. Associate this route table with the public subnet.

This step ensures that traffic from the subnet can reach the internet.


### Task 5: Create Security Group

Create a security group to act as a virtual firewall for the EC2 instance. Configure inbound rules to allow:

SSH on port 22

HTTP on port 80


### Task 6: Launch EC2 Instance

Launch an EC2 instance inside the public subnet using Amazon Linux 2 AMI and a suitable instance type (t2.micro).

Attach the previously created security group and key pair.


### Task 7: Configure Web Server

Install and start a web server (Apache HTTPD) on the EC2 instance using user data or manual commands.

Create a simple HTML page and verify that it can be accessed from a web browser using the public IP address of the instance.---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. ---
2. ---
3. ---
4. ---
5. ---

---

## Output Screenshots (Attach 3)

### Screenshot 1: VPC and Subnet Details

<img width="1600" height="838" alt="image" src="https://github.com/user-attachments/assets/d6377f56-e2a0-4860-a6f3-4e2b2181f0da" />

<img width="1600" height="845" alt="image" src="https://github.com/user-attachments/assets/a293fcc9-bbe3-4df9-812a-038426115294" />

<img width="1600" height="856" alt="image" src="https://github.com/user-attachments/assets/5adc5b18-75a6-43b0-a7cd-5244f5679447" />

<img width="1600" height="853" alt="image" src="https://github.com/user-attachments/assets/d387b72b-231b-43f8-b6df-cd53b29c065f" />



### Screenshot 2: EC2 Instance Running

<img width="960" height="510" alt="image" src="https://github.com/user-attachments/assets/5aa885fb-b848-4b98-9577-7dff1f914ad7" />


### Screenshot 3: Web Server Output in Browser

<img width="956" height="508" alt="image" src="https://github.com/user-attachments/assets/06a35b55-3d28-4272-8e1a-ec6289163e15" />


## Result 

This experiment successfully demonstrated the creation of a custom VPC and deployment of a public-facing web server in AWS. By configuring networking components such as subnets, route tables, and security groups, and by launching an EC2 instance with a web server, the basic architecture of a cloud-hosted application was understood.
