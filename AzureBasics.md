# Basic Cloud Computing Concepts



# An Intro to Cloud Computing
- Cloud computing is the delivery of computing services—like storage, servers, databases, networking, and software—over the internet, often referred to as “the cloud.”
- It allows individuals and organizations to access and manage data from anywhere, without the need for heavy hardware.
- With benefits such as scalability, cost-efficiency, and flexibility, cloud computing has become the backbone of modern digital infrastructure.
  
- K**ey Characteristics:**
    - **On-Demand Self-Service:** Users can provision resources as needed without human interaction with service providers.
    - **Broad Network Access:** Services are available over the network and accessed through standard mechanisms (e.g., laptops, phones).
    - **Resource Pooling:** Providers serve multiple customers using a multi-tenant model, dynamically assigning resources.
    - **Rapid Elasticity:** Resources can be scaled up or down quickly to meet demand.
    - **Measured Service**: Usage is monitored and billed based on consumption.

- **Types of Cloud Services:**
    - **IaaS (Infrastructure as a Service):** Provides virtualized computing resources over the internet (e.g., Amazon EC2).
    - **PaaS (Platform as a Service):** Offers a platform allowing customers to develop, run, and manage applications (e.g., Google App Engine).
    - **SaaS (Software as a Service)**: Delivers software applications over the internet (e.g., Microsoft 365, Gmail).

- **Deployment Models:**
    - **Public Cloud:** Services offered over the public internet and available to anyone.
    - **Private Cloud:** Exclusive to a single organization, offering more control and security.
    - **Hybrid Cloud:** Combines public and private clouds, allowing data and applications to move between them.

- **Benefits:**
    - Cost efficiency
    - Scalability
    - Flexibility
    - Disaster recovery
    - Automatic updates

# Describe the Shared Responsibility Model
- The Shared Responsibility Model is a framework
- used in cloud computing to define the division of security and compliance **responsibilities** between the **cloud service provider** and the **customer**.
- > While the provider is responsible for securing the underlying infrastructure—such as physical data centers, networking, and virtualization—the customer is
    responsible for securing what they put into the cloud, including data, user access, and application configurations.
- The exact split depends on the type of **cloud service used:**
- in **IaaS**, customers manage more (like operating systems and applications);
- in **PaaS**, they manage less;
- and in **SaaS**, they manage the least, typically just user access and data.
- Understanding this model is crucial to avoid security gaps and ensure proper governance in cloud environments.

# The Benefits of Cloud Computing
- **Cost Efficiency**: Reduces capital expenditure by eliminating the need for physical hardware and data centers.
- **Scalability**: Easily scale resources up or down based on demand without overprovisioning.
- Elasticity: 
- **Flexibility & Agility**: Enables rapid deployment of applications and services, supporting innovation and faster time-to-market.
- **High Availability & Reliability**: Built-in redundancy and failover mechanisms ensure consistent uptime and performance.
- **Disaster Recovery & Business**: Cloud providers offer robust backup and recovery solutions to minimize downtime.
- **Security Enhancements:** Advanced security features like encryption, identity management, and compliance support are built-in.
- **Global Reach**: Access services and data from anywhere in the world with minimal latency.
- **Automatic Updates**: Providers handle software and infrastructure updates, ensuring systems are always current.
- **Environmental Sustainability:** Optimized resource usage and energy-efficient data centers contribute to greener IT operations.
- **Collaboration and Remote Work**: Cloud-based tools enable seamless collaboration across teams and geographies.

# Compare Cloud Pricing Models
- Pay-As-You-Go (On-Demand)
- Reserved Instancse
- Spot Instances
- Saving Plans
- Free Tier
- Subscription-Based Pricing
- Per-Second or Per-Minute Billing
- Data Transfer Costs
- Cost Management Tools
- Choosing the Right Model
- 
# Public Cloud, Private Cloud, Hybrid Cloud
- 
# Cloud Service Types
- **Infrastructure as a Service (IaaS)**
    - Provides virtualized computing resources over the internet.
    - Users manage OS, storage, and applications.
    - Examples: Amazon EC2, Microsoft Azure VMs.

- **Platform as a Service (PaaS)**
    - Offers hardware and software tools over the internet.
    - Users focus on application development without managing infrastructure.
    - Examples: Google App Engine, Azure App Service.
  
- **Software as a Service (SaaS)**
    - Delivers software applications via the cloud.
    - Users access apps through a browser; providers manage everything.
    - Examples: Microsoft 365, Salesforce, Google Workspace.

- **Function as a Service (FaaS) / Serverless**
    - Executes code in response to events without managing servers.
    - Scales automatically and charges only for execution time.
    - Examples: AWS Lambda, Azure Functions.
 
## Describe Infrastructure-as-a-Service (IaaS)
- > IaaS is a cloud computing service model that provides virtualized computing resources over the internet.
  > It offers the fundamental building blocks of IT—such as virtual machines, storage, and networking—on a pay-as-you-go basis.
  > With IaaS, users can provision and manage infrastructure without investing in physical hardware.
  
- > While the cloud provider manages the underlying infrastructure (servers, data centers, networking), the customer is responsible for managing the operating
  > systems, applications, data, and security configurations. This model offers maximum flexibility and control, making it ideal for developers, system
  > administrators, and businesses with custom infrastructure needs.
- Examples:
    - Amazon EC2
    - Microsoft Azure Virtual Machines
    - Google Compute Engine

## Describe Platform-as-a-Service (PaaS)
- > PaaS is a cloud computing service model that provides a ready-to-use platform for developing, running, and managing applications without the complexity of
  > building and maintaining the underlying infrastructure.
  
  > It includes tools for coding, testing, deploying, and scaling applications, along with middleware, databases, and development frameworks.
  > The cloud provider manages everything from servers and storage to networking and runtime environments, while the customer focuses solely on the application
  > logic and data.

- PaaS accelerates development, reduces operational overhead, and supports agile workflows.
- Examples:
    - Google App Engine
    - Microsoft Azure App Service
    - Heroku

## Describe Software-as-a-Service (SaaS)
- > SaaS is a cloud computing service model that delivers fully functional software applications over the internet.
  > Users access these applications through a web browser or client interface, without needing to install, maintain, or manage the underlying infrastructure,
  > middleware, or application software.
  > The cloud provider handles everything—from servers and storage to updates and security—while customers simply use the software.
  > SaaS is ideal for businesses seeking cost-effective, scalable, and easy-to-use solutions for collaboration, productivity, CRM, and more.

Examples:
    - Microsoft 365
    - Google Workspace
    - Salesforce
    - Dropbox

## Serverless
- You dont manage the infrastructure and servers
- you only handle writing and running the code, that's it.
- You dont need to pre-purchase or reserve the resources
- 
- 
# Azure Core Architectural Concepts
- > Microsoft Azure’s architecture is built on a foundation of global infrastructure, services, and management tools that support scalable, secure, and
  > resilient cloud solutions.
  > Understanding these core concepts helps in designing efficient and cost-effective cloud architectures
- **Regions and Availability Zones**
    - Azure is deployed globally in regions, each with multiple data centers.
    - Availability Zones provide high availability and fault tolerance.
- **Resource Groups**
    - Logical containers for managing and organizing related Azure resources.
- **Azure Resource Manager (ARM)**
    - The deployment and management service for Azure.
    - Enables infrastructure as code and role-based access control.
- **Subscriptions**
    - Units of management, billing, and access control.
    - Each subscription is linked to an Azure Active Directory tenant.
- **Management Groups**
    - Used to manage access, policies, and compliance across multiple subscriptions.
- **Security and Compliance**
    - Built-in tools and services to help meet regulatory and organizational requirements.
  
## Describe Azure Regions, Region Pairs, and Sovereign Regions
- **Azure Regions**
    - > An Azure Region is a set of data centers deployed within a specific geographic location.
      > Each region offers a range of Azure services and is designed for high availability, scalability, and compliance.
      > Examples: East US, West Europe, Southeast Asia

- **Azure Region Pairs**
    - Azure organizes regions into Region Pairs—two regions within the same geography at least 300 miles apart.
    - Benefits:
        - Disaster recovery: One region can failover to its pair.
        - Data residency: Ensures compliance with local regulations.
    - Sequential updates: Microsoft rolls out updates to one region at a time to reduce downtime risk.
    - Example: East US ↔ West US

- **Sovereign Regions**
- Sovereign Regions are isolated Azure environments designed to meet specific government or regulatory requirements.
- Operated independently from the global Azure cloud.
- Examples:
    - Azure Government (U.S.)
    - Azure China (operated by 21Vianet)
    - Azure Germany (legacy model, now integrated into global Azure)

## Describe Availability Zones in Azure
- > Availability Zones are physically separate locations within an Azure region, each with its own power, cooling, and networking.
  > They are designed to ensure high availability and fault tolerance for your applications and data.
  > Each Azure region with Availability Zones has at least three separate zones, allowing you to distribute your resources across them to protect against data
  > center-level failures.
- **Key Benefits**
    - > High Availability: Ensures uptime even if one zone fails.
      > Fault Isolation: Each zone is independent, reducing the blast radius of failures.
      > Data Redundancy: Supports zone-redundant services like Azure SQL Database and Azure Storage.
      > Disaster Recovery: Enables resilient architectures for mission-critical applications.

## Describe Azure Resources and Resource Groups
- **Azure Resources**
    - > An Azure Resource is any manageable item available through Azure.
      > Examples include:
        Virtual Machines (VMs)
        Storage Accounts
        Web Apps
        Databases
        Virtual Networks
        Each resource has a unique name, type, location, and configuration settings.

- **Resource Groups**
- A Resource Group is a logical container that holds related Azure resources.
- It helps organize and manage resources as a unit.
- You can apply access controls, policies, and tags at the resource group level.
- Resources in a group can share the same lifecycle (e.g., deployed, updated, deleted together).

## Describe Azure Subscriptions
- > An Azure Subscription is a billing and access control boundary within Microsoft Azure.
  > It defines how resources are provisioned, managed, and paid for.
  > Each subscription is associated with an Azure Active Directory (AAD) tenant and can contain multiple resource groups and resources.
-  Key Features of Subscriptions:
    - Billing Unit: Tracks usage and costs for services consumed.
    - Access Control: Role-Based Access Control (RBAC) can be applied at the subscription level.
    - Isolation: Subscriptions can be used to separate environments (e.g., dev, test, prod).
    - Quota Management: Each subscription has limits on resources (e.g., number of VMs).
    - Multiple Subscriptions: Organizations often use multiple subscriptions for departments, projects, or compliance needs.

## Describe Management Groups in Azure
- Management Groups in Azure are hierarchical containers used to organize and manage multiple Azure subscriptions. T
- hey allow organizations to apply governance, policies, and access controls across a group of subscriptions in a scalable and consistent way.
 
# Explore Azure database and analytics services
- Data is the heartbeat of any modern enterprise. Azure doesn’t just store it—it empowers you to make sense of it.
- **Azure SQL Database**: A fully managed, intelligent relational database as a service (DBaaS). 
    - Great for apps needing high availability, performance, and security.
- **Cosmos DB**: Globally distributed NoSQL database for high-speed, scale-out applications. Ideal for IoT, gaming, or ecommerce scenarios.
- **Azure Synapse Analytics**: End-to-end analytics with big data and data warehousing in one unified experience.
- **Azure Databricks**: Apache Spark-based analytics platform optimized for AI and machine learning workloads.
- **Azure Data Lake Storage**: Massive-scale storage designed for big data analytics.

# Explore Azure compute services

## Different Compute Services and Products offered by Azure
- https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree
- **Azure Virtual Machines:** A service where you deploy and manage virtual machines (VMs) inside an Azure virtual network.
- **Azure App Service:** A managed service for hosting web apps, mobile app back ends, RESTful APIs, or automated business processes.
- **Azure Function:** A service that provides managed functions that run based on a variety of trigger types for event-driven applications.
- **Azure Kubernetes Service (AKS):** A managed Kubernetes service for running containerized applications.
- **Azure Container Apps:** A managed service built on Kubernetes, which simplifies the deployment of containerized applications in a serverless environment.
- **Azure Container Instances:** This service is a fast and simple way to run a single container or group of containers in Azure.
                             Azure Container Instances doesn't provide full container orchestration, but you can implement them without having to provision
                             any VMs or adopt a higher-level service.
- **Azure Red Hat Open Shift:** A fully managed OpenShift cluster for running containers in production with Kubernetes.
- **Azure Service Fabric:** A distributed systems platform that can run in many environments, including Azure or on-premises.
- **Azure Batch:** A managed service for running large-scale parallel and high-performance computing (HPC) applications.
- **Azure VMWare Solution:** A managed service for running VMware workloads natively on Azure.

## Understand different Hosting Models for Compute Services

- Infrastructure-as-a-service (IaaS)
- Platform-as-a-service (PaaS)
- Function-as-a-Service (FaaS)

## Microservices Compute Option
- https://learn.microsoft.com/en-us/azure/architecture/microservices/design/compute-options
- The term compute refers to the hosting model for the computing resources that your application runs on.
- For a microservices architecture, the following approaches are popular:
  - Deploy microservices on dedicated compute platforms, typically by using a microservice orchestrator.
  - Deploy microservices on a serverless platform.
  - Following are teh Microservices compute options and products offered by Azure:
    - Azure Kubernetes Service (AKS)
    - Container Apps
    - Service Fabric
    - Red Hat OpenShift

## Availability options in Computing services
There are multiple options to manage the availability of your virtual machines in Azure

- **Availability Zones**
    - Availability Zones are physically separated zones within an Azure region.
    - Availability zones guarantee virtual machine connectivity to at least one instance at least 99.99% of the time when you have two or more instances
      deployed
    - across two or more Availability Zones in the same Azure region.
      
- **Virtual Machine Scale Set**
    -  Virtual Machine Scalet Set let you create and manage a group of load balanced virtual machines.
    -  The number of virtual machine instances can automatically increase or decrease in response to demand or a defined schedule.
    -  Scale sets provide high availability to your applications, and allow you to centrally manage, configure, and update many virtual machines.
    -  Virtual machines in a scale set can also be deployed into multiple availability zones, a single availability zone, or regionally.

# Explore Azure Storage services
- Storing data is just the beginning—Azure makes it secure, scalable, and ready for action.
- **Blob Storage**: For unstructured data like media files, backups, or logs.
- **File Storage**: Cloud-based SMB file shares accessible via standard protocols.
- **Queue Storage**: Message storage for asynchronous app workflows.
- **Disk Storage**: High-performance block storage for VMs.
- Highlight redundancy options (LRS, GRS, ZRS) to showcase reliability and disaster recovery features.

## Explore Azure networking services
Networking is what connects it all. Azure’s global infrastructure keeps your services talking to each other—and to the world.
- **Virtual Network (VNet)**: Your private network space in the Azure cloud, like a company LAN.
- **Load Balancer**: Distributes incoming traffic across multiple resources for high availability.
- **Application Gateway**: Layer 7 (HTTP/HTTPS) load balancing with Web Application Firewall (WAF).
- **VPN Gateway & ExpressRoute**: Secure connections between on-premises and Azure—either over te internet or dedicated private lines.
- **Azure DNS & Traffic Manager**: Manage domain names and global user routing.

You can round off by mentioning how Azure’s integrated security and monitoring tools (like Network Watcher) help track, analyze, and optimize performance. 

## Module 3: Describe core solutions and management tools on Azure Lessons 
- Choose the best AI service for your needs
    - **Azure OpenAI Service**
          - **Best For:** Natural language understanding and generation
          - **Example Use Cases:** Chatbots, content creation, summarization, code generation
    - **Azure Cognitive Services**
          - Best For: Pre-built AI models for vision, speech, language, and decision-making	
          - Example Use Cases: Image analysis, speech-to-text, translation, sentiment analysis
    - **Azure Machine Learning**
          - Best For: Building, training, and deploying custom ML models	
          - Example Use Cases: Predictive analytics, fraud detection, recommendation systems
    - **Azure Bot Services**
            - Best For: Creating intelligent, conversational bots	
          - Example Use Cases: Customer support bots, virtual assistants
    - **Azure Cognitive Search**
          - Best For: AI-powered search over content	
          - Example Use Cases: Enterprise search, document indexing, knowledge mining
- Choose the best tools to help organizations build better solutions 
- Choose the best monitoring service for visibility, insight, and outage mitigation
    - Azure Monitor is the centralized monitoring service in Azure that provides full-stack observability across applications, infrastructure, and network
      resources.
## Module 4: Describe general security and network security features Lessons 
• Protect against security threats on Azure 
• Secure network connectivity on Azure 

## Module 5: Describe identity, governance, privacy, and compliance features Lessons 
• Secure access to your applications by using Azure identity services 
• Build a cloud governance strategy on Azure 
• Examine privacy, compliance, and data protection standards on Azure 

## Module 6: Describe Azure cost management and service level agreements Lessons 
• Plan and manage your Azure costs 
• Choose the right Azure services by examining SLAs and service lifecycle
