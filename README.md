# Marat (Yen-chih Chen)

_5-year experience of optimizing system performance from Linux cpu binding to Database indexing, designing and developing process automation for delivery and for data analysis. Extensive experience in AWS services including ECS/EKS, Redshift, EMR, and etc. with 6 AWS certificates listed below. 7-year experience of enterprise customer support, issues diagnosis, and information visualization_

## Skills
### General
Linux, Network, Wireshark, AWS Services, Kubernetes
### Infrastructure as Code
Terraform, Cloudformation, CDK
### Configuration Management
SaltStack, Chef, Ansible, AWS System Manager
### Programming
Bash, Golang, Python, JavaScript/Nodejs, Git
### CI/CD
Github, Jenkins, Atlassian Bamboo and Bitbucket pipeline, GoCD
### Observability
Prometheus, Grafana, ELK, Nagions, Munin

## Work Experience
**SRE (Site Reliability Engineer) and DevOps Engineer** @ [Data Republic](https://www.datarepublic.com/) ( Sep. 2019 - Present ) <br>
Platform to share and match data securely, and provide sandboxes to analyse data
* Cloud operation and management: improving SLA to over 95%, upgrading infrastructures, and resolving production incidents
  * Migrated services from kops cluster to EKS, including overall upgrade of infrastructure, terraform template development, CD pipeline update and testing 
  * Refactored Helm charts for Helm2 to Helm3 migration 
  * Upgraded Kubernetes clusters across multiple versions for over 50 services
  * Contributed in incidents such as disaster recovery, data restoration, and long downtime during midnight

* Observability: automating user experience monitoring and shortening response time toward issue analysis
  * Developed user-behavior automation testing with Puppeteer for measuring SLA in a black-box approach. The test was also adapted to be run by AWS canary
  * Instructed development teams to define metric and alarm setup with Prometheus operator CRD
  * Built ELK stack to consume both application and infrastructure logs for faster analysis in a single place

* Security: building patching pipeline, working in SOC compliance, and validating product security
  * Built patch pipelines for AWS EC2 instances and AMI with AWS System Manager
  * Integrated log processing system with a vendor for [SOC2](https://www.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc2report.html) compliance
  * Supported validation on product security by intercepting and decrypting SSL traffic with proxy 

* Agility: migrating pipelines and improving their throughput by 30%
  * Refactored legacy CI/CD Makefile scripts to be run on Github actions, shortening bulid and testing time by caching
  * Provisioned and managed the auto-scaling fleet of self-hosted Github action runners for build and deployment to any internal environment

**Senior DevOps Engineer** @ [ELMO Software](https://elmosoftware.com.au/) ( Jan. 2018 - Sep. 2019 ) <br>
Multi-tenant system for small-medium companies to manager human resources, training, payroll, and performance management
* CI/CD and Operation: automating internal manual processes and constructing pipelines from scratch
  * Streamlined the development process, I built internal serverless tools which manages AWS resources, data obfuscation, streaming Cloudwatch logs and developed Chef recipes, Apache/Nginx configuration, Dockerfiles, and Makefiles which simplified CI/CD configuration. 
  * Leveraged network and log analysis tools to investigate production and development issues
  * Operation tasks including integration setup, data analysis for business decisions, and Website maintenance.

* System design and implementation: transforming production into cloud-native ones
  * I designed and built infrastructure for over 10 projects including containerisation with ECS, API Gateway, database migration with Redshift, and serverless applications with best practices including scalability, availability, nested stacks, and minimum permission.

**Project ManagementOperation/Optimization** @ [Groundhog Technology](https://www.ghtinc.com/) ( Oct. 2015 - Jul. 2017 ) <br>
The system processing nationwide radio signal distribution and trajectories of mobile users for business intelligence and mobile network optimisation

* Operation
  * I reproduced and dissected issues, validated features and fixes, and deployed updates. I also automated processes such as data analysis and log collection, prepared internal environments for developers, and enhanced monitoring systems (Nagios and Munin)

* Optimization
  * To initialize DevOps culture and Agile practices, I built continuous integration flows which included compilation, deployment, and application testing. I also documented features and the system architecture in flow charts. Additionally, I took the performance responsibility across projects through identifying bottlenecks and analyzing resource usage

**Senior Field Application Engineer** @ [KLA](https://www.kla-tencor.com/) ( Nov. 2010 - Oct. 2015 )<br>
KLA manufactured semi-conductor inspection tools for advance chip manufacturing processes

My daily tasks included issue resolution and delivery of an inspection product for integrated-chip defect detection. On a regular basis, I collaborated with the U.S. Headquarter in solving production issues

I achieved in resolving several business crises related to productivity and capability and in demonstrating next-generation products and information system for penetration, resulting in winning against a low-cost competitor and acquiring consequent purchase orders worth millions from TSMC, a global chip manufacturer with over 50% market share, supplying chips to Apple, Nvidia, Qualcomm, and major chip designers

## Projects
* Migration of Kubernetes from Kops to AWS EKS @ Data Republic <br>
The legacy kubernetes clusters were having low SLA and a few long down-time incidents. The platform team intended to leverage managed services, AWS EKS, to manage control plane. To approach the migration, I led the refactoring of the infrastructure Terraform templates to use Terraform module as the basic block to construct the platform. The layout enabled each team member to develop in parallel and thus shorten the iteration time. The migration of 4 clusters finished in a month, resulting SLA improvement to over 95%.
  
* Rejuvenation and Performance Optimisation of Security Information and Event Management (SIEM) System <br>
The Elastic-Kibana stack as SIEM system had throughput issues when a platform component was executing massive computation which emitted excessive logs. It was desired to improve the reliability. I had analysed the performance bottleneck and evaluated the replacement of components by managed services. I managed to swap a legacy log parser with Logstash, which later enabled integration with SOC operation vendor. I also tuned the performance of ElasticSearch to reduce infrastructure cost. The completed ELK stack provided the same throughput with 40% less cost.

* Chrome Headless for PDF Generation Service @ ELMO <br>
Phantom.js did not support generating PDF for HTTPS pages. I implemented a single Node.js Lambda function which used Chromeheadless and then leverage ECS which supports larger file. In addition, it also adapts to the environment for supporting local development.

* Slack bot for Operation Automation @ ELMO <br>
Automated manual task of extracting and obfuscating data from production environment for troubleshooting on Developer's local environment. It is created as a Slack bot that replied inquiry from users, triggered an ETL process, and notified users once completion.

## Education
**Master of Engineering (Materials Science and Engineering)** @ The University of New South Wales, NSW, Australia ( Sep. 2008 - Dec. 2011 ) <br>
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
