# **MicroHack Azure Arc for Servers**

- [**MicroHack introduction**](#MicroHack-introduction)
  - [What is Azure Arc?](#what-is-azure-arc)
- [**MicroHack context**](#microhack-context)
- [**Objectives**](#objectives)
- [**MicroHack Challenges**](#microhack-challenges)
  - [General prerequisites](#general-prerequisites)
  - [Challenge 1 - Azure Arc prerequisites & onboarding](#challenge-1---azure-arc-prerequisites--onboarding)
  - [Challenge 2 - Azure Monitor integration](#challenge-2---azure-monitor-integration)
  - [Challenge 3 - Access Azure resources using Managed Identities from your on-premises servers](#challenge-3---access-azure-resources-using-managed-identities-from-your-on-premises-servers)
  - [Challenge 4 - Microsoft Defender for Cloud integration with Azure Arc](#challenge-4---microsoft-defender-for-cloud-integration-with-azure-arc)
  - [Challenge 5 - Azure Automanage Machine Configuration](#challenge-5---azure-automanage-machine-configuration)
- [**Contributors**](#contributors)

## MicroHack introduction

### What is Business Continuity?

Describe Business Continuity....

![image](./img/drcontinuum.png)

## MicroHack context

This MicroHack scenario walks through the use of building a Business Continuity Strategy with a focus on the best practices and the design principles and some interesting challenges for real world scenarios. Specifically, this builds up to include working with an existing infrastructure in your datacenter.

Further resources: 

*[Azure Business Continuity & Disaster Recovery]()
*[Azure Business Continuity & Disaster Recovery](https://learn.microsoft.com/en-us/azure/azure-arc/overview)

💡 Optional: Read this after completing this lab to deepen the learned!

## Objectives

After completing this MicroHack you will:

* Know how to use the right business continuity strategy for your infrastructure or your particular workload
* Understand use cases and possible scenarios in your business continuity & disaster recovery strategy 
* Get insights into real world challenges and scenarios

## MicroHack Challenges

### General prerequisites

This MicroHack has a few but important prerequisites to be understood before starting this lab!

* Your own Azure subscription with Owner RBAC rights at the subscription level
  * [Azure Evaluation free account](https://azure.microsoft.com/en-us/free/search/?OCID=AIDcmmzzaokddl_SEM_0fa7acb99db91c1fb85fcfd489e5ca6e:G:s&ef_id=0fa7acb99db91c1fb85fcfd489e5ca6e:G:s&msclkid=0fa7acb99db91c1fb85fcfd489e5ca6e)
* 

## Challenge 1 - Prerequisites and landing zone preperation 

### Goal

In challenge 1 you will understand and prepare your environemnt for onboarding of the infrastructure to enable business continuity with Cloud Native / PaaS Services on Azure

### Actions

* 

### Success criteria

* 

### Learning resources

* 

* 

### Solution - Spoilerwarning

[Solution Steps](./walkthrough/challenge-1/solution.md)

## Challenge 2 - Protect in Azure - Backup / Restore 

### Goal

In challenge 2 you will successfully onboard your Windows and Linux Virtual Machines to a centralized Recovery Services Vault and leverage Azure Backup Center to Protect with Backup in Azure. 

### Actions

* Create all necessary Azure Resources
*


### Success criteria

* You have an Recovery Services Vault
* You successfully enabled Azure Backup on two virtual machines
* 

### Learning resources

* 


### Solution - Spoilerwarning

[Solution Steps](./walkthrough/challenge-2/solution.md)

## Challenge 3 - Protect in Azure with Disaster Recovery 

### Goal

### Actions

* Use Azure Site Recovery to...

### Success Criteria

* You successfully initiated a Testfailover and a production failover from Azure Region West Europe to North Europe with a near zero downtime requirement 

### Learning resources

* 

### Solution - Spoilerwarning

[Solution Steps](./walkthrough/challenge-3/solution.md)

## Challenge 4 - Protect to Azure with Azure Backup & Restore 

### Goal

* 

### Actions

* 

### Success criteria

* You successfully installed Azure backup Server in you on prem infrastructure and enabled it for two virtual machines 

### Learning resources

* 

### Solution - Spoilerwarning

[Solution Steps](./walkthrough/challenge-4/solution.md)

## Challenge 5 - Protect to Azure with Disaster Recovery 

### Actions

* 

### Success criteria

*

### Learning resources

* 

### Solution - Spoilerwarning

[Solution Steps](./walkthrough/challenge-5/solution.md)

## Finish

Congratulations! You finished the MicroHack Business Continuity / Disaster Recovery. We hope you had the chance to learn about the how to implement a successful DR strategy to protect resources in Azure and to Azure. 
If you want to give feedback please dont hesitate to open an Issue on the repository or get in touch with one of us directly.

Thank you for investing the time and see you next time!


## Contributors
* Markus Klein 
* Bernd Loehlein 
*Hengameh 
* Tara
* Nils Bankert [GitHub](https://github.com/nilsbankert); [LinkedIn](https://www.linkedin.com/in/nilsbankert/)

