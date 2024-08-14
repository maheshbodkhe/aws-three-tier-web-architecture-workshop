### 🚀 Implementing a Scalable Three-Tier Web Architecture on AWS

![1](https://github.com/user-attachments/assets/c762f63c-3c8a-4c23-b704-ae0deb4f50f8)


**1️⃣ Introduction:**  
I’m thrilled to share my experience in implementing a robust and scalable three-tier web architecture on AWS. This project covered key aspects like networking, security, database deployment, load balancing, and auto-scaling.

**2️⃣ Configuration:**
- **Download Code from GitHub:** Cloned the repository containing all necessary dependencies.
- **S3 Bucket Creation:** Set up an S3 bucket to store application assets and configuration files.
- **IAM EC2 Instance Role Creation:** Established an IAM role for EC2 instances, granting secure access to AWS services.

![instances](https://github.com/user-attachments/assets/897500ea-e42d-454f-8fdd-38ff9a53e252)


**3️⃣ Networking and Security:**
- **VPC and Subnets:** Designed a VPC and subnets to segment the network, enhancing security.
- **Internet Connectivity:** Implemented an Internet Gateway to ensure internet access.
- **Routing Configuration:** Configured route tables for efficient traffic management.
- **NAT Gateway:** Deployed a NAT Gateway to allow secure internet access for instances in private subnets.
- **Security Groups:** Defined security groups based on the principle of least privilege to control instance traffic.

![VPC](https://github.com/user-attachments/assets/c6af6233-520d-40e2-b3e3-2705df6cb31b)


![Subnets](https://github.com/user-attachments/assets/63d7a6e8-bba4-4344-9e00-349510f1d7f2)


**4️⃣ Database Setup:**  
- **Subnet Groups:** Created subnet groups for high availability across multiple availability zones.
- **Database Deployment:** Leveraged Amazon Aurora for a scalable, managed database solution.

![RDS Database](https://github.com/user-attachments/assets/69868ce6-3051-48ab-84d1-5fb8e0b3d5ff)


**5️⃣ App Tier Instance Setup:**  
- **App Instance Deployment:** Launched EC2 instances for the application tier.
- **Connect to Instance:** Used Session Manager to configure the environment and deploy the application.
- **Configure Database:** Established secure and efficient database connections.
- **Configure App Instance:** Installed necessary dependencies and configured application settings.
- **Test App Tier:** Thoroughly tested the application tier for functionality and performance.

**6️⃣ Internal Load Balancing and Auto Scaling:**
- **App Tier AMI:** Created an AMI of the configured application instance for seamless scaling.
- **Target Group:** Established a target group to route traffic based on health checks.
- **Internal Load Balancer:** Deployed to distribute traffic evenly among app tier instances.
- **Launch Template:** Streamlined instance launches with predefined configurations.
- **Auto Scaling:** Dynamically adjusted the number of instances based on traffic patterns.

![Load Balancers](https://github.com/user-attachments/assets/61316b50-02a2-44a9-940d-65f6f17aa652)


**7️⃣ Web Tier Instance Setup:**
- **Update Config File:** Updated configuration files specifically for the web tier.
- **Web Instance Deployment:** Launched EC2 instances dedicated to the web tier.
- **Connect to Instance:** Used Session Manager to configure the environment and deploy web server software.
- **Configure Web Instance:** Optimized performance and ensured robust security settings.


![Last](https://github.com/user-attachments/assets/e5034435-5d5e-4a70-a556-dbe379d6ceaa)



![Last1](https://github.com/user-attachments/assets/39540691-cd16-4549-a59a-4708a31472d5)




---

This project highlights my ability to design and deploy scalable, secure, and efficient architectures on AWS. 🛠️🌐
