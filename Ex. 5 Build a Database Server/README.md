# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: A CHANDHNA
* **Register Number**: 212224040051


---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1) Create a Security Group for the RDS DB instance
2) Create a DB Subnet Group
3) Create an Amazon RDS DB instance
4) Interact with your database
   

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

![WhatsApp Image 2026-03-17 at 10 17 35 AM](https://github.com/user-attachments/assets/bb145250-75ef-444d-930d-3618227f86bc)


### Screenshot 2: Database Service Running

![WhatsApp Image 2026-03-17 at 10 17 35 AM](https://github.com/user-attachments/assets/7319b98b-38dd-4c19-96e4-76c924d6f684)

![WhatsApp Image 2026-03-17 at 10 33 48 AM](https://github.com/user-attachments/assets/fd848891-c363-408e-b400-23bdf4e25f14)



### Screenshot 3: Sample Database and Table

<img width="1600" height="793" alt="image" src="https://github.com/user-attachments/assets/dd17ab99-d370-400a-999c-0ce5e86ad00f" />

<img width="1600" height="628" alt="image" src="https://github.com/user-attachments/assets/0d9838d0-e7e8-49b8-9b48-b5dea559a6ad" />




## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
