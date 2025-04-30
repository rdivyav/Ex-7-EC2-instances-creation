# Ex-7-EC2-instances-creation
## Aim
To set up and launch an Amazon EC2 instance, providing on-demand computing services with flexible configurations for application deployment.

## Objectives
Log into AWS: Access the AWS Management Console to create and manage resources.
Launch EC2 Instance: Configure the required instance parameters, including OS, storage, instance type, and network settings.
Create Key Pair: Generate a secure SSH key pair for EC2 access.
Configure Network: Adjust the instance’s VPC, subnets, and security groups as needed.
Connect to Instance: Use SSH to establish a connection to the EC2 instance.
Automate EC2 Instance Creation: Set up an Ansible playbook to automate the instance setup.
Monitor Instance State: Track instance states (running, stopped, terminated) and utilize AWS CloudWatch for performance monitoring.
## Instructions
Step 1: Log into AWS Account
Open the AWS console and select EC2 under Services.
![image](https://github.com/user-attachments/assets/de74cad5-cdb5-48c6-adc4-2d1d68362131)

Step 2: Launch an Instance
Click on Launch Instance and configure AMI (Amazon Machine Image) and Instance Type (e.g., t2.micro for free tier).
![image](https://github.com/user-attachments/assets/3ffcd698-a415-481a-a905-943f9d9eaca8)

Step 3: Create Key Pair
Generate a key pair in .pem format, which will be downloaded for SSH access.
vcc3

![image](https://github.com/user-attachments/assets/31f81896-4ad3-48af-a6e3-130f599d47f9)

Step 4: Configure Network and Storage
Keep network settings default, or customize for VPC, subnets, and security groups.
Choose the EBS storage (up to 30 GB free for eligible free-tier accounts).
vcc4

![image](https://github.com/user-attachments/assets/8b1d3949-6929-4061-85b3-c1ea30107bb3)

Step 5: Launch and Connect
Confirm configurations and click Launch Instance.
Connect to the instance using SSH from your terminal with the downloaded key pair.
vcc5

![image](https://github.com/user-attachments/assets/3a25844f-8b40-474c-ba1e-01c38f31a2f0)

## Results
Successfully created the Elastic Compute Cloud (EC2) instances in this lab.
