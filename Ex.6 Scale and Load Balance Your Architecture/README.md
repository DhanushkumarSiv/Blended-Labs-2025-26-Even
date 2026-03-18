# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : Dhanushkumar Sivakumar  
Reg no : 212224040067   
Date   : 18-03-2026

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

1. **Review Existing Architecture**  
   - Examine the current EC2 setup, note AMI, instance type, security groups, and user data.  
   - Identify limitations such as single‑instance bottlenecks or lack of scaling.

2. **Create a Launch Template**  
   - Define EC2 configuration (AMI, instance type, security group, user data).  
   - Save the template for reuse in Auto Scaling operations.

3. **Create an Auto Scaling Group (ASG)**  
   - Use the launch template to build the ASG.  
   - Configure minimum, maximum, and desired capacity, and select availability zones.

4. **Configure an Application Load Balancer (ALB)**  
   - Create the ALB with listeners (HTTP/HTTPS).  
   - Define target groups and health checks for routing traffic.

5. **Register Auto Scaling Group with Load Balancer**  
   - Attach the ASG to the ALB’s target group.  
   - Ensure instances launched by ASG are automatically registered and monitored.

6. **Configure Scaling Policies**  
   - Set CloudWatch alarms to trigger scaling actions.  
   - Example: scale out when CPU > 70%, scale in when CPU < 30%.

7. **Test Load Balancing and Scaling**  
   - Generate traffic using tools (e.g., JMeter, Locust).  
   - Observe ALB distributing requests and ASG adjusting capacity automatically.


---

## Output Screenshots :


<img width="1920" height="1200" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/f70fb9a3-3801-4332-9827-1dae0e56a49e" />


<img width="1920" height="1200" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/762bc395-421b-4736-8785-22f2846dfa62" />


<img width="1920" height="1200" alt="Screenshot (117)" src="https://github.com/user-attachments/assets/f3245e17-e2d2-4951-a345-76ae989dc39f" />






## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
