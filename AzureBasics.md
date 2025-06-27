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
      - **Users focus on application development without managing infrastructure.**
      - Examples: Google App Engine, Azure App Service.
    
  - **Software as a Service (SaaS)**
      - Delivers software applications via the cloud.
      - Users access apps through a browser; providers manage everything.
      - Examples: Microsoft 365, Salesforce, Google Workspace.
  
  - **Function as a Service (FaaS) / Serverless**
      - **Executes code in response to events without managing servers.**
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
      - **Logical containers** for managing and organizing related Azure resources.
  - **Azure Resource Manager (ARM)**
      - The deployment and management service for Azure.
      - Enables infrastructure as code and role-based access control.
  - **Subscriptions**
      - **Units of management, billing, and access control.**
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
  - > Availability Zones are physically separate locations **within an Azure region**, each with its own power, cooling, and networking.
    > They are designed to ensure high availability and fault tolerance for your applications and data.
    > Each Azure region with Availability Zones has at least **three separate zones**, allowing you to distribute your resources across them to protect against data
    > center-level failures.
  - **Key Benefits**
      - > **High Availability:** Ensures uptime even if one zone fails.
        > Fault Isolation: Each zone is independent, reducing the blast radius of failures.
        > D**ata Redundancy:** Supports zone-redundant services like Azure SQL Database and Azure Storage.
        > **Disaster Recovery:** Enables resilient architectures for mission-critical applications.
  
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
  - only lowercase letters accepted.
  - Storage primary serices include: Blob, File, Table and Queue.
  - Performance Tab has 2 options: Standard and Premium.
  - Redundancy has options:
    - LRS - Locally Redundant Storage
    - ZRS - Zone Redundant Storage
    - GRS - Region Redundant Storage
  - Enable Soft Delete for blobs: set to 7 days by default. 
  - Enable soft Delete for Containers: Set to 7 days by default. It is set to 7 days. File will be permanently deleted after 7 days, and it can be recovered in
    within 7 days.
  - Enable soft Delete for File Shares:
  - 
  - Go to Storage Accounts, and click on Create.
  - 
  - **Blob Storage**: For unstructured data like media files, backups, or logs.
    - 
    
  - **File Storage**: Cloud-based SMB file shares accessible via standard protocols.
  - **Queue Storage**: Message storage for asynchronous app workflows.
  - **Disk Storage**: High-performance block storage for VMs.
  - Highlight redundancy options (LRS, GRS, ZRS) to showcase reliability and disaster recovery features.
  
  ## Explore Azure networking services
  Networking is what connects it all. Azure’s global infrastructure keeps your services talking to each other—and to the world.
  - **Virtual Network (VNet)**: Your private network space in the Azure cloud, like a company LAN.
  - **Bastion:** Azure Bastion provides secure and seamless RDP/SSH connectivity to Azure virtual machines without exposing them to public internet threats. As a fully managed PaaS offering, it strengthens your
             network security while simplifying access management.
  - **VNET Peerng**: irtual Network (VNet) Peering in Azure enables seamless connectivity between two virtual networks, allowing resources to communicate across VNets with high bandwidth and low latency. It
                  simplifies network architecture by extending private IP communication while maintaining isolation and security boundaries.
  - **Load Balancer**: Distributes incoming traffic across multiple resources for high availability.
  - **Application Gateway**: Layer 7 (HTTP/HTTPS) load balancing with Web Application Firewall (WAF).
  - **VPN Gateway & ExpressRoute**: Secure connections between on-premises and Azure—either over te internet or dedicated private lines.
  - **Azure DNS & Traffic Manager**: Manage domain names and global user routing.
  
  You can round off by mentioning how Azure’s integrated security and monitoring tools (like Network Watcher) help track, analyze, and optimize performance. 
  
  # Module 3: Describe core solutions and management tools on Azure Lessons 
  - Choose the best AI service for your needs
      - **Azure OpenAI Service**
            - **Best For:** Natural language understanding and generation
            - **Example Use Cases:** Chatbots, content creation, summarization, code generation
            - Azure OpenAI service provides REST API access to OpenAI's powerfull language model including o1, o1-mini, GPT-4o, GPT-4o
              mini, GPT-4 Turbo with
              Vision, GPT-4, GPT-3.5.
            - These models can be easily adapted to your specific task including but not limited to content generation, summarization,
        image understaning
            - semantic search, and natural language to code translation.
        
      - **Azure Cognitive Services**
            - Best For: Pre-built AI models for vision, speech, language, and decision-making	
            - Example Use Cases: Image analysis, speech-to-text, translation, sentiment analysis
      - **Azure Machine Learning**
            - Best For: Building, training, and deploying custom ML models	
            - Example Use Cases: Predictive analytics, fraud detection, recommendation systems
      - **Azure Bot Services**
              - Best For: Creating intelligent, conversational bots	
            - Example Use Cases: Customer support bots, virtual assistants
            - Azure Bot Services is a managed platform for building, deploying, and managing intelligent bots that interact naturally with users across multiple
              channels.
            - **Key Features:**
            - **Bot Framework SDK:** Build conversational bots using rich tools and libraries.
            - **Multi-Channel Support:** Deploy bots to Teams, Web Chat, Facebook Messenger, and more.
            - **AI Integration:** Enhance conversations with Language Understanding (LUIS) and QnA Maker.
            - **Scalable Hosting:** Automatically scales with demand using Azure infrastructure.
            - **Security & Compliance:** Enterprise-grade authentication and data protection.
            - Search for "Azure Bot service" on the azure portal.
    
      - **Azure Cognitive Search**
            - Best For: AI-powered search over content	
            - Example Use Cases: Enterprise search, document indexing, knowledge mining
            - Azure Cognitive Search is a cloud-based search service
            - It enables developers to build rich search experiences over private, heterogeneous content.
            - **Key Features**
            - **Full-Text Search:** Fast and scalable search across large datasets.
            - **AI Enrichment:** Integrates with Cognitive Services to extract insights from raw content (e.g., OCR, entity recognition).
            - **Indexing:** Supports structured and unstructured data from sources like Azure Blob Storage, SQL, Cosmos DB.
            - **Faceted Navigation:** Enables filtering and drill-downs for better user experience.
            - **Security Trimming:** Ensures users see only what they’re authorized to access.
            - Search for "Azure Cognitive Search" on the azure portal and click create. 
  - Choose the best tools to help organizations build better solutions 
  - Choose the best monitoring service for visibility, insight, and outage mitigation
      - Azure Monitor is the centralized monitoring service in Azure that provides full-stack observability across applications, infrastructure, and network
        resources.
# Module 4: Describe general security and network security features Lessons 
 - Protect against security threats on Azure
   - Key Concepts
      - **Shared Responsibility Model**: Understand what security aspects are managed by Microsoft vs. the customer.
      - **Azure Security Center / Microsoft Defender for Cloud**:
        - Threat detection and response
        - Security posture management
      - **Role-Based Access Control (RBAC):**
        - Assigning least privilege access
        - Managing roles and permissions
      - **Azure Policy:**
        - Enforcing organizational standards
        - Compliance tracking
      - **Microsoft Entra ID (formerly Azure AD):**
        - Identity protection
        - Multi-Factor Authentication (MFA)
        - Conditional Access policies
      - **Key Vault:**
        - Securely storing secrets, keys, and certificates
  
  - **Secure network connectivity on Azure** 
    - Key Concepts
      - Virtual Networks (VNets):
      - Network segmentation
      - Subnets and IP addressing
    - **Network Security Groups (NSGs):**
      - Controlling inbound/outbound traffic
      - Rule-based access control
    - **Azure Firewall:**
      - Stateful packet inspection
      - Threat intelligence-based filtering
    - **Azure DDoS Protection:**
      - Mitigating distributed denial-of-service attacks
      - Private Endpoints & Service Endpoints:
      - Secure access to Azure services over private IPs
      - Azure DDoS Protection is a cloud-native service that helps protect your applications and resources from Distributed Denial of Service (DDoS) attacks.
      - It works by monitoring traffic patterns and automatically mitigating attacks in real time.
      - 
      - 
    - **VNET Peering:**
      - VNet Peering allows you to connect two Azure virtual networks seamlessly.
      - The networks appear as one for connectivity purposes, enabling direct traffic flow using private IP addresses.
      - Key Features
        - **Low Latency & High Bandwidth**: Traffic between peered VNets is routed through the Azure backbone, ensuring fast and reliable communication.
        - **Private Communication**: No need for gateways, public IPs, or Internet routing.
        - **Cross-Region Support**: Supports both intra-region and global VNet peering.
        - **Non-Transitive**: Peering is not transitive—if VNet A is peered with B, and B with C, A cannot communicate with C unless explicitly peered.
          
    - **VPN Gateway:**
      - Secure hybrid connectivity
      - Site-to-site and point-to-site VPNs
      - > Azure VPN Gateway is a type of virtual network gateway that sends encrypted traffic between an Azure virtual network and an on-premises location over
        > the public Internet. It enables secure cross-premises connectivity and site-to-site, point-to-site, and VNet-to-VNet connections.
      - Key Features of VPN Gateway
        - **Secure Communication**: Uses IPsec and IKE protocols to ensure encrypted and secure data transmission.
        - **Multiple Connection Types**:
        - **Site-to-Site VPN**: Connects entire networks.
        - **Point-to-Site VPN**: Connects individual clients to Azure.
        - **VNet-to-VNet VPN**: Connects virtual networks within Azure.
        - **High Availability**: Supports active-active configurations for improved reliability.
        - **Scalability**: Offers different SKUs (Basic, VpnGw1–5, etc.) to match performance and throughput needs.
        - **Integration**: Works seamlessly with Azure services like Azure Firewall, Network Security Groups, and ExpressRoute.   

      - **ExpressRoute:**
        - > Azure ExpressRoute is a service that enables private, dedicated network connectivity between your on-premises infrastructure and Microsoft Azure.
            Unlike VPN Gateway, ExpressRoute does not use the public Internet, offering more reliability, faster speeds, and lower latencies.
        - Key Features
          - **Private Connectivity**: Establishes a direct connection to Azure via a connectivity provider.
          - **High Performance**: Supports bandwidths from 50 Mbps up to 100 Gbps.
          - **Redundancy & SLA**: Offers built-in redundancy and a financially backed SLA for uptime.
          - **Global Reach**: Can connect to Microsoft cloud services across regions using ExpressRoute Global Reach.
          - **Integration**: Works with Azure services like Virtual Networks, Azure Site Recovery, and Microsoft 365 (with limitations).
            
# Module 5: Describe identity, governance, privacy, and compliance features Lessons 
- Secure access to your applications by using Azure identity services 
- Build a cloud governance strategy on Azure 
- Examine privacy, compliance, and data protection standards on Azure 
 - Azure Compliance Offerings
  - Over 100 compliance certifications globally
  - Key standards:
    - ISO/IEC 27001, 27017, 27018
    - SOC 1, 2, 3
    - GDPR, HIPAA, FedRAMP, IRAP
    - Azure Compliance Documentation Center
 - Data Protection in Azure
  - Encryption at rest and in transit
  - Customer-managed keys (CMK)
  - Azure Confidential Computing
  - Azure Key Vault for secrets and certificates
- Privacy Controls in Azure
  - Data residency and sovereignty options
  - Customer Lockbox for access control
  - Data Subject Requests (DSRs) support for GDPR
- Microsoft Priva for privacy risk management
  - Azure Policy and Compliance Manager
  - Define and enforce compliance policies
  - Monitor compliance posture
  - Automate remediation of non-compliant resources
- Shared Responsibility Model
   
# Module 6: Describe Azure cost management and service level agreements Lessons 
- Plan a  nd manage your Azure costs
  - Why Cost Management Matters
  - Cloud costs can spiral without governance
  - Budget overruns impact profitability
    - Cost visibility enables better planning and accountability
    - Azure Cost Management + Billing Overview
  
- Choose the right Azure services by examining SLAs and service lifecycle
- SLAs and lifecycle status are critical for service selection
  - Azure provides transparency and tools to guide decisions
  - Make choices that align with your reliability and support goals
- Why SLAs and Service Lifecycle Matter
  - Ensures reliability, availability, and supportability
  - Helps avoid technical debt and service deprecation risks
  - Aligns service choices with business continuity goals
- What is an SLA?
  - Service Level Agreement (SLA) defines:
  - Uptime guarantees (e.g., 99.9%)
  - Performance commitments
  - Compensation terms for SLA breaches
  - Example: Azure Virtual Machines offer 99.99% SLA with availability sets

- SLA Tiers in Azure
- !![image](https://github.com/user-attachments/assets/af20be0c-cb35-4e12-a0de-f7e214cfeb56)

- Service Lifecycle in Azure
  - Preview: Early access, not for production
  - General Availability (GA): Fully supported and SLA-backed
  - Deprecated/Retired: Scheduled for removal, no new features

- Tools to Help You Decide
  - Azure Service Health: Tracks outages and planned maintenance
  - Azure Advisor: Recommends reliable and cost-effective services
  - Azure Updates: Announces lifecycle changes and new features

- Best Practices
  - Prefer GA services for production workloads
  - Use availability zones and redundancy for high SLA targets
  - Monitor service health and subscribe to alerts
  - Plan for migration if a service is deprecated

