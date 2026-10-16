# Cloud Resource Comparison Across AWS, Azure, and Google Cloud

**Name:** BASHIRU TAJUDEEN OPEYEMI  
**Student No.:** 041289261

## Cloud Resource Comparison

| No. | Cloud Resource / Function | AWS | Microsoft Azure | Google Cloud |
| --- | --- | --- | --- | --- |
| 1 | Scalable virtual machines | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| 2 | Object storage | Amazon S3 | Azure Blob Storage | Cloud Storage |
| 3 | Managed relational databases | Amazon RDS | Azure SQL Database; Azure Database for MySQL / PostgreSQL | Cloud SQL |
| 4 | Event-driven serverless functions | AWS Lambda | Azure Functions | Cloud Run functions, formerly Cloud Functions |
| 5 | Isolated cloud networks | Amazon VPC | Azure Virtual Network | Virtual Private Cloud (VPC) |
| 6 | Content delivery network | Amazon CloudFront | Azure Front Door | Cloud CDN |
| 7 | Managed NoSQL database | Amazon DynamoDB | Azure Cosmos DB | Firestore; Bigtable |
| 8 | Persistent block storage | Amazon EBS | Azure Managed Disks | Hyperdisk; Persistent Disk |
| 9 | Managed Kubernetes | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |
| 10 | Access management and encryption keys | AWS IAM + AWS KMS | Microsoft Entra ID / Azure RBAC + Azure Key Vault | Cloud IAM + Cloud KMS |
| 11 | Managed application deployment and scaling | AWS Elastic Beanstalk | Azure App Service | App Engine |
| 12 | Monitoring and logging | Amazon CloudWatch | Azure Monitor + Log Analytics | Cloud Monitoring + Cloud Logging |
| 13 | Managed DNS | Amazon Route 53 | Azure DNS | Cloud DNS |
| 14 | Load balancing | Elastic Load Balancing (ELB) | Azure Load Balancer; Application Gateway | Cloud Load Balancing |
| 15 | Automatic resource scaling | Amazon EC2 Auto Scaling; Application Auto Scaling | Azure Monitor autoscale / Virtual Machine Scale Sets | Compute Engine autoscaling for managed instance groups |
| 16 | Message queues | Amazon SQS | Azure Service Bus queues | Cloud Tasks; Pub/Sub, depending on messaging pattern |
| 17 | Real-time data streaming | Amazon Kinesis Data Streams + Managed Service for Apache Flink | Azure Event Hubs + Stream Analytics | Pub/Sub + Dataflow |
| 18 | Analytical data warehouse | Amazon Redshift | Azure Synapse Analytics dedicated SQL pools | BigQuery |
| 19 | Workflow orchestration | AWS Step Functions | Azure Logic Apps | Workflows |
| 20 | Data integration, transformation, and movement | AWS Glue + AWS Database Migration Service | Azure Data Factory | Cloud Data Fusion + Datastream |
| 21 | Data catalog and governance | AWS Glue Data Catalog + Lake Formation + Amazon DataZone | Microsoft Purview | Knowledge Catalog, formerly Dataplex Universal Catalog |
| 22 | Prebuilt AI models, APIs, and development tools | Amazon Bedrock; Rekognition; Comprehend; other AWS AI services | Microsoft Foundry + Foundry Tools, formerly Azure AI services | Vertex AI + Cloud Vision, Speech-to-Text, and other AI APIs |
| 23 | Infrastructure as code | AWS CloudFormation | Azure Resource Manager templates / Bicep | Infrastructure Manager, using Terraform |
| 24 | CI/CD pipelines | AWS CodePipeline + CodeBuild + CodeDeploy | Azure Pipelines | Cloud Build + Cloud Deploy |
| 25 | Virtual desktops | Amazon WorkSpaces | Azure Virtual Desktop | Partner solutions such as Citrix or Dizzion Frame on Google Cloud |
| 26 | Backup and disaster recovery | AWS Backup + AWS Elastic Disaster Recovery | Azure Backup + Azure Site Recovery | Backup and DR Service |
| 27 | Big data and real-time analytics | Amazon EMR + Managed Service for Apache Flink | Azure Databricks + Azure Data Explorer | Dataproc + Dataflow + BigQuery |
| 28 | Shared file storage | Amazon EFS; Amazon FSx | Azure Files | Filestore |
| 29 | Media transcoding and streaming | AWS Elemental MediaConvert + MediaLive + MediaPackage | Partner media solutions; Azure Media Services is retired | Transcoder API + Live Stream API + Media CDN |
| 30 | Notifications, email, and text messages | Amazon SNS + Amazon SES + AWS End User Messaging | Azure Communication Services + Notification Hubs | Firebase Cloud Messaging for push; third-party providers for email and SMS |

## 1. Introduction

Cloud computing lets businesses and individuals use resources like servers, storage, databases, and networking over the internet. The main providers are Amazon Web Services (AWS), Microsoft Azure, and Google Cloud.

Cloud storage is another area where they are similar. Amazon S3, Azure Blob Storage, and Google Cloud Storage let users save files, images, backups, and other data. These services can scale as a business grows.

All three providers also have serverless computing. AWS Lambda, Azure Functions, and Google Cloud Run let developers run code without managing servers.

Each provider includes security features, monitoring tools, and automatic scaling to help applications perform well and stay available.

## 2. Differences Between Cloud Providers

Although their services are similar, each provider delivers cloud solutions differently.

AWS offers many dedicated services for computing, storage, networking, databases, and app development. For example, Amazon DynamoDB is a managed NoSQL database, and Amazon Redshift supports data warehousing and analytics.

Microsoft Azure integrates closely with Microsoft technologies such as Windows Server, Microsoft Entra ID, and Microsoft SQL Server. This can help organizations already using Microsoft products. Azure also provides services such as Azure App Service, Azure Virtual Desktop, and Azure DevOps.

Google Cloud is known for its data analytics, Kubernetes, and machine learning services. For example, organizations use BigQuery to analyze large datasets, while Google Kubernetes Engine helps manage containerized applications.

Another difference is how some services are organized. AWS offers Amazon RDS for multiple relational database engines, while Azure supplies separate services such as Azure SQL Database and Azure Database for PostgreSQL.

These differences show that similar cloud services can have different features, configurations, and management options.

## 3. Special Features and Capabilities

Each cloud provider offers features that can meet different business requirements.

AWS provides Amazon WorkSpaces for remote virtual desktops and AWS Elastic Beanstalk for application deployment. It also offers several services to build and manage cloud applications.

Azure delivers Azure Virtual Desktop, which supports remote desktop environments. Microsoft Entra ID also helps organizations manage identities and control access to resources. Azure is especially useful when businesses need to integrate cloud services with existing Microsoft environments.

Google Cloud provides BigQuery for large-scale analytics and Vertex AI for developing and running machine learning applications. Google Kubernetes Engine is another important service for organizations using containers and microservices.

The best cloud provider depends on the organization's needs, existing technology, budget, and technical requirements.

## 4. Naming Conventions

One interesting observation from this comparison is how the three providers name their services.

AWS commonly uses names beginning with "Amazon" or "AWS," such as Amazon EC2, Amazon S3, AWS Lambda, and AWS CloudFormation. Some names are shortened forms or branded product names that do not immediately explain their functions.

Microsoft Azure often uses descriptive names that begin with "Azure," such as Azure Virtual Machines, Azure Functions, Azure Backup, and Azure Monitor. These names usually provide a clear indication of what the service does.

Google Cloud also uses descriptive names such as Compute Engine, Cloud Storage, Cloud SQL, and Cloud Monitoring. These names generally reflect each service's main purpose.

For example, Amazon EC2, Azure Virtual Machines, and Google Compute Engine all provide virtual machine computing resources, even though their names are different.

These naming conventions help cloud professionals identify equivalent services across providers.

## 5. Conclusion

From this research, I learned that AWS, Microsoft Azure, and Google Cloud offer many similar cloud computing services, but their names and features do not always match.

I also learned that knowing one cloud platform makes it easier to understand another. For example, someone familiar with Azure Virtual Machines can grasp the basic purpose of Amazon EC2 and Google Compute Engine.

As a Cloud Development and Operations student, I believe learning the differences between these platforms matters because organizations may choose different cloud providers based on their business requirements.

Overall, this comparison helped me understand how cloud services relate to one another and why choosing the right technology for a particular project matters.

## References

- Amazon Web Services. (n.d.). [AWS documentation](https://docs.aws.amazon.com/).
- Microsoft. (n.d.). [Azure documentation](https://learn.microsoft.com/en-us/azure/).
- Google Cloud. (n.d.). [Google Cloud documentation](https://docs.cloud.google.com/docs).
- Google Cloud. (n.d.). [Compare AWS and Azure services to Google Cloud](https://docs.cloud.google.com/docs/get-started/aws-azure-gcp-service-comparison).
