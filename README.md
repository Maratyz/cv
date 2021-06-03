# Marat (Yen-chih Chen)

_5-year experience of optimizing system performance, designing and developing process automation for delivery and data analysis. Extensive experience in AWS services including ECS/EKS, Redshift, EMR, and etc. with 6 AWS certificates including Professional Solution Architect and Network speciality. 7-year experience of enterprise customer support, issues diagnosis, and information visualization_

## Skills
### General
Linux, Network, Wireshark, AWS Services, Kubernetes
### Infrastructure as Code
Terraform, Cloudformation, CDK
### Configuration Management
Saltstack, Chef, Ansible, AWS System Manager
### Programming
Bash, Golang, Python, JavaScript/Nodejs, Git
### CI/CD
Github, Jenkins, Atlassian Bamboo and Bitbucket pipeline, GoCD
### Observability
Prometheus, Grafana, ELK, Nagions, Munin

## Work Experience
**SRE (Site Reliability Engineer) and DevOps Engineer** @ [Data Republic](https://www.datarepublic.com/) ( Sep. 2019 - Present ) <br>
* Cloud operation and management
  * Migration of services from kops cluster to EKS, including overall upgrade of infrastructer, terraform template development, CD pipeline update and testing. Resulting in SLA improvement to over 95%
  * Migration of self-managed Atlassian server to Atlassian Cloud. Having 3rd-party plugin blocks captured by a Go script
  * Helm2 to Helm3 migration and Kubernetese version update for over 50 services

* Observability
  * Developed user-behavior automation testing with Puppeteer for measuring SLA in a black-box approach. The test was also adapted to be run by AWS canary
  * Enabled development teams to define metric and alarm setup with Prometheus operator CRD
  * Build ELK stack to consume both application and infrastructure logs for analysis and dashboards

* Security
  * Build patch pipelines for AWS EC2 instances and AMI with AWS System Manager
  * Integrate log processing system with a vendor for [SOC2](https://www.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc2report.html) compliance

* Agility
  * Refactored legacy CI/CD Makefile scripts to be run on Github actions
  * Provisioned and managed the fleet of self-hosted Github action runners for deployment to any interanal environment

**Senior DevOps Engineer** @ [ELMO Software](https://elmosoftware.com.au/) ( Jan. 2018 - Sep. 2019 ) <br>
* CI/CD and Operation
  * Streamlining the development process, I built internal serverless tools which manages AWS resources, data obfuscation, streaming Cloudwatch logs and developedChef recipes, Apache/Nginx configuration, Dockerfiles, and Makefiles which simplified CI/CD configuration. 
  * Leveraged network and log analysis tools to investigate production and development issues
  * Operation tasks including integration setup, data summarisation for business decisions, and Website maintenance.

* System design and implementation
  * I designed and built infrastructure for over 10 projects including containerisation transition to ECS, API, Cloudfront cache, database migration with Redshift, and serverless applications with best practices including scalability, availability, nested stacks, and minimum permission.

**Project ManagementOperation/Optimization** @ [Groundhog Technology](https://www.ghtinc.com/) ( Oct. 2015 - Jul. 2017 ) <br>
The system served both telecommunication managers and engineers by providing nationwide radio signal distribution and trajectories of mobile users for business intelligence

* Operation
  * I reproduced and dissected issues, validated features and fixes, and deployed updates. I also automated processes such as data analysis and log collection, prepared internal environments for developers, and enhanced monitoring systems (Nagios and Munin)

* Optimization
  * To initialize DevOps culture and Agile practices, I built continuous integration flows which included compilation, deployment, and application testing. I also documented features and the system architecture in flow charts. Additionally, I took the performance responsibility across projects through identifying bottlenecks and analyzing resource usage

**Senior Field Application Engineer** @ [KLA](https://www.kla-tencor.com/) ( Nov. 2010 - Oct. 2015 )<br>
My daily tasks included issue resolution and delivery of an inspection product for integrated-chip defect detection. On a regular basis, I collaborated with the U.S. Headquarter in solving production issues

I achieved in resolving several business crises related to productivity and capability and in demonstrating next-generation products and information system for penetration, resulting in winning against a low-cost competitor and acquiring consequent purchase orders worth millions from TSMC, a global chip manufacturer with over 50% market share, supplying chips to Apple, Nvidia, Qualcomm, and major chip designers

## Projects
* Chrome Headless for PDF generation @ ELMO
It aimed to resolve the PDF issues of Phantom.js. It evolved from a single Node.js Lambda function to leverage ECS which supports larger file. In addition, it also adapt to the environment for supporting local development

* Cronjob Status Monitoring Dashboard @ ELMO
Serverless application in a poll-based model, provides the latest status of cronjob execution information and history results. Technology stacks include ReactJS (frontend) and Node.js (backend) on the top of AWS Serverless Services including CloudWatch Log, Lambda, DynamoDB, and Athena

## Education
**Master of Engineering (Materials Science and Engineering)** @ The University of New South Wales, NSW, Australia ( Sep. 2008 - Oct. 2010 ) <br>
Thesis: *Computational Fluid Dynamics for Simulating Flows in Furnace*

**Bachelor of Engineering** @ National Cheng Kung University, Tainan, Taiwan ( Sep. 2003 - Jun. 2007 ) <br>
GPA: 3.8 of 4, Rank: 3rd of 49

## Certificates
### Amazon Web Service (AWS) 
* AWS Solution Architect Professional Certificate (SAP)
* AWS DevOps Professional Certificate (DOP)
* AWS Advanced Networking (ANP)
* AWS Solution Architect Associate Certification (SAA)
* AWS Developer Associate Certification (DVA)
* AWS SysOps Administrator Certification (SOA)
