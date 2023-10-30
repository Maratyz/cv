# Marat (Yen-chih Chen)

Optimized performance from Linux cpu binding for highly concurrent systems, database indexing on Web application, to big-O optimization on code. Focused on iterating observability for incident response and DevOps implementation for delivery. Leveraged AWS services for container orchestration, networking, and big data analysis.

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
**System Engineer** @ [Amazon](https://www.amazon.com/) ( Feb. 2022 - present ) <br>
Keep every Amazon retail website up
* System development
  * Reduced the developer-engagement cost by >90% by bulilding critical components in an internal dependency observability system. 
  * Streamlined engagement process by building a ML-supported system to consolidate anomaly detection and service owner lookup
* Incident response
  * Enabled >30% reduction in time to resolve incidents by moderating 100+ drills within a year to familiarize team members with internal tools
* Resiliency and observability improvement
  * Extend alarm audit for 2000+ services with the insight on monitoring miss from reviewing every incident

**SRE (Site Reliability Engineer)** @ [IXUP](https://ixup.com/) ( Jul. 2021 - Feb. 2022 ) <br>
Continue to operate the purchased products from Data Republic
* Cost reduction by ~20k / month by depreciating services and balancing cloud resources
* Reduce 1 developer-day on monthly basis with extending a Promethus plugin to build Grafana dashboard for business data export

**SRE and DevOps Engineer** @ [Data Republic](https://www.datarepublic.com/) ( Sep. 2019 - Jul. 2021 ) <br>
Platform to share and match data securely, and provide sandboxes to analyse data
* Cloud operation and management: SLA improvement and SLA-impacting incidents
  * Migrated services from legacy kops cluster to AWS EKS by refactoring and extending Terraform templates and Kubernetes definitions for over 50 services, updating and testing CD pipeline, and defining the procedure; SLA improvement from <90% to >95% 
  * Shortened incident resolution time by working out automation for disaster recovery and data restoration over 100+ EC2 instances

* Observability: automating user experience monitoring and shortening response time toward issue analysis
  * Bulit user-behavior automation testing with Puppeteer for measuring SLA in a black-box approach.
  * Reduce development effort from over weeks to less than a day by introducing Prometheus operator CRD to define metric and alarm setup 
  * Revamp ELK stack to consume both application and infrastructure logs for faster analysis in a single place with better performance and higher SLI

* Security: building patching pipeline, working in SOC compliance, and validating product security
  * Automate security patch with pipelines for AWS EC2 instances and AMI with AWS System Manager
  * Complied with [SOC2](https://www.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc2report.html) by ingesting log to a 3rd-party system
  * Demonstarted product security validation by intercepting and decrypting SSL traffic with a man-in-the-middle proxy 

* Agility: migrating pipelines to scalable solution and reducing the lead time by 30%
  * Refactored legacy CI/CD Makefile scripts to execute on Github actions, shortening bulid and testing time with Docker image caching
  * Minimized monetary cost by auto-scaling the self-hosted Github action runners based on demand

**Senior DevOps Engineer** @ [ELMO Software](https://elmosoftware.com.au/) ( Jan. 2018 - Sep. 2019 ) <br>
Multi-tenant system for small-medium companies to manager human resources, training, payroll, and performance management
* CI/CD and Operation: automating internal manual processes and constructing pipelines from scratch
  * Streamlined the development process, I built internal serverless tools which manages AWS resources, data obfuscation, streaming Cloudwatch logs and developed Chef recipes, Apache/Nginx configuration, Dockerfiles, and Makefiles which simplified CI/CD configuration. 
  * Leveraged network and log analysis tools to investigate production and development issues
  * Operation tasks including integration setup, data analysis for business decisions, and Website maintenance.

* System design and implementation: transforming production into cloud-native ones
  * I designed and built infrastructure for over 10 projects including containerisation with ECS, API Gateway, database migration with Redshift, and serverless applications with best practices including scalability, availability, nested stacks, and minimum permission.

**Project Management/Operation/Optimization** @ [Groundhog Technology](https://www.ghtinc.com/) ( Oct. 2015 - Jul. 2017 ) <br>
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

## Certificates
### Amazon Web Service (AWS) 
* AWS Solution Architect Professional Certificate (SAP)
* AWS DevOps Professional Certificate (DOP)
* AWS Advanced Networking (ANP)
* AWS Solution Architect Associate Certification (SAA)
* AWS Developer Associate Certification (DVA)
* AWS SysOps Administrator Certification (SOA)
