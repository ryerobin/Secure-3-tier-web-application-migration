# Secure-3-tier-web-application-migration
legacy database to move to cloud securely with no downtime
## Project-Overview
This project demonstrates execution and deployment of a secure, available 3-tier web architecture within the AWS cloud enviornment. It follows business logic constraints, keeping data storage isolated from public-facing internet traffic while maintaining availibility.
## Technical Architecture (AWS SAA)
* **VPC Infrastructure** Designed custom 3-tier-VPC across 2 Availability Zones for high resiliency.
* **Network Isolation** Created separate Public subnets and Private subnets.
* **Security Barriers** Created and configured custom security groups('web-sg' and db-sg'), mapping inbound rules to allow web tier traffic to communicate with MySQL RDS database, while blocking external communication.
* **Compute & Web Tier** Deployed an EC2 instance running Apache Web Server ('httpd') through Linux initialization

## Agile Execution Profile (CSM)
Managed the deployment using Agile methodologies and framework using the Github projects tab as a Scrum Board
* **Sprint Cycle** Broke down epics into executable user stories
* **Sprint Retrospective & Lessons Learned** Resovled network blocks regarding subnets and internet gateways.
