source #source/azure-documentation [exam-az-204](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-204)
area #area/programming
subject #subject/csharp/exam
type #destilled 
related-notes

# Study guide for Exam AZ-204: Developing Solutions for Microsoft Azure

## Purpose of this document

This study guide should help you understand what to expect on the exam and includes a summary of the topics the exam might cover and links to additional resources. The information and materials in this document should help you focus your studies as you prepare for the exam.

| Useful links                                                                                                                                                              | Description                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| [How to earn the certification](https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/)                                                            | Some certifications only require passing one exam, while others require passing multiple exams.                                                      |
| [Certification renewal](https://learn.microsoft.com/en-us/credentials/certifications/renew-your-microsoft-certification)                                                  | Microsoft associate, expert, and specialty certifications expire annually. You can renew by passing a **free** online assessment on Microsoft Learn. |
| [Your Microsoft Learn profile](https://learn.microsoft.com/en-us/users)                                                                                                   | Connecting your certification profile to Microsoft Learn allows you to schedule and renew exams and share and print certificates.                    |
| [Exam scoring and score reports](https://learn.microsoft.com/en-us/credentials/certifications/exam-scoring-reports)                                                       | A score of 700 or greater is required to pass.                                                                                                       |
| [Exam sandbox](https://aka.ms/examdemo)                                                                                                                                   | You can explore the exam environment by visiting our exam sandbox.                                                                                   |
| [Request accommodations](https://learn.microsoft.com/en-us/credentials/certifications/request-accommodations)                                                             | If you use assistive devices, require extra time, or need modification to any part of the exam experience, you can request an accommodation.         |
| [Take a free Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-204/practice/assessment?assessment-type=practice&assessmentId=35) | Test your skills with practice questions to help you prepare for the exam.                                                                           |

## Updates to the exam

Our exams are updated periodically to reflect skills that are required to perform a role.

We always update the English language version of the exam first. Some exams are localized into other languages, and those are updated approximately eight weeks after the English version is updated. Other available languages are listed in the **Schedule Exam** section of the **Exam Details** webpage. If the exam isn't available in your preferred language, you can request an additional 30 minutes to complete the exam.

#### Note

The bullets that follow each of the skills measured are intended to illustrate how we are assessing that skill. Related topics may be covered in the exam.

#### Note

Most questions cover features that are general availability (GA). The exam may contain questions on Preview features if those features are commonly used.

## Skills measured as of January 14, 2026

### Audience profile

As a candidate for this exam, you’re responsible for participating in all phases of development, including requirements gathering, design, development, deployment, security, maintenance, performance tuning, and monitoring.

You should be proficient in Azure:
- [[SDKs]]
    
- Data storage options
    
- Data connections
    
- APIs
    
- App authentication and authorization
    
- Compute and container deployment
    
- Debugging
    

To implement solutions, you partner with:

- Cloud solution architects
    
- DBAs
    
- DevOps
    
- Infrastructure admins
    
- Other stakeholders
    

You should have:

- At least two years of programming experience.
    
- Proficiency in programming with Azure SDKs.
    
- Proficiency using Azure CLI, Azure PowerShell, and other tools.
    

### Skills at a glance

- Develop Azure compute solutions (25–30%)
    
- Develop for Azure storage (15–20%)
    
- Implement Azure security (15–20%)
    
- Monitor, troubleshoot, and optimize Azure solutions (5–10%)
    
- Connect to and consume Azure services and third-party services (20–25%)
    

### Develop Azure compute solutions (25–30%)


#### Implement containerized solutions

- Create and manage container images for solutions
    
- Publish an image to Azure Container Registry
    
- Run containers by using Azure Container Instances
    
- Create solutions by using Azure Container Apps
    

#### Implement Azure App Service Web Apps

- Create an Azure App Service Web App
    
- Configure and implement diagnostics and logging
    
- Deploy code and containerized solutions
    
- Configure settings including Transport Layer Security (TLS), API settings, and service connections
    
- Implement autoscaling
    
- Configure deployment slots
    
#### Implement Azure Functions

- Create and configure an Azure Functions app
    
- Implement input and output bindings
    
- Implement function triggers by using data operations, timers, and webhooks
    

### Develop for Azure storage (15–20%)

#### Develop solutions that use Azure Cosmos DB

- Perform operations on containers and items by using the SDK
    
- Set the appropriate consistency level for operations
    
- Implement change feed notifications
    
#### Develop solutions that use Azure Blob Storage

- Set and retrieve properties and metadata
    
- Perform operations on data by using the appropriate SDK
    
- Implement storage policies and data lifecycle management
    
### Implement Azure security (15–20%)
#### Implement user authentication and authorization

- Authenticate and authorize users by using the Microsoft Identity platform
    
- Authenticate and authorize users and apps by using Microsoft Entra ID
    
- Create and implement shared access signatures
    
- Implement solutions that interact with Microsoft Graph
    
#### Implement secure Azure solutions

- Secure app configuration data by using Azure App Configuration or Azure Key Vault
    
- Develop code that uses keys, secrets, and certificates stored in Azure Key Vault
    
- Implement Managed Identities for Azure resources
    
### Monitor and troubleshoot Azure solutions (5–10%)
#### Monitor and troubleshoot solutions by using Azure Monitor Application Insights

- Monitor and analyze metrics, logs, and traces
    
- Implement availability tests and alerts
    
- Instrument an app or service to use Application Insights
    
### Connect to and consume Azure services and third-party services (20–25%)

#### Implement Azure API Management

- Create an Azure API Management instance
    
- Create and document APIs
    
- Configure access to APIs
    
- Implement policies for APIs
    
#### Develop event-based solutions

- Implement solutions that use Azure Event Grid
    
- Implement solutions that use Azure Event Hubs
    
#### Develop message-based solutions

- Implement solutions that use Azure Service Bus
    
- Implement solutions that use Azure Queue Storage
    

## Study resources

We recommend that you train and get hands-on experience before you take the exam. We offer self-study options and classroom training as well as links to documentation, community sites, and videos.

| Study resources        | Links to learning and documentation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Get trained            | [Choose from self-paced learning paths and modules or take an instructor-led course](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-204#two-ways-to-prepare)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Find documentation     | [Azure documentation](https://learn.microsoft.com/en-us/azure/?product=featured)  <br>[Container Registry](https://learn.microsoft.com/en-us/azure/container-registry/)  <br>[Container Instances](https://learn.microsoft.com/en-us/azure/container-instances/)  <br>[App Service](https://learn.microsoft.com/en-us/azure/app-service/)  <br>[Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/)  <br>[Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/)  <br>[Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/)  <br>[Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/active-directory/)  <br>[Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/)  <br>[Azure Cache for Redis](https://learn.microsoft.com/en-us/azure/azure-cache-for-redis/)  <br>[API Apps](https://learn.microsoft.com/en-us/azure/app-service/)  <br>[API Management](https://learn.microsoft.com/en-us/azure/api-management/)  <br>[Event Hubs](https://learn.microsoft.com/en-us/azure/event-hubs/)  <br>[Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/)  <br>[Service Bus Messaging](https://learn.microsoft.com/en-us/azure/service-bus-messaging/)  <br>[Queue Storage](https://learn.microsoft.com/en-us/azure/storage/queues/) |
| Ask a question         | [Microsoft Q&A \| Microsoft Docs](https://learn.microsoft.com/en-us/answers/products/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Get community support  | [Azure Community Support](https://azure.microsoft.com/support/community/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Follow Microsoft Learn | [Microsoft Learn - Microsoft Tech Community](https://techcommunity.microsoft.com/t5/microsoft-learn/ct-p/MicrosoftLearn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Find a video           | [Exam Readiness Zone](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/?terms=az-204)  <br>[Azure Fridays](https://azure.microsoft.com/resources/videos/azure-friday/)  <br>[Browse other Microsoft Learn shows](https://learn.microsoft.com/en-us/shows/browse)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

## Change log

The table below summarizes the changes between the current and previous version of the skills measured. The functional groups are in bold typeface followed by the objectives within each group. The table is a comparison between the previous and current version of the exam skills measured and the third column describes the extent of the changes.

|Skill area prior to January 14, 2026|Skill area as of January 14,2026|Change|
|---|---|---|
|Audience profile||No change|
|**Monitor and troubleshoot Azure solutions**|**Monitor and troubleshoot Azure solutions**|No % change|
|Monitor and troubleshoot solutions by using Application Insights|Monitor and troubleshoot solutions by using Azure Monitor Application Insights|Minor|
|**Connect to and consume Azure services and third-party services**|**Connect to and consume Azure services and third-party services**|No % change|
|Develop message-based solutions|Develop message-based solutions|Minor|

---

## Additional resources

Documentation

- [Level up with Microsoft Certified: Azure Developer Associate](https://learn.microsoft.com/en-us/credentials/certifications/posts/level-up-with-microsoft-certified-azure-developer-associate?source=recommendations)
    
    Level up with Microsoft Certified: Azure Developer Associate
    
- [Azure developers, beta exam AZ-204 is just for you](https://learn.microsoft.com/en-us/credentials/certifications/posts/azure-developers-beta-exam-az-204-is-just-for-you?source=recommendations)
    
    Azure developers, beta exam AZ-204 is just for you
    
- [Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-204/practice/assessment?source=recommendations)
    
    Practice Assessment
    
- [Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/practice/assessment?source=recommendations)
    
    Practice Assessment
    

Training

Module

[Plan and Implement Advanced Security for Compute - Training](https://learn.microsoft.com/en-us/training/modules/advanced-security-compute/?source=recommendations)

This module is designed to provide administrators with the knowledge and skills needed to plan and implement advanced security measures for Azure compute resources, safeguarding applications and data against evolving security threats.

Certification

[Microsoft Certified: Azure Developer Associate - Certifications](https://learn.microsoft.com/en-us/credentials/certifications/azure-developer/?source=recommendations)

Build end-to-end solutions in Microsoft Azure to create Azure Functions, implement and manage web apps, develop solutions utilizing Azure storage, and more.

Events

[Microsoft AI Tour](https://aka.ms/AITourLearnQBGHP)

Dec 16, 1 PM - May 26, 1 PM

Take your business to the AI frontier with the Microsoft AI Tour

[Free to join. Request to attend](https://aka.ms/AITourLearnQBGHP)