# 📖 Microsoft Azure Fundamentals AZ-900
Study notes for Microsoft certification AZ-900.
Sources:
- Linked Learning path: [Prepare for the Microsoft Azure Fundamentals (AZ-900) Certification Exam](https://www.linkedin.com/learning/paths/prepare-for-the-microsoft-azure-fundamentals-az-900-certification-exam?u=2216250)
  - [Cert Prep: 1 Cloud Concepts](https://www.linkedin.com/learning/microsoft-azure-fundamentals-az-900-cert-prep-1-cloud-concepts/hello-cloud-9706287?contextUrn=urn%3Ali%3AlyndaLearningPath%3A5d8bb5f9498e3236cc92196a&u=2216250)
  - [Cert Prep: 2 Azure Architecture and Security](https://www.linkedin.com/learning/microsoft-azure-fundamentals-az-900-cert-prep-2-azure-architecture-and-security/hello-azure?contextUrn=urn%3Ali%3AlyndaLearningPath%3A5d8bb5f9498e3236cc92196a&u=2216250)
- Microsoft Learning: [Microsoft Azure Fundamentals: Describe cloud concepts](https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)
___
## 📝 Exam curriculum

- Describe Cloud Concepts: 25-30%.
- Describe Azure Architecture and Services: 35-40%
- Describe Azure Management and Governance: 30-35%

### ☁️ What is Cloud Computing?

#### The traditional IT stack
![traditional it stack image](images/traditional-it-stack.jpg)

"Cloud computing is the delivery of any computing resources from the IT stack as a service, by a cloud service provider"

#### 🖥️ Virtualization

Virtualization is the core foundation of all cloud computing. It is basically the creation of virtual **processor**, **memory**, and **hard disk**. This enables the delivery of those components  over the network. Also provides isolation between instances of virtualized resources.

#### 🌨️ Key characteristics of Cloud Computing
![traditional it stack image](images/four-characteristic-of-cloud-computing.jpg)

**1. Resource pooling:** Large pool of virtualized computing resources
**2. Elasticity:** Enables increasing and decreasing the provisioned resources as demand varies.
**3. Pay per use:** You pay only for the resources you use and the time you use them for
**4. Automation:** Enables the user to provision resources on demand and perform self-service on resources without depending on anyone. Neither the CSP, tech support, nor anybody else

#### 💽 Cloud computing offering models

There are 3 cloud service models of how computing resources can be offered to customers. Azure provides all 3.
##### 1. Infrastructure-as-a-Service (IaaS)

![traditional it stack image](images/infrastructure-as-a-service.jpg)

The cloud provides access to virtualized hardware resources. The customer gets maximum control of the application environment, but it must handle a bigger part of the stack (OS, frameworks, etc).

##### 2. Platform-as-a-Service (PaaS)

![traditional it stack image](images/platform-as-a-service.jpg)

Customer can get up and running with their application quickly without having to deal with unnecessary configuration. The disadvantage is less control of the environment. It is the most popular cloud service offering among businesses.

##### 2. Software-as-a-Service (SaaS)

![traditional it stack image](images/software-as-a-service.jpg)

Cloud provides the application configured and ready to use. Usually only the most popular applications are available.

##### Shared Responsibility Model

![traditional it stack image](images/shared-respon.jpg)

Both the Customer and Cloud Service Provider are responsible for the application uptime and security. The share of responsibility each of them bears varies depending on the type of service model.

## 🌥️ Types of Cloud Computing

### 1. Public Cloud

Offers services to many customers often over the public internet. Open to anyone to pay for and consume. Organizations that consume these services are called tenants. It is a multi-tenant cloud. Very economical because public cloud providers run on a low cost-high volume strategy.

### 2. Private Cloud

Some companies have policies that limits the use of public Clouds for various reasons (compliance, data center location, laws, security). A private Cloud is when the whole stack is created and managed by the organization. But why? It can deliver efficiency, streamlining process, striving for operational excellence and implement best practices. Usually only medium or large enterprises uses private Cloud because of the cost, technical complexity, and effort involved. Some venders can setup and hand over private Clouds. In Microsoft, this service is called Azure Stack.

### 3. Hybrid Cloud

Combination of Public and Private Cloud.
### 4. Sovereign Cloud

Used by National Governments to process and store sensitive information.

## ✅ Benefits of Cloud Computing

### 👟 Elasticity

To be considered elastic, the infrastructure pool must be able to assign resources to an application, provide extra resources when an application requests it, and reclaim it when the application does not need it anymore. A cloud should always have an elastic infrastructure. And, therefore, elasticity is a core benefit of the cloud. The cloud service provider is responsible for ensuring elasticity in all three service models, IaaS, PaaS, and SaaS. Remember, elasticity is an attribute of the infrastructure.

### 