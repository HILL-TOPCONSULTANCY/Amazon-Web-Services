Here are the steps to create a Free Tier AWS account:

### Step 1: Go to the AWS Website
1. Open your web browser and go to the [AWS Free Tier](https://aws.amazon.com/free) page.
2. Click the **"Create a Free Account"** button.

### Step 2: Sign Up for AWS
1. **Enter your email address**: You will need a valid email address that will be associated with your AWS account.
2. **Create a password**: Choose a strong password.
3. **Account name**: Enter a unique name for your AWS account (e.g., your personal name or business name).
4. Click on **"Continue"**.

### Step 3: Contact Information
1. **Select account type**: Choose between a **Personal** or **Professional** account. For most users, select **Personal**.
2. **Fill in your personal information**: Enter your full name, phone number, and country/region.
3. **Address details**: Fill in your address.
4. **Agree to the AWS Customer Agreement** and click **"Create Account and Continue"**.

### Step 4: Payment Information
1. **Add your payment details**: You need to provide a valid credit or debit card, even for the Free Tier account. AWS uses this information to verify your identity and ensure compliance with the free usage limits.
2. AWS will place a small authorization charge (typically $1) on your card for verification purposes, which will be refunded.
3. Once you've added your payment details, click **"Verify and Add"**.

### Step 5: Identity Verification
1. **Phone verification**: AWS will require you to verify your identity via phone. Choose either a **text message (SMS)** or **voice call**.
2. Enter your phone number and click **"Send SMS"** or **"Call me now"**.
3. You will receive a PIN code. Enter the code to complete the verification.

### Step 6: Select a Support Plan
1. AWS offers several support plans, including **Basic (Free)**, **Developer**, **Business**, and **Enterprise**. For the Free Tier, select **Basic Support – Free**.
2. Click **"Continue"**.

### Step 7: Confirmation
1. You will see a confirmation message saying your account is being created.
2. Shortly after, you will receive a confirmation email from AWS. Follow any instructions in the email to finalize your account setup.

### Step 8: Sign In to Your AWS Account
1. After your account is confirmed, you can sign in to the AWS Management Console using the email and password you provided during registration.
2. Go to [AWS Console Login](https://aws.amazon.com/console/) and enter your credentials.

### Step 9: Access the Free Tier Services
1. Once logged in, you can explore the AWS Free Tier services. AWS offers 12 months of free usage for several popular services like **Amazon EC2**, **Amazon S3**, and **Amazon RDS**, among others.
2. Use the **Free Tier Dashboard** in the AWS Console to track your Free Tier usage and ensure you stay within the free usage limits.

---

### Important Notes:
- **Credit Card Requirement**: Although AWS Free Tier is free for many services, you are required to provide credit card details to prevent misuse and for any usage beyond the Free Tier limits.
- **Monitoring Usage**: Make sure to monitor your usage, as exceeding the Free Tier limits can lead to charges.
- **Free Tier Limits**: The AWS Free Tier provides 12 months of free usage for new customers and includes 750 hours per month of Amazon EC2 usage, 5 GB of Amazon S3 storage, and other resources.

By following these steps, you will have successfully created an AWS Free Tier account and can start exploring AWS services at no cost within the limits provided.
---
# What is Amazon EC2?

+ ✔ Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud.
+ ✔ Access reliable, scalable infrastructure on demand. Scale capacity within minutes with SLA commitment of 99.99% availability.
+ ✔ Provide secure compute for your applications. Security is built into the foundation of Amazon EC2 with the AWS Nitro System.
+ ✔ Optimize performance and cost with flexible options like AWS Graviton-based instances, Amazon EC2 Spot instances, and AWS Savings Plans.

## Use cases
1. Run Cloud-Native and Enterprise Applications
+ Deliver secure, reliable, high-performance, and cost-effective compute infrastructure to meet demanding business needs.
2. Scale for HPC Applications
+ Access the on-demand infrastructure and capacity you need to run HPC applications faster and cost-effectively.

## Features
+ Multiple Locations
Amazon EC2 provides the ability to place instances in multiple locations. Amazon EC2 locations are composed of Regions and Availability Zones.
Availability Zones are distinct locations that are engineered to be insulated from failures in other Availability Zones and provide inexpensive, 
low latency network connectivity to other Availability Zones in the same Region. By launching instances in separate Availability Zones,
you can protect your applications from failure of a single location. Regions consist of one or more Availability Zones and are geographically dispersed. 
The Amazon EC2 Service Level Agreement commitment is 99.99% availability for each Amazon EC2 Region. Please refer to Regional Products and Services for more details of our product and service availability by region.

## Storage
+ Optimal storage for every workload
Different Amazon EC2 workloads can have vastly different storage requirements. Amazon cloud storage is reliable, scalable, and secure storage for your data.
- Amazon Elastic Block Store (Amazon EBS) is an easy to use, high performance block storage.
- Amazon Simple Storage Service (Amazon S3) is object storage with industry-leading scalability, availability, and security.
- For file storage, Amazon offers a complete portfolio including Amazon EFS which provides simple, scalable, persistent, fully managed cloud file storage for shared access.
- Amazon FSx file storage offerings deliver fully managed, cost-effective file storage with the capabilities and performance of popular commercial and open-source file systems.

## Networking
+ High Packet-Per-Second Performance and Low Latency with Enhanced Networking
Enhanced Networking enables you to get significantly higher packet per second (PPS) performance, lower network jitter and lower latencies. This feature uses a network virtualization stack that provides
higher I/O performance and lower CPU utilization compared to traditional implementations.

## Operating Systems and Software
Amazon Machine Images (AMIs) are preconfigured with an ever-growing list of operating systems, including Microsoft Windows and Linux distributions such as Amazon Linux 2,
Ubuntu, Red Hat Enterprise Linux, CentOS, SUSE and Debian. We work with our partners and community to provide you with the most choice possible. 
The AWS Marketplace features a wide selection of commercial and free software from well-known vendors, designed to run on your EC2 instances.
## Maintenance
AWS regularly performs routine hardware, software, power, and network maintenance with minimal disruption across all EC2 instance types.

## PRICING
### AWS Free Tier
As part of the AWS Free Tier, you can get started with EC2 for free. This includes 750 hours of Linux and Windows t2.micro instances (t3.micro for the regions in which t2.micro is unavailable), each month for one year. To stay within the Free Tier, use only EC2 Micro instances. 

AWS Free Tier also includes 750 hours of of public IPv4 addresses free per month when used on EC2 instances. There is no restriction of instance type here.

## Purchase models
**On-Demand**
* On-Demand Instances let you pay for compute capacity by the hour or second with no long-term commitments. This frees you from the costs and complexities of planning, purchasing, and maintaining hardware and transforms what are commonly large fixed costs into much smaller variable costs.

**+ On-Demand Instances are recommended for:**
+ Users that prefer the low cost and flexibility of EC2 without any upfront payment or long-term commitment
+ Applications with short-term, spiky, or unpredictable workloads that cannot be interrupted
+ Applications being developed or tested on EC2 for the first time

**Savings Plans**
Savings Plans is a flexible pricing model that can help you reduce your bill by up to 72% compared to On-Demand prices, in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a 1- or 3-year term.

AWS offers three types of Savings Plans: Compute Savings Plans, EC2 Instance Savings Plans, and Amazon SageMaker Savings Plans. Compute Savings Plans apply to usage across Amazon EC2, AWS Lambda, and AWS Fargate.

**+ Savings Plans are recommended for:**
+ Committed and steady-state usage
+ Users looking to take advantage of the latest compute offerings while continuing to save money

**Amazon EC2 Spot Instances**
Amazon EC2 Spot Instances let you take advantage of unused EC2 capacity in the AWS cloud and are available at a discount of up to 90% compared to On-Demand prices.

**+ Spot Instances are recommended for:**
+ Fault tolerant or stateless workloads
+ Applications that can run on heterogeneous hardware
+ Applications that have flexible start and end times

## Reserved or dedicated capacity
**On-Demand Capacity Reservations**
On-Demand Capacity Reservations enable you to reserve compute capacity for your EC2 instances in a specific Availability Zone for any duration. Capacity reservations mitigate against the risk of being unable to get 
On-Demand capacity in case of capacity constraints and ensure that you always have access to EC2 capacity when you need it, for as long as you need it.

**+ On-Demand Capacity Reservations are recommended for:**
+ Business-critical events or workloads that require capacity assurance
+ Workloads that need to meet regulatory requirements for high availability
+ Disaster recovery

**Amazon EC2 Capacity Blocks for ML**
With Amazon EC2 Capacity Blocks for ML, you can easily reserve GPU instances for a future date to run your machine learning (ML) workloads. You pay only for the amount of compute time that you need, with no long-term commitment.

**+ EC2 Capacity Blocks are recommended for:**
+ Training and fine-tuning ML models
+ Running experiments and building prototypes
+ Planning for future surges in demand for ML applications

**Dedicated Hosts**
A Dedicated Host is a physical EC2 server fully dedicated for your use. Dedicated Hosts can help you reduce costs by allowing you to use your existing server-bound software licenses, including Windows Server, SQL Server, a
nd SUSE Linux Enterprise Server (subject to your license terms). Dedicated Hosts can be purchased On-Demand (hourly) or can be purchased as part of Savings Plans.

**+ Dedicated Hosts are recommended for:**
+ Users looking to save money on licensing costs
+ Workloads that need to run on dedicated physical servers
+ Users looking to offload host maintenance onto AWS, while controlling their maintenance event schedules to suit their business’s operational needs

## Instance Types:

**General Purpose**
General purpose instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads. 
These instances are ideal for applications that use these resources in equal proportions such as web servers and code repositories. 

**Compute Optimized**
Compute Optimized instances are ideal for compute bound applications that benefit from high performance processors. Instances belonging to this category are well suited for batch processing workloads, media transcoding, 
high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intensive applications.

+ AWS BUDGET
+ EC2 with User Data for a website
+ Security Groups
+ AUTO-SCALING GROUP & POLICY- target tracking policy

+ LOAD BALANCER
+ SSH
+ Public and Private IP (ELASTIC IP)

# AWS AUTO-SCALING GROUP
- In real rile, the load of your website and application can change
- In the cloud, it is possible to create anf get rid of servers so easily.
  **The Goal of ASG**
  - Scale outy to match increading load
  - Scale in to match decreasing load
  - Ensure you have the desired number of instances running max and min
  - Automaticallyb register new instances to LB
  - Health checks and destroy unhealthy and create new ones
 
- CREATING ASG
- Therre is horizontal and vertical scaling
  Name
  Launch Template
  AMI
  Instance Type, key pair, SG   Userdata VPC and Subnets, group size
  Change desired to see scaling
Scale based on CPU, Request Count Per Target, Average Network

**Saling Policy**
-Predictive Scaling
- Machine Learning Driven (Dynamic)

 ```sh
sudo amazon-linux-extras install epel -y
sudo yum install stress -y
stress -c 4
```
  
  **ASSIGNMENT:**_

 # EC2 PROJECTS
'[PROJECT REPO](https://github.com/HILL-TOPCONSULTANCY/ApplicationLB-App)
 1. APPLICATION DEPLOYMENT with user data
 2. APPLICATION LOAD BALANCER
---
[LAMP PROJECT](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html?refid=4b76a70e-625f-48c4-b90e-cc5a1eadff15)
4. Install an Apache web server with PHP and MySQL support on your Amazon Linux instance
