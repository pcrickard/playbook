# playbook

Play |	Description |	Results |	Best Practices
--- | --- | --- | ---
Microservice Architecture | Breaks a monolithic application into self-contained microservices |	Results in easier to develop and maintain applications, autonomous and cross-functional teams, flexibility in using technologies and scalability| Loose Coupling, Stateless Application, Containerization
Cloud-Native Services | Design architecture with Cloud-Native services in mind | Results in reduced operations Cost, Elasticity, Scalability and Fault-Tolerant Applications| Infrastructure-as-Code (IaC), Immutable Infrastructure, Dev-Prod Parity
API-First Development | Treats APIs as first-class citizens when a product or service is designed and provides a contract |	Results in Parallel development teams, reusability of the developed services, good developer experience, and reduced risk of failure. |	OpenAPI Specification, Hypermedia as the Engine of Application State (HATEOAS), API Contracts
Data-Driven Solutions | Design your solution to be optimal to the problems that the data will have at scale	| Results in optimized response time, scalability, maximum value from the data | Event Storming, Domain Driven Design (DDD), Decoupled Persistence, Intelligent Search
Shift-Left Security | Security should not be an afterthought and should be built into the development process. | Results in rapid ATO, easier to resolve security issues, and reduced risk of failures | Security Scans, Encryption In-Transition and At-Rest, Penetration Testing
Automation Everywhere | Build a development pipeline that provides automation for developers and allows for rapid development	| Results in fast delivery, reduced risk of failure, measurable progress, version control	| Automated CI/CD pipeline, Automated Testing, Automated Monitoring/Alerts, Autoscaling
Built-in Quality | Quality should be part of the process and not a separate activity |	Results in lower costs, fewer bugs, increasing returns, and stakeholders confidence	| Test Driven Development (TDD), Behavior Driven Development (BDD), Unit/Integration/End-to-End/Load, Quality Gates | Human-Centered Design	Provide an approach that makes for a better user experience, including making information accessible to all constituents | Results in customer-driven solutions, maximum accessibility, good user experience	| Best practices include 508 compliance, United States web design system, code scaffolding, complete documentation

# reference architecture

![alt text](https://github.com/USPTO/playbook/blob/master/refarch.png "Reference Architecture")


# technology toolbox

Layer |	Category | Technology Tools
--- | --- | ---
Agile |	Code Repository |	GitHub, GitLab
Agile |	Collaboration |	SharePoint
Agile |	Communication |	Microsoft Teams
Agile |	Scrum/Kanban Board |	Rally
Data |	Caching |	Amazon ElastiCache, Memcached, Redis
Data |	CDN |	Amazon Cloud Front
Data |	Client-Side Caching |	HTML WEb Storage, IndexedDB
Data |	Cluster |	Ambari, Apache Zookeeper, Hadoop-HDFS, Spark
Data |	Content Management |	Alfresco, Patent CMS
Data |	DB-Connections |	c3p0, JDBC, ODBC, Spring JDBC
Data |	DB-Document Oriented |	Amazon DocumentDB (with MongoDB compatibility), MongoDB
Data |	DB-Graph Oriented |	Amazon Neptune, Azure Cosmos DB, Neo4J
Data |	DB-Relational |	Amazon Aurora (MySQL), Amazon RDS (Oracle), MySQL, Oracle, Percona (MySQL), PostgreSQL
Data |	ETL/Streaming |	Alteryx, Amazon Glue, Amazon Kinesis Data Streams (Kafka), Amazon Kinesis Firehose (Kafka), Amazon Managed Streaming for Kafka (Amazon MSK), Apache Kafka, Apache Nifi, Spark Streaming
Data |	Object Storage |	Amazon AWS S3
Data |	Queue |	Apache Kafka, Jboss AMQ
Data |	Schema Version Control |	Liquibase
Data |	Search |	Apache Solr, Elasticsearch
Data |	Security |	Apache Knox, Apache Ranger
Data |	Synchronization |	Oracle Data Guard
Data |	Visualization |	Alteryx Tableau Desktop, Amazon QuickSight, elastic Kibana, PowerBI
Data |	Warehouse & Data Mart |	USPTO Enterprise Data Warehouse
Desktop |	Browser |	Current Browser Trends
Development |	AOP |	AspectJ, Spring AOP
Development |	API |	OpenAPI, Spring Cloud Contracts, SpringFox, Swagger
Development |	Authentication/Authorization |	Amazon AWS IAM, Azure AD, MyUSPTO, Okta, Oracle IAM, Spring Security
Development |	Authoring |	CKEditor, MS Word
Development |	Automation |	Red Hat Ansible
Development |	Build Packages |	Angular CLI, Apache Maven, Bower, ES6 Modules, Gulp, NPM, Webpack
Development |	Code Documentation |	Javadoc
Development |	Data Science Tools |	Apache Hive, Apache Pig, Apache Tez, Jupyter Notebook, Zeppelin Notebook
Development |	Data Science-Languages |	Julia, Python, R Lang
Development |	Data Science-ML |	Apache Spark MLlib, AWS SageMaker, Google Cloud ML, Tensorflow
Development |	Data Science-NLP |	Stanford NLP
Development |	Framework-Backend |	Node.js, Spring Batch, Spring Boot
Development |	Framework-Frontend |	Angular, React, Vue
Development |	IDE |	Anaconda, Eclipse, IntelliJ IDEA, R Studio, Sublime Text, Visual Studio Code
Development |	Languages |	Google GO, Java, JavaScript, TypeScript
Development |	Notification |	AWS SNS, AWS SQS, Email, USPTO Internally Developed REST API for AWS
Development |	Optical Character Recognition (OCR) |	Tessaract, Tika-server
Development |	ORM |	Hibernate, Sequelize
Development |	Parse, Serialize, Transform |	Jackson, Java Architecture for XML Binding (JAXB)
Development |	PDF Content Management |	Antenna House Formatter, Apache PDFBox, iText, PDFTron WebViewer
Development |	Services-REST |	Jersey, RESTEasy JAX-RS, Spring Boot REST
Development |	Services-SOAP |	Apache Axis2
Development |	Style |	Bootstrap, CSS3, HTML5, SASS, USPTO Design Pattern Library (DPL), USWDS
Infrastructure |	API Gateway |	Apigee, Broadcom Layer 7 Gateway, Kong, MuleSoft
Infrastructure |	Cloud |	AWS, Azure, GCP, MicroPact
Infrastructure |	Cluster |	Apache Ambari (Server & Agent), Apache Spark, Apache Zookeeper, Hadoop-HDFS, Hadoop-Yarn, Hive Server Interactive (HSI), Horton SmartSense
Infrastructure |	Container |	containerd, CRI-O, Docker
Infrastructure |	Container Compute |	Amazon Fargate
Infrastructure |	IaC |	AWS Cloud Development Kit (CDK), Terraform
Infrastructure |	Orchestration |	Amazon ECR, Amazon ECS, Amazon EKS, Kubernetes
Infrastructure |	Pipeline |	Amazon Jenkins, AWS CodeDeploy, Jenkins
Infrastructure |	Platform |	OpenShift
Infrastructure |	Repository Manager |	Nexus
Infrastructure |	Service Mesh |	Istio
Infrastructure |	Shared Services |	Apache Ambari Infra
Infrastructure |	Workflow |	USPTO Hierarchical Finite State Machine
Operations |	APM |	AppDynamics
Operations |	Dashboards |	elastic Kibana, Grafana
Operations |	Metrics |	Apache Ambari Metrics, AppDynamics Pro, Fluentd, Google Analytics, HP SiteScope, Logstash, Prometheus, Splunk
Operations |	Monitoring |	Amazon X-Ray, Apache Log4j 2, AppDynamics Pro, Fluentd, HP SiteScope, JBoss EAP Logging, Logback, QRadar, SLF4J, Splunk
Operations |	Scheduling |	Quartz Scheduler
Testing |	Accessibility/508 |	ANDI, Pa11y, Wave Plug-In for Chrome by Webaim
Testing |	Integration |	Cucumber, Protractor, Selenium
Testing |	Penetration |	Fortify, OWASP Zed Attack Proxy (ZAP), WebInspect
Testing |	Performance |	Gatling, JMeter, LoadRunner
Testing |	Static Code Analysis |	SonarQube
Testing |	Unit |	Jasmine, Jest, jMock, JUnit, Karma, Mockito, OpenPojo, Spring Cloud Contracts

# toolbox statistics

![alt text](https://github.com/USPTO/playbook/blob/master/toolstats.png "Toolbox Statistics")
