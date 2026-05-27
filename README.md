# AWS (Amazon Web Service)
- https://www.youtube.com/watch?v=-nCUSqugkRs&list=PLSJds3dF41Kzm6kANLxowm5dECkEbM8lr
- https://www.youtube.com/watch?v=XGcoeEyt2UM&list=PLEiEAq2VkUULlNtIFhEQHo8gacvme35rz&index=10
- This youtube Repo - https://www.youtube.com/watch?v=Ens8asZLomk&list=PL0tP8lerTbX3mKdZYfJwXcKf6SOfmQcgl&index=6

  
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

# --------------------YOUTUBE AWS--------------------


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

- **Create Users**
  - You can create individual user accounts for people who need access to your AWS resources.
- **Assign Permissions**
  - You can assign specific permissions to users, groups, or roles to control what actions they can perform on AWS services.
- **Create Groups**
  - You can group users together and assign permissions to the group, making management easier for multiple users.
- **Create Roles**
  - You can create roles to assign temporary permissions to AWS services or users. This is especially useful for securely managing permissions across different AWS resources.
- **Define Policies**
  - You can create and attach custom policies to define fine-grained permissions for controlling access to AWS resources.
- **Manage Federated Access**
  - IAM allows integration with external identity providers (such as Active Directory) for centralized management of user access across AWS.

## MFA (Multi Factor Authentication)
- MFA is a extra layer of security that require user to provide two or more forms of verification, like a password and a code from their phone, to access the account. (username + password + securitypassword).
- MFA must be active for root user.

# Practical - Create user and group user in IAM dahsboard- 
https://www.youtube.com/watch?v=N4sJj-SxX00 - 44min
```
https://253647676357.signin.aws.amazon.com/console
```

- Create User and add user in group from IAM services
- install aws in macOs - brew install awscli
- check aws cli install or not with enter command: aws
- You can see some aws message
<img width="680" height="350" alt="Screenshot 2026-05-26 at 7 43 02 AM" src="https://github.com/user-attachments/assets/6678b4d9-8989-4948-9940-1e44aca1b9a8" />


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

---

# AWS EC2 Service (Elastic Compute Service)

EC2 is a cloud service that provides resizable virtual server, called instances which you can use to run application. Exam: Buying and managing physical server AWS EC2 lets you rent virtual server inthe cloud. These virtual server called instances.
- EC2 server region specific hoti hai. Means jo bhi server, machine jis region me create hoga usi region me dikhega.
- Example: OS, RAM, Memory, Disk Space, CPU core.

### AWS EC2 – Key Configuration Options
- Instance Type: Select the hardware capacity (e.g., CPU, memory).
- AMI (Amazon Machine Image): Choose the operating system and software (Linux, macOS, Windows).
- Storage: Configure the type and size of storage (e.g., EBS volume).
- Security Groups: Set up firewall rules to control inbound/outbound traffic.
- Key Pair: Create or use an existing key pair for SSH access.
- Network Settings: Configure VPC, subnet, and assign public or private IP addresses.
- IAM Role: Attach an IAM role to grant permissions for accessing other AWS resources.
- User Data: Add scripts that will run automatically when the instance starts.
- Elastic IP: Optionally associate a static IP address for consistent public access.

### Step follow to create EC2 instance.
- Goto EC2 dashbaord
- Click Launched instanced
- Give instance name
- Application and os image select based on requirement for OS
- instances type - check cpu and memory capacity
- key pair login - create key pair (u will get one file will be downloaded in your sys)
- Network setting- which services u want to allow u have to handle in this section.
- configure storage
- click on launch instances finally your instance had created.

>[!Important]
>EC2 Instances based on region means in which region u will make instance u can get that specific region only.

## Security Groups:
Network firewall rules that controls inbound and outbound traffic for instances. Because of Security group u allow that on your instance which services u wanna to run or not u can handle via security group.
<img width="873" height="201" alt="Screenshot 2025-12-02 at 1 57 15 PM" src="https://github.com/user-attachments/assets/20a0ea95-ee0b-4ef9-8d08-449d62844e3e" />

- Goto EC2 dashboard
- go into Security
- see security group and inbound(request coming from outside on your server) and outbound rules.

>[!Important]
>Firewall related issue if you are getting means u have to check your security group.

### Important Point about Security group
- Region specific
- Only “Allow” rule (there is no “Deny” rule)
- All inbound traffic is blocked and outbound is allowed by default

- You define rules for specific:**
  - Protocols (like HTTP, HTTPS, SSH, etc.)
  - Port numbers (e.g., port 80 for HTTP, port 22 for SSH)
  - IP addresses or ranges: (e.g., allow traffic only from a specific IP or a range of IPs)

- If you allow incoming traffic on a specific port (e.g., port 80 for HTTP), then outgoing response traffic is automatically allowed without requiring an explicit outbound rule.

- Ypu can create your security group also: left sidebar > Network & Security > Security Groups

### Some ports you should be aware of:

1. HTTP (Port 80) – Unencrypted web traffic.
2. HTTPS (Port 443) – Encrypted web traffic (SSL/TLS).
3. SSH (Port 22) – Secure remote access to servers (Linux/Unix).
4. FTP (Port 21) – File Transfer Protocol (unsecured).
5. SFTP (Port 22) – Secure File Transfer Protocol.
6. SMTP (Port 25) – Simple Mail Transfer Protocol (email sending).
7. RDP (Port 3389) – Remote Desktop Protocol (Windows remote access).
8. MySQL (Port 3306) – MySQL database connections.
9. PostgreSQL (Port 5432) – PostgreSQL database connections.
10. DNS (Port 53) – Domain Name System (converts domain names to IP addresses).

# How to SSH into EC2 instance? (Accessing EC2 Instances in remote machine)
SSH allow you to connect and control/access a remote machine.

- goto EC2 dashboard
- goto instance and select created instance
- click right button connect
- click again down connect
- (Now you are able to see new terminal)
```
// commond enter one by one

cat /etc/os-release
free
df -h
```

>[!Note]
>putty is free ssh tool : (https://www.youtube.com/watch?v=Ens8asZLomk&list=PL0tP8lerTbX3mKdZYfJwXcKf6SOfmQcgl&index=6 (started from 24 min))

## Access SSH EC2 From Mac

>[!Important]
> Run this command, if necessary, to ensure your key is not publicly viewable: chmod 400 "mywebserver-key.pem"

- open terminal
- goto section where .pem file is there
- ls -ltr
- chmod 400 "mywebserver-key.pem"
- ssh -i "mywebserver-key.pem" ec2-user@ec2-3-237-40-100.compute-1.amazonaws.com

# EC2 Termination 
- select instances checkbox
- goto instance state above section
- Terminate (delete) Instance

>[!Important]
>Checking billing or cost: Go to searchbar and search billing > Billing and Cost Management > See cost summary.

# EC2 Types Example:
- Case 1: Small Website or Blog
  - Suitable Type: t3.micro or t3.small (General Purpose)
- Case 2: E-Commerce Application
  - Suitable Type: m5.large or m5.xlarge (General Purpose)
- Case 3: Real-Time Video Rendering and Streaming (Accelerated Computing: NVIDIA)
  - Instance Type: g5.12xlarge or g5.24xlarge
- Case 4: In-Memory Database for Real-Time Analytics (Memory Optimized)
  - Instance Type: r6g.16xlarge or x2idn.32xlarge (Memory Optimized)

# AWS EC2 Purchasing Options Comparison

| **Purchasing Option**  | **Best For**                                                                           | **Cost**                      | **Commitment**                       | **Flexibility**             |
| ---------------------- | -------------------------------------------------------------------------------------- | ----------------------------- | ------------------------------------ | --------------------------- |
| **On-Demand**          | Short-term, unpredictable workloads                                                    | High                          | None                                 | High                        |
| **Reserved Instances** | Long-term, steady workloads (1–3 years)                                                | Medium to Low (Up to 75% off) | 1 or 3 years                         | Low                         |
| **Spot Instances**     | Fault-tolerant, flexible tasks like batch jobs, big data, CI/CD, distributed computing | Very Low (Up to 90% off)      | None (but can be terminated anytime) | Medium (can be interrupted) |

<img width="600" height="325" alt="EC2" src="https://github.com/user-attachments/assets/3d2dfb2c-1a41-4b52-8382-1c93ddac1dca" />

---
# AWS EBS (Elastic Block Store) Resizing and backup storage
- In this topic u will learn how to increase instance storage size, how to add storage, additional disk add linux base instance, how to take backup and how to retrieve, snapshot share one region to another region etc.
- Jab ham instance create krte to usme option dikhta hai **configure storage** vhi hota hai in the form of EBS.
- AWS EBS is a cloud-based storage service that provides durable, high-performance block storage for use with Amazon EC2 instances.
- It works like a virtual hard drive, allowing you to store and access data even when your EC2 instances are stopped or terminated.

**For example,** if you're hosting a MySQL or PostgreSQL database, you need reliable, high-performance storage to handle frequent read/write operations.
EBS provides persistent, fast storage that ensures your data is saved even if the EC2 instance is stopped or restarted, making it ideal for database workloads.

### ⭐ Important Points About EBS (Elastic Block Store)

- Region & AZ specific
- Built-in Redundancy
  - EBS volumes are automatically replicated within the same AZ.
  - This prevents data loss due to hardware failures.
- Different Volume Types
  - gp2 / gp3, io1 / io2, st1, sc1.
- Allows Encryption & Snapshots for Backup
- Scalable

>[!Note]
> If instance is terminated then volume is also deleted means what the storage of that particular instance got deleted by default. If u don't want to delete storage when instance is deleted then when u are creating instance - storage -> Delete on termination -> select No.

## Create EBS Volume (Console)
1. Open AWS Console → EC2 → Elastic Block Store → Volumes.
2. Click Create volume.
3. Choose Volume type (gp3, gp2, io1, etc.), Size (GiB), and Availability Zone (pick the AZ of your instance).
4. Optionally add tags (e.g., Name=MyVolume).
5. Click Create volume.

## Attach Volume to an Instance (Console)
1. In EC2 Console → Volumes, select your new volume.
2. Click Actions → Attach volume.
3. Choose the Instance from dropdown and set the Device name (suggested /dev/sdf or /dev/xvdf).
4. Click Attach.
5. How to check that volume got attached or not : goto running instances > storage > scroll and you will see EBS (block storage)

## Modify size EBS volumne
- select instances
- goto action above
- modify volume based on req
- click modify button

## Delete and Detach Volumwe
- Step-1: Go to AWS Console → EC2 → Elastic Block Store → Volumes
- Step-2: Select the volume you want to detach.
- Step-3: Click Actions → Detach volume/Delete Volume
- Step-4: Confirm Detach/Delete

## EBS Snapshot(backup of storage) 
- ✔ Sidebar Go to EC2 → Volumes
- ✔ Select Volume → Create Snapshot (take care after creating snapshot status completed)
- ✔ Monitor in Snapshots section
- ✔ Optional: copy to another region
- ✔ Optional: schedule automatic backups

## EBS Snapshot (Copy to Other region)
1. Create a Snapshot
2. Select Snapshot to Copy
3. Choose the Destination Region
4. Click Copy Snapshot
5. Switch AWS Console region (top-right)
6. Go to EC2 → Snapshots (you will see a snapshot with status pending → completed.)

## EBS Lifecycle Manager
EBS Lifecycle Manager is an AWS service that automatically creates, retains, and deletes EBS snapshots based on rules you define.

- Automate backups
- Reduce manual snapshot management
- Save storage costs
- Maintain compliance by keeping backups for the right amount of time

>[!Important]
> Db ka database ka monthly yearly weekly backup automatically lega.
  EBS -> Lifecycle Manager

>[!Note]
> Agar Snapshot delete kr dete hai to recycle bin ka optin rhata hai apko thoda billing krke wha se rollback kr skate hai apne resources ko.

---

# AWS AMI(AMazon Machine Image) Service
An Amazon Machine Image (AMI) is a pre-configured template that provides the necessary information to launch an EC2 instance in AWS.

- With an AMI, you can launch new EC2 instances with a consistent, predefined configuration.
- You can also create custom AMIs to include specific software or settings, allowing for quick replication of environments.
  
**It includes:**
- Operating system (e.g., Linux, Windows)
- Application server (e.g., Apache, Nginx)
- Pre-installed software and configurations

>[!Note]
> You will see how to deploy website application in production. for static website.

### Console (GUI) — quick steps
1. Open AWS Console → EC2 → Instances.
2. Select the Windows instance you want to image.
3. Click Actions → Image and templates → Create image.
4. Fill Image name and optional Description.
5. (Optional) Review Instance volumes — add or remove volumes to include in the AMI.
6. Choose whether to No reboot the instance (unchecked = AWS will reboot the instance to ensure file-system consistency; for Windows leaving reboot enabled is recommended).
7. (Optional) Add tags for the new AMI (e.g., Name=MyWindowsAMI).
8. Click Create image.
9. Go to EC2 → AMIs (same region) and wait — status will be pending then available.
10. When available, you can Launch a new instance from the AMI (Actions → Launch) or Share/Copy it to another region.

## Types of AMI
| **Type of AMI**                  | **Description**                                                                                                                   |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Public AMIs**                  | Available to all AWS users. Useful for basic use cases like popular operating systems (e.g., Ubuntu, CentOS).                     |
| **Private AMIs**                 | Created by a user and only available within that account or shared with specific accounts.                                        |
| **Paid AMIs / Marketplace AMIs** | Provided by third parties through AWS Marketplace, offering software like databases, web servers, or pre-configured environments. |

### Use Case of Paid AMIs Benefits:
- 🔹 Rapid Deployment:
  - The LAMP stack is pre-configured, eliminating the need to manually install and configure Apache, MySQL, and PHP.
- 🔹 Scalability and Load Balancing:
  - Running on AWS enables quick scaling to match website traffic, while Elastic Load Balancer helps distribute requests efficiently.
- 🔹 Cost Efficiency:
  - You only pay for the infrastructure and the software according to your usage.
 
## Why creating template instance?
Instead of creating multiple instance again and again with same specification we can create templete instance so we can save our time.

### Key Differences: Create Launch Template vs Create Images (AMI)
| **Feature**     | **Create Launch Template**                                                        | **Create Image (AMI)**                                         |
| --------------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **Purpose**     | Create a reusable blueprint for launching instances                               | Create a custom AMI snapshot of an instance                    |
| **Content**     | Contains configuration settings (e.g., AMI, instance type, security groups, etc.) | Captures OS, applications, configurations, and data            |
| **Reusability** | Used repeatedly to launch new instances in a consistent way                       | Used to create new instances that replicate the captured image |
| **Use Cases**   | Auto Scaling, Spot Instances, Standardizing instance settings                     | Backup, Replication, Migrating instances to another region     |
| **Versioning**  | Can have multiple versions for different configurations                           | Typically, an AMI is a point-in-time capture of an instance    |

>[!Important]
> Summary: Yes, all installed applications, configuration settings, environment variables, network configurations, DNS settings, users, and firewall settings will be included in the AMI.
An AMI is essentially a complete snapshot of the instance at the point in time you created the image, allowing you to replicate the exact state of that server, including all software, configuration, and operating system-level changes.
When you create an EC2 instance from this AMI, it will boot up as if it were an exact clone of the original, with all installed software and settings intact.

### EC2 Image Builder
It is pipeline of Building, testing and deployment and it's free of cost.

<img width="753" height="408" alt="Screenshot 2025-12-03 at 11 47 07 PM" src="https://github.com/user-attachments/assets/e55d824f-5084-449d-89aa-cc1d1c8360d4" />

**Usr Cases:**
- Automated Build and maintenance of images.
- Imcrease image quality.
- Manage image compliance for your industry standard.

---
# ELB(Elastic Load Balancing) & ASG(Auto Scaling Group)





















