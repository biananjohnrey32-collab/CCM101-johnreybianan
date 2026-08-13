# Client Recommendations

## Cloud Platform Recommendations

Different organizations have different technical requirements. The most appropriate cloud platform depends on factors such as existing infrastructure, business goals, application requirements, scalability, data needs, and technical expertise.

---

## Client A — Startup Company

### Recommended Platform: Amazon Web Services (AWS)

AWS is recommended for the startup because it provides a broad range of cloud services that can support a company from its early stage through future growth. AWS allows startups to use scalable computing, storage, databases, and application deployment services without having to purchase physical infrastructure. The platform also provides services that can be expanded as the startup's number of users and business requirements increase. AWS specifically provides startup guidance and services such as Amazon S3, Amazon EC2, Amazon RDS, and Elastic Beanstalk for building and scaling applications.

### Recommended AWS Services

1. **Amazon EC2** — Provides scalable virtual computing capacity for running applications and servers.
2. **Amazon S3** — Provides scalable object storage for files, images, backups, and application data.
3. **Amazon RDS** — Provides managed relational database services.
4. **AWS Elastic Beanstalk** — Helps developers deploy and manage web applications without managing all of the underlying infrastructure.

### Recommendation

AWS is a strong choice for the startup because it provides the flexibility and scalability needed as the business grows.

---

## Client B — University Using Windows Server, Microsoft 365, and Active Directory

### Recommended Platform: Microsoft Azure

Microsoft Azure is recommended for the university because the organization already uses Microsoft technologies such as Windows Server, Microsoft 365, and Active Directory. Azure provides strong integration with Microsoft's identity and enterprise ecosystem. The university can use Azure services to extend or migrate existing Windows-based workloads while maintaining centralized identity and access management. Azure also supports hybrid environments, allowing an organization to connect existing infrastructure with cloud resources.

### Recommended Azure Services

1. **Azure Virtual Machines** — Can host Windows Server workloads and other applications in the Azure cloud.
2. **Microsoft Entra ID** — Provides cloud-based identity and access management and integrates with Microsoft's ecosystem.
3. **Microsoft Entra Domain Services** — Provides managed domain services using technologies such as LDAP, Kerberos, NTLM, and Group Policy for compatible applications and workloads.
4. **Azure Virtual Network** — Provides private networking for Azure resources and connections to existing networks.

### Recommendation

Azure is the most suitable choice because the university already operates within the Microsoft ecosystem. This can simplify integration, identity management, and migration of existing Windows-based systems.

---

## Client C — AI Research Company

### Recommended Platform: Google Cloud Platform (GCP)

Google Cloud Platform is recommended for the AI research company because it provides strong capabilities for artificial intelligence, machine learning, and data analytics. Google Cloud provides tools that can support the complete data and machine learning workflow, from storing and analyzing data to developing and deploying machine learning models. BigQuery can be used for large-scale data analytics, while Vertex AI provides tools for developing and deploying AI and machine learning solutions. These services can help researchers work with large datasets and build AI applications.

### Recommended GCP Services

1. **Vertex AI** — Provides a platform for developing and deploying machine learning and AI applications.
2. **BigQuery** — Provides a scalable data warehouse and analytics platform for analyzing large datasets.
3. **Google Cloud Storage** — Provides object storage for datasets, research files, and other data.
4. **Google Kubernetes Engine (GKE)** — Provides managed Kubernetes for containerized applications and workloads.

### Recommendation

GCP is recommended because the company's primary requirements are AI research, machine learning, and large-scale data analytics. Its data and AI services can support researchers throughout the machine learning lifecycle.

---

## Client D — Global E-Commerce Company

### Recommended Platform: Amazon Web Services (AWS)

AWS is recommended for the global e-commerce company because it provides services for scalable web applications, databases, storage, networking, content delivery, messaging, security, and analytics. A global e-commerce system needs to handle large numbers of customers, product requests, orders, payments, and other transactions. AWS provides multiple services that can work together to build scalable and resilient e-commerce architectures. AWS also provides official guidance for building web stores using services such as Amazon S3, Amazon EC2, Amazon RDS, Amazon CloudFront, Amazon SQS, and other AWS services.

### Recommended AWS Services

1. **Amazon EC2** — Provides scalable computing capacity for web and application servers.
2. **Amazon S3** — Stores product images, static website content, backups, and other data.
3. **Amazon RDS** — Provides managed relational database capabilities for application data.
4. **Amazon CloudFront** — Provides content delivery for websites and applications to improve performance for users in different geographic locations.
5. **Amazon SQS** — Provides message queuing that can help separate application components and process orders reliably.

### Recommendation

AWS is a suitable choice for the global e-commerce company because it provides a broad collection of services for building scalable and globally distributed applications. The company can combine compute, storage, databases, content delivery, and messaging services to support its e-commerce operations.

---

# Summary of Recommendations

| Client | Recommended Platform | Main Reason |
|---|---|---|
| Client A — Startup | AWS | Flexible and scalable services for business growth |
| Client B — University | Microsoft Azure | Strong integration with Windows Server, Microsoft 365, and Microsoft identity technologies |
| Client C — AI Research Company | GCP | Strong AI, machine learning, and data analytics capabilities |
| Client D — Global E-Commerce | AWS | Broad services for scalable and globally distributed applications |
---

# Checkpoint 5 — Matching Cloud Services

| Service Category | AWS | Azure | GCP |
|---|---|---|---|
| Virtual Machine | Amazon EC2 | Azure Virtual Machines | Google Compute Engine |
| Object Storage | Amazon S3 | Azure Blob Storage | Google Cloud Storage |
| Identity Management | AWS IAM | Microsoft Entra ID | Cloud Identity / Google Cloud IAM |
| SQL Database | Amazon RDS | Azure SQL Database | Cloud SQL |
| Kubernetes | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |

