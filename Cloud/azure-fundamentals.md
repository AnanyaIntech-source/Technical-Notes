## 📝 Azure Fundamentals Notes

This document contains concise notes and important concepts related to **Microsoft Azure Fundamentals**. It serves as a quick revision guide covering cloud computing concepts, Azure architecture, core Azure services, security, governance, pricing, and management tools.

---

## 📌 What is Cloud Computing?

Cloud Computing is the delivery of computing services such as servers, storage, databases, networking, software, and AI over the Internet instead of using local infrastructure.

Benefits include:

- On-demand resources
- Scalability
- Cost efficiency
- High availability
- Global accessibility

---

## 📌 Types of Cloud Computing

**Public Cloud**

Resources are owned and managed by a cloud provider and shared among multiple customers.

Examples:

- Microsoft Azure
- Amazon Web Services (AWS)
- Google Cloud Platform (GCP)

##

**Private Cloud**

Cloud infrastructure dedicated to a single organization.

Benefits:

- Higher security
- Greater control
- Custom configurations

##

**Hybrid Cloud**

Combines public and private cloud environments.

Benefits:

- Flexibility
- Better disaster recovery
- Easier migration

---

## 📌 Cloud Service Models

### Infrastructure as a Service (IaaS)

Provides virtualized computing resources.

Examples:

- Virtual Machines
- Virtual Networks
- Storage

Customer manages:

- Operating System
- Applications
- Data

##

### Platform as a Service (PaaS)

Provides a platform to build, deploy, and manage applications.

Examples:

- Azure App Service
- Azure SQL Database
- Azure Functions

Customer manages:

- Applications
- Data

Azure manages:

- Infrastructure
- Operating System
- Runtime

##

### Software as a Service (SaaS)

Provides fully managed software over the internet.

Examples:

- Microsoft 365
- Outlook
- Microsoft Teams

Customer only uses the software.

---

## 📌 Benefits of Azure

- High Availability
- Scalability
- Elasticity
- Global Infrastructure
- Disaster Recovery
- Security
- Cost Optimization

---

## 📌 Azure Regions

A Region is a geographical area containing one or more Azure datacenters.

Examples:

- East US
- West Europe
- Central India
- Southeast Asia

---

## 📌 Availability Zones

Availability Zones are physically separate datacenters within an Azure region.

Benefits:

- Fault tolerance
- High availability
- Business continuity

---

## 📌 Azure Resources

A Resource is any service created in Azure.

Examples:

- Virtual Machine
- Storage Account
- SQL Database
- Virtual Network

---

## 📌 Resource Group

A Resource Group is a logical container used to organize Azure resources.

Benefits:

- Easier management
- Access control
- Monitoring
- Billing

---

## 📌 Azure Subscription

A Subscription provides access to Azure services and is used for billing and resource management.

One account can have multiple subscriptions.

---

## 📌 Azure Management Hierarchy

```
Management Group

↓

Subscription

↓

Resource Group

↓

Resources
```

---

## 📌 Core Azure Services

### Compute

Provides processing power.

Examples:

- Azure Virtual Machines
- Azure App Service
- Azure Functions
- Azure Kubernetes Service (AKS)

##

### Storage

Stores data securely.

Types:

- Blob Storage
- File Storage
- Queue Storage
- Table Storage

##

### Networking

Provides communication between Azure resources.

Examples:

- Virtual Network (VNet)
- VPN Gateway
- Load Balancer
- DNS

##

### Databases

Managed database services.

Examples:

- Azure SQL Database
- Cosmos DB
- Azure Database for MySQL
- Azure Database for PostgreSQL

---

## 📌 Azure Identity Services

Azure uses **Microsoft Entra ID** (formerly Azure Active Directory) for identity and access management.

Features:

- Authentication
- Authorization
- Single Sign-On (SSO)
- Multi-Factor Authentication (MFA)

---

## 📌 Azure Security Services

Examples:

- Microsoft Defender for Cloud
- Azure Firewall
- Azure DDoS Protection
- Azure Key Vault

---

## 📌 Azure Monitoring

Azure Monitor helps track resource performance and health.

Features:

- Metrics
- Logs
- Alerts
- Dashboards

---

## 📌 Azure Cost Management

Azure follows a **Pay-as-you-Go** pricing model.

Pricing depends on:

- Compute usage
- Storage
- Networking
- Service type

Tools:

- Azure Pricing Calculator
- Azure Cost Management

---

## 📌 Azure Governance

Governance ensures resources comply with organizational policies.

Services include:

- Azure Policy
- Resource Locks
- Tags
- Management Groups
- Azure Blueprints

---

## 📌 Azure Portal

The Azure Portal is a web-based interface for managing Azure resources.

Features:

- Create resources
- Monitor services
- Manage subscriptions
- Configure networking
- Billing

---

## 📌 Azure CLI

Azure CLI is a command-line tool used to manage Azure resources.

Example:

```bash
az login
```

---

## 📌 Azure PowerShell

PowerShell provides scripting support for Azure administration.

Example:

```powershell
Connect-AzAccount
```

---

## 📌 ARM (Azure Resource Manager)

Azure Resource Manager manages Azure resources using templates and automation.

Benefits:

- Infrastructure as Code (IaC)
- Automation
- Resource organization

---

## 📌 Shared Responsibility Model

| Responsibility | Customer | Microsoft |
|---------------|:--------:|:---------:|
| Data | ✅ | |
| Applications | ✅ | |
| Identity & Access | ✅ | |
| Physical Datacenters | | ✅ |
| Hardware | | ✅ |
| Networking Infrastructure | | ✅ |

---

## 📌 Common Azure Services

| Service | Purpose |
|----------|---------|
| Virtual Machines | Compute |
| App Service | Web Hosting |
| Azure Functions | Serverless Computing |
| Blob Storage | Object Storage |
| Azure SQL Database | Managed Database |
| Cosmos DB | NoSQL Database |
| Virtual Network | Networking |
| Azure Monitor | Monitoring |
| Azure Key Vault | Secrets Management |
| Microsoft Entra ID | Identity Management |

---

## 📌 Advantages of Azure

- Global availability
- Enterprise-grade security
- High scalability
- Cost-effective pricing
- Wide range of cloud services
- Easy integration with Microsoft ecosystem

---

## 📌 Key Azure Terms

| Term | Meaning |
|------|---------|
| Region | Geographic location of Azure datacenters |
| Availability Zone | Independent datacenter within a region |
| Resource | Individual Azure service |
| Resource Group | Logical container for resources |
| Subscription | Billing and management boundary |
| Tenant | Microsoft Entra ID instance |

---

## 💡 Key Takeaways

- Microsoft Azure is a leading cloud computing platform.
- Cloud services are categorized into IaaS, PaaS, and SaaS.
- Azure resources are organized using Resource Groups and Subscriptions.
- Azure provides secure, scalable, and globally available cloud services.
- Microsoft Entra ID manages identity and access.
- Azure Monitor and Cost Management help optimize cloud resources.

---

## Status

🟢 Active | Continuously Updated

---

## License

This repository is protected under the Creative Commons Attribution 4.0 International License.
All certificates belong to the author and are displayed here for educational and professional documentation purposes.

---

## Contact

**Ananya Siju**  
[LinkedIn](https://www.linkedin.com/in/ananya-siju-a04835291/) | [GitHub](https://github.com/AnanyaIntech-source) | ananyasiju16@gmail.com

---

> **Author:** [Ananya Siju](https://github.com/AnanyaIntech-source)
> 

