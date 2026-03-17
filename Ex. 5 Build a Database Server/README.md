# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: Dhanushkumar Sivakumar
* **Register Number**: 212224040067
* **Date of Submission**: 17-03-2026

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


1. Logged into the AWS Academy portal and accessed the Lab 5 environment using the provided credentials.
2. Opened the required AWS service (like EC2 / S3 / RDS) from the AWS Management Console.
3. Configured the necessary resources by following the lab instructions (such as creating instances, buckets, or databases).
4. Set up permissions, security groups, or policies to ensure proper access and functionality.
5. Tested the setup and verified the output to confirm that the lab task was completed successfully.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1200" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/87c5f73e-8379-45c7-8663-68c8c54d36f8" />


---

### Screenshot 2: Database Service Running


<img width="1920" height="1200" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/ea504fb9-8a4f-41a3-8a05-66c5454bdf89" />


---

### Screenshot 3: Sample Database and Table

<img width="1920" height="1200" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/739d735c-012e-4b3d-a3d4-dd3a4dd33294" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
