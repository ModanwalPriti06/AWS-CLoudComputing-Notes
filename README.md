# AWS (Amazon Web Service)
# Prerequisites (Before Learning AWS)
- ✅ Basic Linux Commands (for EC2)
- ✅ Networking Basics (IP, DNS, Firewall, Ports)
- ✅ Understanding of Cloud Computing

# Learn AWS EC2 (Virtual Servers in Cloud)
## Beginner Level (Basic Setup)
- 🔹 Create an AWS Free Tier Account
- 🔹 Launch an EC2 Instance (Ubuntu/ Amazon Linux)
- 🔹 Connect to EC2 using SSH (PuTTY, Terminal)
- 🔹 Understand EC2 Instance Types (t2.micro, t3.medium, etc.)
- 🔹 Learn about Security Groups (Firewalls for EC2)
- 🔹 Set Up Key Pair Authentication
- 🔹 Install Node.js, MongoDB, and Deploy a MERN App

## Intermediate Level (2-Year Experience Level)
- 🔹 Elastic IP: Assigning Static IP to EC2
- 🔹 Auto Scaling: Handling Traffic Spikes
- 🔹 Load Balancer: Distribute Traffic Across EC2s
- 🔹 EC2 User Data: Automating Instance Setup
- 🔹 IAM Roles: Grant Permissions to EC2
- 🔹 Monitoring with CloudWatch (CPU, Memory Usage)
- 🔹 Backup and Recovery (Creating Snapshots & AMIs)
- 🔹 Deploying with CI/CD (GitHub Actions, Bitbucket Pipelines, or Jenkins)

# Learn AWS S3 (Cloud Storage)
##  Beginner Level (Basic File Storage)

- 🔹 Create an S3 Bucket
- 🔹 Upload, Download, and Delete Files in S3
- 🔹 Bucket Policies & Permissions (Public vs Private Access)
- 🔹 Use S3 to Store Static Assets (Images, Videos, Logs, etc.)
- 🔹 Enable Versioning (To Restore Old Files)
- 🔹 Use AWS SDK (Node.js, Python) to Upload/Download Files

## Intermediate Level (2-Year Experience Level)
- 🔹 Hosting a Static Website on S3
- 🔹 Setting Up Custom Domain with Route 53
- 🔹 Using S3 with CloudFront (CDN for Faster Delivery)
- 🔹 S3 Lifecycle Policies (Move Files to Glacier for Cost Savings)
- 🔹 S3 Presigned URLs (Secure Temporary Access)
- 🔹 Encrypting Data in S3 (SSE-S3, SSE-KMS)

---

# S3 Bucket
- Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance
  
## Benefits
1. Scalability
2. Durability and availability
3. Security and data protection
4. Lowest price and highest performance

Use cases
- Build a data lake
- Backup and restore critical data
- Archive data at the lowest cost
- Generative AI

# EC2 - (Elastic Compute Cloud)
- Amazon Elastic Compute Cloud (Amazon EC2) provides on-demand, scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 reduces hardware costs so you can develop and deploy applications faster.
<img width="896" alt="Screenshot 2025-04-28 at 10 48 16 PM" src="https://github.com/user-attachments/assets/c78516df-ebdd-4442-8013-647f2fda7e96" />

---

# ----------------------YOUTUBE AWS----------------------


# What is visualization?
Virtualization = Making a fake (virtual) computer inside your real computer. So If you have windows and want to work on different OS (linux or mac) then u need to create layer then above can run virtual machine (macOs, Linux, windows.) The layer which help to manage real and virtual machine caller hypervisor.

> [!Note]
> Host OS (Your real machine)

### Benefits of VM
- No need buy bew machine for work on different OS.
- No risk of any issues with your primary OS.
- Testing any app on different OS.

### Usecases of VM
- Cheap
- Reduce
- Easy backup using snapshot
- Easy recovery
  
### How Hypervisor Work?
- VirtualBox shares hardware resources with the Host OS.
(CPU, memory, storage, network, etc.)
- Each virtual machine gets its own virtual CPU, RAM, storage, and devices.
These are simulated by the hypervisor.
- Virtual machines are fully isolated.
Each VM runs independently and does not affect the host OS or other VMs.

### Type of Hypervisor.

1. Type1 (Bare Metal) - Is type ke hypervisor direct h/w par install hote hai. No any Host machine. (Used by cloud provider and enterprise servers)
2. Type2 (hosted) - Hostel Hypervisor because your virtual machine hosted on your real machine (Host OS)
   
# What is Cloud Computing?
- Cloud computing is the delivery of on-demand computing services over the internet on a pay-as-you-go basis.
- Cloud computing means storing and accessing data, applications, and services over the internet instead of your computer’s hard drive.
-  Instead of buying and maintaining physical servers and storage, you use someone else's servers (like AWS, Microsoft Azure, or Google Cloud) and access them online.
- <img width="618" height='500' alt="Screenshot 2025-04-27 at 4 57 16 PM" src="https://github.com/user-attachments/assets/40db001f-b632-4581-94c5-20f59ae324a8" />

### Key benefits of cloud computing:

- You pay only for what you use (no huge upfront cost).
- Cost Saving, Speed, productivity, Performance (secure and upgrade), Reliability.
- You can scale up or down easily
- You can access services from anywhere with internet
  
## Types of Cloud Computing:

<img width="703" height='500' alt="Screenshot 2025-04-27 at 5 00 44 PM" src="https://github.com/user-attachments/assets/62ff4f12-25c2-46bd-a5f4-a2b0d8ca598d" />
<img width="503" height='300' alt="Screenshot 2025-04-27 at 5 18 39 PM" src="https://github.com/user-attachments/assets/163418b7-9ffc-4b2f-8f3c-831870b7ede4" />
<img width="503" height='350' alt="Screenshot 2025-04-27 at 5 22 07 PM" src="https://github.com/user-attachments/assets/35cb9e61-82f4-4167-9019-ee910df35486" />
<img width="1138" alt="Screenshot 2025-04-27 at 5 24 50 PM" src="https://github.com/user-attachments/assets/262d5e63-ca6b-495a-948d-237f50a07a2a" />

## Cloude provider
- AWS (Amazon Web Service)
- Microsoft Azure
- IBM Cloud
- vmware
- Google Cloud platform
- Digital Ocean

## Lifecycle of a Cloud Computing Solution
1. Define the purpose: Understand the requirement of the business and determine what type of application to run on the cloud.
2. Define the hardware: (Lmbda, EC2, Elastic Container Service) Choose a cmpute service that will provide the rights support where you resize the compute capacity in the cloud to run application aprogram.
3. Define the Storage: (S3, EFS, Glacier) Choose a storage service where you can backup and archive your data over the internet.
4. Define the Network: (VPS, Route S3, Direct Connect) Define the network that securley deliver data, videos, application etc. with low latancy and high transfer speed.
5. Define Security: (IAM, KMS, Cognito): only authorized can access of AWS resoures.
6. Define Management processes and Tools: (Cloud Watch, Auto Scaling, Cloud Formation).
7. Testing the process: (CodeSTar, CodeBuild, Codepipeline) Verify the process using AWS developer tools.
8. Analytics: Athena, EMR, CloudSearch.
   
## Few feature commonly offered by cloud providers:
- Compute services
- storage services
- Database services
- Netwroking services
- Container services
- serverless computing
- Machine learning services
- Identity and Access Management
- Monitoring and Logging
- API Management
- Data analytics services
- Virtual Private Cloud
- CDN

# AWS (Amazon Web Service)
- AWS (Amazon Web Services) is a platform provided by Amazon that offers cloud services — like storage, servers, databases, security, and more — over the internet.
- 👉 Instead of buying your own computers or servers, you rent them from AWS and pay only for what you use.
- Need space to store files? 📦 → AWS gives you S3 (Storage service).
- Need a computer to run apps? 💻 → AWS gives you EC2 (Virtual server).
- Need a database to store users' data? 📚 → AWS gives you RDS (Database service).
- Want to run code without buying any server? ⚡ → AWS gives you Lambda (Serverless compute).

<img width="1437" height="500" alt="Screenshot 2025-04-27 at 5 52 05 PM" src="https://github.com/user-attachments/assets/c6cf8bf2-fae9-443d-a204-9db485212ef2" />
<img width="879" alt="Screenshot 2025-04-27 at 11 19 05 PM" src="https://github.com/user-attachments/assets/8b8c0d7f-730f-44d9-8b54-6880021ea2e2" />


### What make AWS so special?
Scalabilit, Global Reach, Reliability, Security.

### Popular Services Provided by AWS
Most popular ones inlcuded **EC2** for scalable compute capacity. **S3** for highly reliable storage, **RDS** for managed databases, **Lambda** for serverless computing, and **CloundFront** for delivery.

>[!Important]
>AWS Prasent Market (As per CRN report): Cloud Market Share Q2 2024| AWS: 32%| Microsoft: 23%| Google Cloud:12%

# IAM: 
- Free Service: IAM is offered at no additional cost
- Global Service
- Root account created by default, shouldn't be used or shared.

#### Create Users
You can create individual user accounts for people who need access to your AWS resources.

#### Assign Permissions
You can assign specific permissions to users, groups, or roles to control what actions they can perform on AWS services.

#### Create Groups
You can group users together and assign permissions to the group, making management easier for multiple users.

#### Create Roles
You can create roles to assign temporary permissions to AWS services or users. This is especially useful for securely managing permissions across different AWS resources.

#### Define Policies
You can create and attach custom policies to define fine-grained permissions for controlling access to AWS resources.

#### Manage Federated Access
IAM allows integration with external identity providers (such as Active Directory) for centralized management of user access across AWS.

## MFA (Multi Factor Authentication)
- MFA is a extra layer of security that require user to provide two or more forms of verification, like a password and a code from their phone, to access the account. (username + password + securitypassword).
- MFA must be active for root user.

# Practical - Create user and group user in IAM dahsboard- 
https://www.youtube.com/watch?v=N4sJj-SxX00 - 44min
```
https://253647676357.signin.aws.amazon.com/console
```

## Ways of accessing AWS 
- AWS Management Console (Web UI)
- AWS CLI (Command Line Interface): with the help of cli we an do automation thing like cron job.
- AWS SDKs & APIs (for programming languages)
- AWS CloudFormation / IaC (Infrastructure as Code)

<img width="759" height="601" alt="Screenshot 2025-12-01 at 6 36 24 PM" src="https://github.com/user-attachments/assets/c9d52ff6-b9ae-4014-92c5-30ea52bcf445" />

## AWS IAM Best Practices

- Avoid using the root account except for initial account setup.
- Add users to a group and assign permissions to the group instead of assigning directly to individuals.
- Use a strong password policy or enable MFA (Multi-Factor Authentication).
- Use Access Keys for CLI/SDK access instead of passwords.
- Never share Access Keys or passwords with anyone.
- Regularly audit permissions using the IAM Credential Report.

# AWS EC2 Service















