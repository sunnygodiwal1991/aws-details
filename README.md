## blue

### AWS services list
```
https://www.hava.io/blog/aws-services-list
```

### Details
```
## Penetration testing
- Nessus
- Burpsuit
- Nmap
- Gaurd duty
- Cloud Watch

check with udemy
    - Nessus Scanner: Network Scanning from Beginner to Advanced!
```

### Penetration steps follow by DevOps or tester

* Step 1: Information Gathering (Reconnaissance): Collect information about the target system through public sources (OSINT), such as domain names, IP addresses, and other publicly available data.
* Step 2: Vulnerability Scanning: Use tools to scan for known vulnerabilities in the target system (e.g., Nessus, OpenVAS).
Port Scanning: Identify open ports and services on the target system using tools like Nmap.
Service Enumeration: Identify detailed information about the services running on the open ports (e.g., versions, configurations).
* Step 3: Vulnerability Exploitation: Attempt to exploit the vulnerabilities identified in the scanning phase to gain unauthorized access to the system. Gain Access: This can involve exploiting weaknesses in software, misconfigurations, or weak passwords to gain access.
* Step 4: Privilege Escalation: Once access is gained, attempt to escalate privileges (e.g., gaining admin/root access). Maintain Access: Set up backdoors or other methods to maintain persistent access.
* Step 5: Data Exfiltration Test the ability to access, alter, or exfiltrate sensitive data.
* Step 6: Document Findings: Record the vulnerabilities discovered, how they were exploited, and the potential impact. Risk Assessment: Analyze the severity of the vulnerabilities and provide recommendations for mitigation.
* Steps 7: Provide a detailed report to the client, including the penetration test results, evidence of exploitation, and suggestions for improving security.
* Step 8: Fix Vulnerabilities: Work with the client to address the identified vulnerabilities. Retesting: Conduct retesting to ensure that the vulnerabilities have been properly mitigated.

<br>

## Amazon GuardDuty
Amazon GuardDuty is a security guard for our AWS account, always keeping an eye out for anything unusual or harmful. It uses smart technology to detect threats, such as hackers or suspicious activity, and sends you alerts so you can take action quickly. It uses machine learning, AI, and threat intelligence to identify and assess security risks.

* It support Threat Detection & identify suspicious activity in our AWS environment, like if someone tries to log in using credentials.
Example: GuardDuty alerts you if someone is trying to access our account from a strange location.

* It identifies Malicious IP and Domain Detection when our resources communicate with known bad IPs or websites.
Example: GuardDuty warns you if our system is trying to connect to a hacker's server.

* It looks for unusual behavior, like a sudden spike in activity that doesn't match normal patterns.
Example: GuardDuty notifies you if there’s a sudden surge of activity from a user who usually doesn’t log in much.

* It monitors IAM user behavior monitoring, how your users and roles behave to detect any signs of compromised credentials.
Example: GuardDuty alerts you if a user suddenly starts accessing parts of your system they don't usually touch.

* It also analyzes VPC Flow Log to traffic between our AWS services to spot any unusual or unauthorized connections.
Example: GuardDuty tells you if there’s suspicious traffic happening between servers that shouldn’t be talking to each other.

* It looks for signs that data might be leaving our S3 storage without permission.
Example: GuardDuty alerts you if a large amount of data is being downloaded from our S3 bucket unexpectedly.

<br>

## Amazon CloudWatch
Amazon CloudWatch is a service that helps you monitor and track how your AWS resources are performing. It keeps an eye on things like server health and usage, and alerts you if something goes wrong.

* CloudWatch helps to monitor AWS Resources & track the performance and health of AWS services like EC2, RDS, and Lambda.
Example: You can monitor server CPU usage to ensure it's not overloaded.

* It allows you to set alarms for specific metrics, notifying you when thresholds are crossed.
Example: CloudWatch can alert you if your website's traffic exceeds a certain limit, so you can scale up resources.

* CloudWatch collects and stores logs from AWS services, making it easier to track errors or issues in your applications.
Example: You can check logs to find out why an app crashed or identify security issues.

* CloudWatch can trigger automatic scaling of resources based on usage metrics, such as increasing server capacity when traffic spikes.
Example: If your website gets a sudden surge of visitors, CloudWatch can automatically add more servers to handle the load.

* CloudWatch can help track usage and costs, giving insights into how much resources are being used.
Example: You can set alerts if your cloud usage is approaching your budget limits to avoid overspending.

<br>

## Network Services
* Amazon VPC (Virtual Private Cloud): Create and manage your own private network within AWS.
* AWS Direct Connect: Establish a dedicated network connection between your on-premises data center and AWS.
* AWS VPN (Virtual Private Network): Securely connect your on-premises network to AWS over the internet.
* AWS Transit Gateway: Connect multiple VPCs and on-premises networks through a central hub.
* Amazon Route 53: Scalable domain name system (DNS) service to route user requests to appropriate AWS resources.
* AWS Global Accelerator: Improve the availability and performance of your global applications by routing traffic through optimal AWS edge locations.
* Elastic Load Balancing (ELB): Distribute incoming traffic across multiple targets, like EC2 instances.
* Amazon CloudFront: Content delivery network (CDN) for fast distribution of content to users worldwide.
* AWS App Mesh: Service mesh to monitor and control microservices applications' communication.

<br>

## Security Services
* AWS Identity and Access Management (IAM): Manage access to AWS resources and services securely.
* Amazon GuardDuty: Threat detection service to monitor AWS accounts and workloads for malicious activity.
* AWS Shield: DDoS protection service to safeguard your applications from denial-of-service attacks.
* AWS WAF (Web Application Firewall): Protect your web applications from common web exploits and threats.
* AWS Key Management Service (KMS): Create and control encryption keys to secure data.
* AWS Secrets Manager: Securely manage and rotate credentials and API keys.
* AWS Certificate Manager (ACM): Manage SSL/TLS certificates for secure website connections.
* AWS Macie: Data security and privacy service to discover, classify, and protect sensitive data.
* AWS CloudHSM: Hardware security module (HSM) to manage encryption keys and other security functions.
* AWS Security Hub: Centralized view for security alerts and security posture across AWS accounts.
* AWS Systems Manager (Session Manager): Securely manage and access EC2 instances without needing SSH access.
* Amazon Inspector: Automated security assessment service to help identify vulnerabilities in your AWS resources.
* Amazon Cognito: Manage user sign-up, sign-in, and access control for applications.
* AWS Config: Track AWS resource configurations and changes to ensure compliance and governance.
* AWS Firewall Manager: Simplify the management of firewall rules across your organization.

<br>
<br>

## AWS Analytics
```
Amazon Athena - Serverless Query S3 using SQL
Amazon Cloudsearch - Search Solution for Websites and Apps
Amazon Elastic Search - Deploy and run ElasticSearch
Amazon EMR - Big Data Platform and Analysis
Amazon Kenesis - Real time streaming data capture and analysis
Amazon Redshift - Data Warehouse Service
Amazon QuickSight - Serverless ML BI Dashboards
Amazon Data Exchange - Subscribe to 3rd Party Data Sets
Amazon Data Pipeline - Transfer and process data
Amazon Glue - Data discovery, enrichment and transfer
AWS Lake Formation - Set up Data Lakes quickly
```

## AWS Application Integration Services
```
AWS Step Functions - Serverless Function Orchestration
Amazon AppFlow - Integrate 3rd party app data
Amazon EventBridge - Serverless Event Bus
Amazon MQ - Message Broker Service for Apache/Rabbit MQ
Amazon SNS - Simple Notification Messaging System
Amazon SQS - Simple Queue Service Inter Component Messaging
Amazon AppSync - GraphQL API Service
```

## AWS Cost Management Services
```
AWS Cost Explorer - Visualize and manage AWS costs
AWS Budgets - Service to set and monitor usage budgets
AWS Cost and Usage Report - reporting to analyse AWS usage
```

## BlockChain
```
Amazon Managed Blockchain - Hyperledger & Ethereum Service
Quantum Ledger DB (QLDB) - Fully managed financial ledger db
AWS Compute Services
Amazon EC2 - Secure, resizable Compute Instances (400+)
EC2 Autoscaling - Automated compute capacity scaling
Amazon LightSail - Easy virtual private server instances
Elastic Beanstalk - Deploy & scale web apps (Java/Ruby/etc)
Lambda - Serverless Compute Functions
```

## Container Services
```
ECR - Elastic Container Registry
ECS - Elastic Container Service to deploy/manage clusters & tasks
EKS - Elastic Kubernetes Service
AWS Copilot - CLI to launch and manage containers
AWS Fargate - Serverless Compute Engine for ECS/EKS Containers
```

## AWS Database Services
```
Aurora - MySQL and PostgreSQL compatible database service
DynamoDB - KeyValue / Document Database
Elasticache - Scalable in-memory database
Neptune - Graph database for highly connected data sets
Amazon RDS - Relational Database (MySQL/Postgres/Maria etc)
Timestream - Serverless time series db for IoT
```

## AWS Network and Content Delivery
```
AWS VPC - logically isolated virtual private clouds
API Gateway - Create and manage APIs
CloudFront - Fast content delivery network CDN service
Route53 - fast DNS service
AWS PrivateLink - Connect your on-prem network to AWS
AWS App Mesh - Service Mesh for inter compute instance comms
AWS CloudMap - Resource discovery for app usage
AWS Direct Connect - Fast connection from your equipment to AWS
Global Accellerator - App traffic routing over the AWS network
AWS Transit Gateway - Centralised VPC and on prem connectivity
Elastic Load Balancing - Service to evenly distribute network traffic
```

## AWS Storage
```
Amazon S3 - Widely used AWS object storage service
EBS - Elastic Block Store, Persistent block
EFS - Serverless Elastic File System
FSx for Lustre - High performance file storage using Lustre
FSx for Windows File System - AWS Windows file system
S3 Glacier - Durable low cost archival storage
AWS Backup - Policy driven data protection
AWS Snow - Edge infrastructure for storage and compute
AWS Storage Gateway - Hybrid on prem AWS storage
CloudEndure - Disaster recovery service
```
## ===================== END =====================
