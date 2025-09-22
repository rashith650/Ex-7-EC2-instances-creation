# Ex-04 EC2 Instance Creation

## *Aim*
To set up and launch an Amazon EC2 instance, providing on-demand computing services with flexible configurations for application deployment.

## *Objectives*
1. *Log into AWS*: Access the AWS Management Console to create and manage resources.
2. *Launch EC2 Instance*: Configure the required instance parameters, including OS, storage, instance type, and network settings.
3. *Create Key Pair*: Generate a secure SSH key pair for EC2 access.
4. *Configure Network*: Adjust the instance’s VPC, subnets, and security groups as needed.
5. *Connect to Instance*: Use SSH to establish a connection to the EC2 instance.
6. *Automate EC2 Instance Creation*: Set up an Ansible playbook to automate the instance setup.
7. *Monitor Instance State*: Track instance states (running, stopped, terminated) and utilize AWS CloudWatch for performance monitoring.

---

## *Instructions*

### Step 1: Log into AWS Account
   - Open the AWS console and select *EC2* under *Services*.
<img width="1132" height="634" alt="Screenshot 2025-09-15 152117" src="https://github.com/user-attachments/assets/ae06269e-9632-4e62-91ff-9f8101e6d1d9" />



### Step 2: Launch an Instance
   - Click on *Launch Instance* and configure *AMI* (Amazon Machine Image) and *Instance Type* (e.g., t2.micro for free tier).


<img width="1011" height="543" alt="Screenshot 2025-09-15 155044" src="https://github.com/user-attachments/assets/0d674d8e-7add-404c-8d39-8cfd418b078d" />

### Step 3: Create Key Pair
   - Generate a *key pair* in .pem format, which will be downloaded for SSH access.


<img width="1015" height="543" alt="Screenshot 2025-09-15 155110" src="https://github.com/user-attachments/assets/80a24bba-9bcd-444e-8ffe-9b5a003df1c0" />

### Step 4: Configure Network and Storage
   - Keep *network settings* default, or customize for VPC, subnets, and security groups.
   - Choose the *EBS storage* (up to 30 GB free for eligible free-tier accounts).


<img width="1011" height="545" alt="Screenshot 2025-09-15 155125" src="https://github.com/user-attachments/assets/6e42a31d-03cc-49a1-8c0d-7dae8f667d41" />

### Step 5: Launch and Connect
   - Confirm configurations and click *Launch Instance*.
   - Connect to the instance using SSH from your terminal with the downloaded key pair.

<img width="1020" height="547" alt="Screenshot 2025-09-15 155151" src="https://github.com/user-attachments/assets/e64595de-86ff-418e-aa8a-f8d6745b289c" />


## *Results*

Successfully created the Elastic Compute Cloud (EC2) instances in this lab.
