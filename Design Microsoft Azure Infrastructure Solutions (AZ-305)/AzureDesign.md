# Design Microsoft Azure Infrastructure Solutions (AZ-305)

## Contents

[Course Introduction](#course-introduction) (8)

[Module 1: Governance](#module-1-governance) (27)

[Module 2: Compute](#module-2-compute) (39)

[Module 3: Non-relational storage](#module-3-non-relational-storage) (38)

[Module 4: RDBS](#module-4-rdbs) (40)

[Module 5: Data integration](#module-5-data-integration) (27)

[Module 6: App architecture](#module-6-app-architecture) (42)

[Module 7: Identity](#module-7-identity) (24)

[Module 8: Monitor/Log](#module-8-monitorlog) (14)

[Module 9: Network](#module-9-network) (38)

[Module 10: BCDR](#module-10-bcdr) (34)

[Module 11: Migrate](#module-11-migrate) (18)

## Course Introduction

[About this course](<https://learn.microsoft.com/learn/browse/?WT.mc_id=AZ-MVP-5002880?term=fundamentals&terms=fundamentals&products=azure>)

[Exam AZ-305: Designing Microsoft Azure Infrastructure Solutions](<https://learn.microsoft.com/credentials/certifications/exams/az-305/?WT.mc_id=AZ-MVP-5002880>)

[AZ-305 Case Study GitHub](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/?WT.mc_id=AZ-MVP-5002880>)

[The cloud adoption journey](<https://azure.microsoft.com/cloud-adoption-framework/?WT.mc_id=AZ-MVP-5002880#cloud-adoption-journey>)

[Azure Migrate overview](<https://learn.microsoft.com/azure/cloud-adoption-framework/migrate/azure-migration-guide?WT.mc_id=AZ-MVP-5002880>)

[Microsoft Cloud Adoption Framework for Azure](<https://learn.microsoft.com/learn/modules/microsoft-cloud-adoption-framework-for-azure/?WT.mc_id=AZ-MVP-5002880>)

[Microsoft Azure Well-Architected Framework](<https://learn.microsoft.com/azure/cloud-adoption-framework/?WT.mc_id=AZ-MVP-5002880>)

[Build great solutions with the Microsoft Azure Well-Architected Framework](<https://learn.microsoft.com/azure/well-architected/?WT.mc_id=AZ-MVP-5002880>)

## Module 1: Governance

[Design governance](<https://learn.microsoft.com/training/modules/design-governance/?WT.mc_id=AZ-MVP-5002880>)

[Exam page](<https://learn.microsoft.com/learn/certifications/exams/az-305?WT.mc_id=AZ-MVP-5002880>)

[Why is governance important?](<https://learn.microsoft.com/azure/cloud-adoption-framework/govern/methodology?WT.mc_id=AZ-MVP-5002880>)

[Azure governance documentation](<https://learn.microsoft.com/azure/governance/?WT.mc_id=AZ-MVP-5002880>)

[Overview of Azure subscriptions, management groups, and resources](<https://learn.microsoft.com/learn/modules/azure-architecture-fundamentals/overview?WT.mc_id=AZ-MVP-5002880>)

[Organize your Azure resources effectively](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/azure-setup-guide/?WT.mc_id=AZ-MVP-5002880organize-resources?tabs=AzureManagementGroupsAndHierarchy>)

[How would you organize your management groups? By department/geography/product line/…](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/design-area/resource-org-management-groups?WT.mc_id=AZ-MVP-5002880>)

[Why should you consider a top-level management group?](<https://learn.microsoft.com/learn/modules/design-governance/3-design-for-management-groups?WT.mc_id=AZ-MVP-5002880>)

[Why should you consider a top-level management group?](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/design-area/resource-org-management-groups?WT.mc_id=AZ-MVP-5002880#management-groups-in-the-azure-landing-zone-accelerator>)

[Management groups – whiteboard and discussion (notes)](<https://learn.microsoft.com//azure/governance/management-groups/overview#management-group-access?WT.mc_id=AZ-MVP-5002880>)

[What are Azure management groups?](<https://learn.microsoft.com/azure/governance/management-groups/overview?WT.mc_id=AZ-MVP-5002880>)

[How will you decide how many subscriptions your organization needs?](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/scale-subscriptions?WT.mc_id=AZ-MVP-5002880>)

[Will you use a centralized or decentralized approach to subscriptions?](<https://learn.microsoft.com/azure/cloud-adoption-framework/manage/centralize-operations?WT.mc_id=AZ-MVP-5002880>)

[Subscription decision guide](<https://learn.microsoft.com/azure/cloud-adoption-framework/decision-guides/subscriptions/?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Resource Manager](<https://docs.microsoft.com/azure/azure-resource-manager/management/overview?WT.mc_id=AZ-MVP-5002880>)

[Resource naming and tagging decision guide](<https://learn.microsoft.com/azure/cloud-adoption-framework/decision-guides/resource-tagging/?WT.mc_id=AZ-MVP-5002880>)

[Define your tagging strategy](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/resource-tagging?WT.mc_id=AZ-MVP-5002880>)

[Resource tagging patterns](<https://learn.microsoft.com/azure/cloud-adoption-framework/decision-guides/resource-tagging/?toc=/azure/azure-resource-manager/management/toc.json?WT.mc_id=AZ-MVP-5002880#resource-tagging-patterns>)

[What is Azure Policy](<https://learn.microsoft.com/azure/governance/policy/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Built-in Policy List](<https://learn.microsoft.com/azure/governance/policy/samples/built-in-policies?WT.mc_id=AZ-MVP-5002880#general>)

[Only grant the access users need](<https://learn.microsoft.com/azure/role-based-access-control/best-practices#only-grant-the-access-users-need>)

[Limit the number of subscription owners](<https://learn.microsoft.com/azure/role-based-access-control/best-practices#limit-the-number-of-subscription-owners>)

[Microsoft Entra Privileged Identity Management](<https://learn.microsoft.com/azure/role-based-access-control/best-practices#use-azure-ad-privileged-identity-management>)

[Assign roles to groups, not users](<https://learn.microsoft.com/azure/role-based-access-control/best-practices#assign-roles-to-groups-not-users>)

[What are Azure Landing Zones](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/?WT.mc_id=AZ-MVP-5002880>)

[Choose the best Azure landing zone to support your requirements for cloud operations](<https://learn.microsoft.com/learn/modules/cloud-adoption-framework-ready/?WT.mc_id=AZ-MVP-5002880>)

[Case study – Cost and Accounting](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/01-Governance.html>)

## Module 2: Compute

[Design a compute solution](<https://learn.microsoft.com/training/modules/design-compute-solution/?WT.mc_id=AZ-MVP-5002880>)

[Choose an Azure compute service for your application](<https://learn.microsoft.com/azure/architecture/guide/technology-choices/compute-decision-tree?WT.mc_id=AZ-MVP-5002880>)

[Who is responsible for your VM? Microsoft or the customer?](<https://learn.microsoft.com/azure/security/fundamentals/shared-responsibility?WT.mc_id=AZ-MVP-5002880>)

[I need to run a database. Which VM size should I use?](<https://learn.microsoft.com/azure/virtual-machines/sizes?WT.mc_id=AZ-MVP-5002880>)

[Managed disks versus unmanaged disks?](<https://learn.microsoft.com/azure/virtual-machines/managed-disks-overview?WT.mc_id=AZ-MVP-5002880>)

[Virtual machines in Azure](<https://learn.microsoft.com/azure/virtual-machines/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Well-Architected Framework perspective on Virtual Machines and scale sets](<https://learn.microsoft.com/azure/well-architected/service-guides/virtual-machines?WT.mc_id=AZ-MVP-5002880>)

[There are VM selector tools](<https://aka.ms/vm-selector>)

[My VM Scale Set needs high availability. What are my options?](<https://learn.microsoft.com/azure/virtual-machines/availability?WT.mc_id=AZ-MVP-5002880>)

[I need to deploy my application to VM Scale Set. What are my options?](<https://learn.microsoft.com/azure/virtual-machines/shared-image-galleries?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Batch?](<https://learn.microsoft.com/azure/batch/batch-technical-overview?WT.mc_id=AZ-MVP-5002880>)

[Best practices - Azure Batch | Microsoft Docs](<https://learn.microsoft.com/azure/batch/best-practices?WT.mc_id=AZ-MVP-5002880>)

[What is it that I pay for with an Azure App Service?](<https://learn.microsoft.com/azure/app-service/overview-hosting-plans?WT.mc_id=AZ-MVP-5002880#how-much-does-my-app-service-plan-cost>)

[What is it that I pay for with an Azure App Service?](<https://learn.microsoft.com/azure/app-service/overview-manage-costs?WT.mc_id=AZ-MVP-5002880#understand-the-full-billing-model-for-azure-app-service>)

[Why would I consider deployment slots?](<https://learn.microsoft.com/azure/app-service/deploy-staging-slots?WT.mc_id=AZ-MVP-5002880>)

[Azure App Service –whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/app-service/quickstart-custom-container?tabs=dotnet&pivots=container-linux?WT.mc_id=AZ-MVP-5002880>)

[What are WebJobs? Why would I use WebJobs?](<https://learn.microsoft.com/azure/app-service/webjobs-create?WT.mc_id=AZ-MVP-5002880>)

[Azure Container Instances](<https://learn.microsoft.com/azure/container-instances/container-instances-overview?WT.mc_id=AZ-MVP-5002880>)

[Security considerations for container instances](<https://learn.microsoft.com/azure/container-instances/container-instances-image-security?WT.mc_id=AZ-MVP-5002880>)

[Containers vs. virtual machines](<https://learn.microsoft.com/virtualization/windowscontainers/about/containers-vs-vm?WT.mc_id=AZ-MVP-5002880>)

[Who manages the Kubernetes cluster?](<https://learn.microsoft.com/azure/aks/concepts-clusters-workloads?WT.mc_id=AZ-MVP-5002880>)

[What do you pay for?](<https://azure.microsoft.com/pricing/details/kubernetes-service/?WT.mc_id=AZ-MVP-5002880>)

[What methods exist to scale your AKS application?](<https://learn.microsoft.com/azure/aks/concepts-scale?WT.mc_id=AZ-MVP-5002880>)

[How can I isolate workloads inside my AKS cluster?](<https://learn.microsoft.com/azure/aks/operator-best-practices-cluster-isolation?WT.mc_id=AZ-MVP-5002880>)

[What is AKS](<https://learn.microsoft.com/azure/aks/intro-kubernetes?WT.mc_id=AZ-MVP-5002880>)

[Considerations for Azure Kubernetes Services](<https://learn.microsoft.com/azure/aks/best-practices?WT.mc_id=AZ-MVP-5002880>)

[Azure Functions Overview](<https://learn.microsoft.com/azure/azure-functions/functions-overview?WT.mc_id=AZ-MVP-5002880>)

[Why would I consider Azure Functions? Do you have some scenarios?](<https://learn.microsoft.com/azure/azure-functions/functions-scenarios?WT.mc_id=AZ-MVP-5002880>)

[What are durable functions and why should I consider these?](<https://learn.microsoft.com/azure/azure-functions/durable/durable-functions-overview?WT.mc_id=AZ-MVP-5002880>)

[Best practices for reliable Azure Functions](<https://learn.microsoft.com/azure/azure-functions/functions-best-practices?WT.mc_id=AZ-MVP-5002880>)

[Why would I consider Logic Apps? Do you have some scenarios?](<https://learn.microsoft.com/azure/logic-apps/logic-apps-overview?WT.mc_id=AZ-MVP-5002880>)

[What are some differences between a Logic App and Azure Functions?](<https://learn.microsoft.com/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs?WT.mc_id=AZ-MVP-5002880#compare-azure-functions-and-azure-logic-apps>)

[Azure Logic App](<https://learn.microsoft.com/azure/logic-apps/?WT.mc_id=AZ-MVP-5002880>)

[Choose the right integration and automation services in Azure](<https://learn.microsoft.com/azure/azure-functions/functions-compare-logic-apps-ms-flow-webjobs?WT.mc_id=AZ-MVP-5002880>)

[Case Study – Compute](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/02-Compute.html?WT.mc_id=AZ-MVP-5002880>)

[Run a Windows VM on Azure](<https://learn.microsoft.com/azure/architecture/reference-architectures/n-tier/windows-vm?WT.mc_id=AZ-MVP-5002880>)

[Run a Linux VM on Azure](<https://learn.microsoft.com/azure/architecture/reference-architectures/n-tier/linux-vm?WT.mc_id=AZ-MVP-5002880>)

[Basic web application](<https://learn.microsoft.com/azure/architecture/reference-architectures/app-service-web-app/basic-web-app?WT.mc_id=AZ-MVP-5002880>)

[Pipeline for container-based workloads](<https://learn.microsoft.com/azure/architecture/example-scenario/apps/devops-with-aks?WT.mc_id=AZ-MVP-5002880>)

## Module 3: Non-relational storage

[Design a non-relational data storage solution](<https://learn.microsoft.com/training/modules/design-data-storage-solution-for-non-relational-data/?WT.mc_id=AZ-MVP-5002880>)

[Introduction to the core Azure Storage services](<https://learn.microsoft.com/azure/storage/common/storage-introduction?WT.mc_id=AZ-MVP-5002880>)

[Types of storage accounts](<https://learn.microsoft.com/azure/storage/common/storage-account-overview#types-of-storage-accounts?WT.mc_id=AZ-MVP-5002880>)

[Performance tiers for block blob storage](<https://learn.microsoft.com/azure/storage/blobs/storage-blob-performance-tiers?WT.mc_id=AZ-MVP-5002880#premium-performance>)

[Overview of Azure page blobs](<https://learn.microsoft.com/azure/storage/blobs/storage-blob-pageblob-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure storage redundancy](<https://learn.microsoft.com/azure/storage/common/storage-redundancy?WT.mc_id=AZ-MVP-5002880>)

[Access tiers for blob data](<https://learn.microsoft.com/azure/storage/blobs/access-tiers-overview?WT.mc_id=AZ-MVP-5002880>)

[Optimize costs by automatically managing the data lifecycle](<https://learn.microsoft.com/azure/storage/blobs/lifecycle-management-overview?WT.mc_id=AZ-MVP-5002880>)

[Store business-critical blob data with immutable storage](<https://learn.microsoft.com/azure/storage/blobs/immutable-storage-overview?WT.mc_id=AZ-MVP-5002880>)

[When would you use Azure Files instead of Azure Blob storage?](<https://learn.microsoft.com/azure/storage/common/storage-introduction?WT.mc_id=AZ-MVP-5002880#example-scenarios>)

[Which file storage tiers would you choose in different scenarios?](<https://learn.microsoft.com/azure/storage/files/storage-files-planning?WT.mc_id=AZ-MVP-5002880#storage-tiers>)

[Why would I consider Azure NetApp files?](<https://learn.microsoft.com/azure/azure-netapp-files/azure-netapp-files-introduction?WT.mc_id=AZ-MVP-5002880>)

[Why would I consider Azure NetApp files?](<https://learn.microsoft.com/azure/storage/files/storage-files-netapp-comparison?WT.mc_id=AZ-MVP-5002880>)

[Compare access to Azure Files, Blob Storage, and Azure NetApp Files with NFS](<https://learn.microsoft.com/azure/storage/common/nfs-comparison?WT.mc_id=AZ-MVP-5002880>)

[Solution architectures using Azure NetApp Files](<https://learn.microsoft.com/azure/azure-netapp-files/azure-netapp-files-solution-architectures?WT.mc_id=AZ-MVP-5002880>)

[When to use Azure NetApp Files](<https://learn.microsoft.com/learn/modules/introduction-to-azure-netapp-files/4-when-to-use-azure-netapp-files?WT.mc_id=AZ-MVP-5002880>)

[How will you decide which disk type to choose for your application?](<https://learn.microsoft.com/azure/virtual-machines/disks-types#disk-type-comparison?WT.mc_id=AZ-MVP-5002880>)

[How would you decide between the different types of disk encryption?](<https://learn.microsoft.com/azure/virtual-machines/disk-encryption-overview?WT.mc_id=AZ-MVP-5002880>)

[What features can you use to improve disk performance?](<https://learn.microsoft.com/azure/virtual-machines/premium-storage-performance#disk-striping?WT.mc_id=AZ-MVP-5002880>)

[What disk types are available in Azure?](<https://learn.microsoft.com/azure/virtual-machines/disks-types?WT.mc_id=AZ-MVP-5002880>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/storage-account-keys-manage?WT.mc_id=AZ-MVP-5002880>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/storage-sas-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/storage-network-security?WT.mc_id=AZ-MVP-5002880?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=azure-portal>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/storage-private-endpoints?WT.mc_id=AZ-MVP-5002880?toc=/azure/storage/blobs/toc.json>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/transport-layer-security-configure-minimum-version?WT.mc_id=AZ-MVP-5002880?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=portal>)

[Azure storage security – discussion and whiteboard](<https://learn.microsoft.com/azure/storage/common/storage-require-secure-transfer?WT.mc_id=AZ-MVP-5002880?toc=/azure/storage/blobs/toc.json>)

[Security recommendations for Blob storage](<https://learn.microsoft.com/azure/storage/blobs/security-recommendations?WT.mc_id=AZ-MVP-5002880>)

[Use private endpoints for Azure Storage](<https://learn.microsoft.com/azure/storage/common/storage-private-endpoints?WT.mc_id=AZ-MVP-5002880>)

[Customer-managed keys for Azure Storage encryption](<https://learn.microsoft.com/azure/storage/common/customer-managed-keys-overview?WT.mc_id=AZ-MVP-5002880>)

[Case Study – Design Non-Relational Storage](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/03-Nonrelationalstorage.html>)

[Choose the right disk storage for your virtual machine workload - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/choose-the-right-disk-storage-for-vm-workload/?WT.mc_id=AZ-MVP-5002880>)

[Configure blob storage - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/configure-blob-storage/?WT.mc_id=AZ-MVP-5002880>)

[Optimize performance and costs by using Azure Disk Storage - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/optimize-performance-and-costs-using-azure-disk-storage/?WT.mc_id=AZ-MVP-5002880>)

[Caching and performance in Azure storage disks - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/caching-and-performance-azure-storage-and-disks/?WT.mc_id=AZ-MVP-5002880>)

[Introduction to securing data at rest on Azure - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/secure-data-at-rest/?WT.mc_id=AZ-MVP-5002880>)

[Create a storage account using the Azure portal - Learn | Microsoft Docs](<https://learn.microsoft.com/learn/modules/create-azure-storage-account?WT.mc_id=AZ-MVP-5002880>)

[Hybrid file services](<https://learn.microsoft.com/azure/architecture/hybrid/hybrid-file-services?WT.mc_id=AZ-MVP-5002880>)

[Archive your on-premises data to Azure Blob storage](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/backup-archive-on-premises?WT.mc_id=AZ-MVP-5002880>)

## Module 4: RDBS

[Design a data storage solution for relational data](<https://learn.microsoft.com/training/modules/design-data-storage-solution-for-relational-data/?WT.mc_id=AZ-MVP-5002880>)


[Introduction to Azure storage](<https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction?WT.mc_id=AZ-MVP-5002880>)

[Features comparison: Azure SQL Database and Azure SQL Managed Instance](<https://learn.microsoft.com/azure/azure-sql/azure-sql-iaas-vs-paas-what-is-overview?WT.mc_id=AZ-MVP-5002880#comparison-table>)

[What is Azure SQL](<https://learn.microsoft.com/azure/azure-sql/azure-sql-iaas-vs-paas-what-is-overview?WT.mc_id=AZ-MVP-5002880?toc=/azure/cloud-adoption-framework/toc.json&bc=/azure/cloud-adoption-framework/_bread/toc.json>)

[Database scaling strategy](<https://learn.microsoft.com/azure/azure-sql/database/scale-resources?WT.mc_id=AZ-MVP-5002880>)

[Elastic pools help you manage and scale multiple databases in Azure SQL Database](<https://learn.microsoft.com/azure/azure-sql/database/elastic-pool-overview?view=azuresql?WT.mc_id=AZ-MVP-5002880#when-should-you-consider-a-sql-database-elastic-pool>)

[Scalable performance and pools](<https://learn.microsoft.com/azure/azure-sql/database/sql-database-paas-overview?WT.mc_id=AZ-MVP-5002880?view=azuresql#scalable-performance-and-pools>)

[Compare vCore and DTU-based purchasing models of Azure SQL Database](<https://learn.microsoft.com/azure/azure-sql/database/purchasing-models?WT.mc_id=AZ-MVP-5002880>)

[DTU-based purchasing model overview](<https://learn.microsoft.com/en-us/azure/azure-sql/database/service-tiers-dtu?WT.mc_id=AZ-MVP-5002880>)

[vCore purchasing model - Azure SQL Database](<https://learn.microsoft.com/en-us/azure/azure-sql/database/service-tiers-sql-database-vcore?WT.mc_id=AZ-MVP-5002880>)

[Serverless compute tier for Azure SQL Database](<https://learn.microsoft.com/en-us/azure/azure-sql/database/serverless-tier-overview?WT.mc_id=AZ-MVP-5002880>)

[vCore purchasing model - Azure SQL Database](<https://learn.microsoft.com/azure/azure-sql/database/service-tiers-sql-database-vcore?WT.mc_id=AZ-MVP-5002880?view=azuresql>)

[Availability through redundancy - Azure SQL Database](<https://learn.microsoft.com/azure/azure-sql/database/high-availability-sla-local-zone-redundancy?view=azuresql&tabs=azure-powershell#basic-standard-and-general-purpose-service-tier-locally-redundant-availability>)

[Premium and Business Critical service tier locally redundant availability](<https://learn.microsoft.com/en-us/azure/azure-sql/database/high-availability-sla-local-zone-redundancy?WT.mc_id=AZ-MVP-5002880?view=azuresql&tabs=azure-powershell#premium-and-business-critical-service-tier-locally-redundant-availability>)

[High availability with the Business Critical/Premium tier](<https://learn.microsoft.com/azure/azure-sql/database/service-tier-hyperscale?WT.mc_id=AZ-MVP-5002880>)

[High availability with the Business Critical/Premium tier](<https://learn.microsoft.com/azure/azure-sql/database/service-tier-hyperscale-frequently-asked-questions-faq?WT.mc_id=AZ-MVP-5002880#how-can-i-choose-between-azure-synapse-analytics-and-azure-sql-database-hyperscale->)

[This doc covers the comparison of SQL DB and SQL MI HA](<https://learn.microsoft.com/azure/azure-sql/database/high-availability-sla?WT.mc_id=AZ-MVP-5002880>)

[Failover groups overview & best practices (Azure SQL Database)](<https://learn.microsoft.com/azure/azure-sql/database/failover-group-sql-db?WT.mc_id=AZ-MVP-5002880>)

[Active geo-replication](<https://learn.microsoft.com/azure/azure-sql/database/active-geo-replication-overview?WT.mc_id=AZ-MVP-5002880>)

[Select a database failover strategy](<https://learn.microsoft.com/azure/azure-sql/database/disaster-recovery-guidance?WT.mc_id=AZ-MVP-5002880>)

[Azure encryption overview](<https://learn.microsoft.com/azure/security/fundamentals/encryption-overview?WT.mc_id=AZ-MVP-5002880>)

[TLS/TDE](<https://learn.microsoft.com/azure/azure-sql/database/security-overview#transport-layer-security-encryption-in-transit?WT.mc_id=AZ-MVP-5002880>)

[Protect your database](<https://learn.microsoft.com/azure/azure-sql/database/transparent-data-encryption-tde-overview?WT.mc_id=AZ-MVP-5002880>)

[Always encrypted overview](<https://learn.microsoft.com/azure/azure-sql/database/always-encrypted-landing?WT.mc_id=AZ-MVP-5002880>)

[Dynamic data masking](<https://learn.microsoft.com/azure/azure-sql/database/dynamic-data-masking-overview?WT.mc_id=AZ-MVP-5002880>)

[Authenticate to an Azure SQL database](<https://learn.microsoft.com/azure/azure-sql/database/authentication-aad-overview?WT.mc_id=AZ-MVP-5002880?view=azuresql>)

[Authenticate to an Azure SQL database](<https://docs.microsoft.com/azure/sql-database/sql-database-manage-logins?WT.mc_id=AZ-MVP-5002880>)

[Azure Cosmos DB - Database for the AI Era](<https://learn.microsoft.com/azure/cosmos-db/introduction?WT.mc_id=AZ-MVP-5002880>)

[Database Architecture design](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/multi-region-web-app-cosmos-db-replication?WT.mc_id=AZ-MVP-5002880#architecture>)

[What is Azure Cosmos DB for Table?](<https://learn.microsoft.com/en-us/azure/cosmos-db/table/introduction?WT.mc_id=AZ-MVP-5002880>)

[Considerations when choosing an API](<https://learn.microsoft.com/azure/cosmos-db/choose-api#considerations-when-choosing-an-api?WT.mc_id=AZ-MVP-5002880>)

[Review your data options](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/considerations/data-options?WT.mc_id=AZ-MVP-5002880>)

[Design Relational Storage Case Study](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/04-Relationalstorage.html>)

[Work with CosmosDB](<https://learn.microsoft.com/en-us/training/modules/work-with-cosmos-db/?WT.mc_id=AZ-MVP-5002880>)

[Secure your Azure SQL database](<https://learn.microsoft.com/learn/modules/secure-your-azure-sql-database/?WT.mc_id=AZ-MVP-5002880>)

[Scale multiple Azure SQL Databases with SQL elastic pools](<https://learn.microsoft.com//learn/modules/scale-sql-databases-elastic-pools/?WT.mc_id=AZ-MVP-5002880>)

[Configure database authentication and authorization](<https://learn.microsoft.com/learn/modules/configure-database-authentication-authorization/?WT.mc_id=AZ-MVP-5002880>)

[Database architecture design](<https://learn.microsoft.com/azure/architecture/databases/?WT.mc_id=AZ-MVP-5002880>)

[Architecture diagram as explained in the reference page.](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/multi-region-web-app-multi-writes-azure-table?WT.mc_id=AZ-MVP-5002880>)

## Module 5: Data integration

[Design a data integration solution](<https://learn.microsoft.com/training/modules/design-data-integration/?WT.mc_id=AZ-MVP-5002880>)

[Data Integration – whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/architecture/example-scenario/dataplate2e/data-platform-end-to-end?WT.mc_id=AZ-MVP-5002880?tabs=portal>)

[Azure Data Lake is built on top of Azure Blob Storage. What does it add?](<https://learn.microsoft.com/azure/storage/blobs/data-lake-storage-introduction#key-features-of-data-lake-storage-gen2?WT.mc_id=AZ-MVP-5002880>)

[Azure Data Lake - whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/storage/blobs/data-lake-storage-namespace?WT.mc_id=AZ-MVP-5002880>)

[Azure Data Lake - whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/architecture/data-guide/scenarios/data-lake?WT.mc_id=AZ-MVP-5002880>)

[Why would I choose for Blob Storage, instead of Data Lake?](<https://learn.microsoft.com/azure/storage/blobs/storage-feature-support-in-storage-accounts?WT.mc_id=AZ-MVP-5002880>)

[Why would I choose for Blob Storage, instead of Data Lake?](<https://learn.microsoft.com/azure/architecture/guide/technology-choices/data-store-decision-tree?WT.mc_id=AZ-MVP-5002880>)

[Why is it important to support RBAC down to the individual file level?](<https://learn.microsoft.com/azure/storage/blobs/data-lake-storage-access-control-model#access-control-lists-acls>)

[I need to organize my Data Lake. What are some common approaches?](<https://learn.microsoft.com/azure/storage/blobs/data-lake-storage-best-practices#directory-structure?WT.mc_id=AZ-MVP-5002880>)

[I need to organize my Data Lake. What are some common approaches?](<https://learn.microsoft.com/azure/databricks/delta/delta-intro?WT.mc_id=AZ-MVP-5002880>)

[I need to organize my Data Lake. What are some common approaches?](<https://learn.microsoft.com/training/modules/describe-azure-databricks-delta-lake-architecture/2-describe-bronze-silver-gold-architecture?WT.mc_id=AZ-MVP-5002880>)

[Azure Data Lake](<https://learn.microsoft.com/azure/storage/blobs/data-lake-storage-introduction?WT.mc_id=AZ-MVP-5002880>)

[Choose a big data storage technology in Azure](<https://learn.microsoft.com/azure/architecture/data-guide/technology-choices/data-storage?WT.mc_id=AZ-MVP-5002880>)

[Why would you consider Azure Data Factory over SSIS (SQL Server Integration Services)?](<https://learn.microsoft.com/azure/architecture/data-guide/technology-choices/pipeline-orchestration-data-movement?WT.mc_id=AZ-MVP-5002880>)

[Why would you consider Azure Data Factory over SSIS (SQL Server Integration Services)?](<https://learn.microsoft.com/azure/architecture/reference-architectures/data/enterprise-bi-adf?WT.mc_id=AZ-MVP-5002880>)

[Why would you consider Azure Data Factory over SSIS (SQL Server Integration Services)?](<https://learn.microsoft.com/azure/architecture/example-scenario/data/hybrid-etl-with-adf?WT.mc_id=AZ-MVP-5002880>)

[What do you pay for when using Azure Data Factory?](<https://learn.microsoft.com/azure/data-factory/plan-manage-costs?WT.mc_id=AZ-MVP-5002880>)

[What do you pay for when using Azure Data Factory?](<https://learn.microsoft.com/azure/data-factory/pricing-concepts?WT.mc_id=AZ-MVP-5002880>)

[Azure Data Factory - whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/data-factory/transform-data?WT.mc_id=AZ-MVP-5002880>)

[What is a Self-Hosted Integration Runtime and why do you need it?](<https://learn.microsoft.com/azure/data-factory/concepts-integration-runtime?WT.mc_id=AZ-MVP-5002880#self-hosted-integration-runtime>)

[What is a Self-Hosted Integration Runtime and why do you need it?](<https://learn.microsoft.com/azure/data-factory/create-self-hosted-integration-runtime?WT.mc_id=AZ-MVP-5002880?tabs=data-factory>)

[What is Azure Databricks?](<https://learn.microsoft.com/azure/databricks/introduction/?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Synapse Analytics?](<https://learn.microsoft.com/azure/synapse-analytics/overview-what-is?WT.mc_id=AZ-MVP-5002880>)

[Data integration in Azure Synapse Analytics versus Azure Data Factory](<https://learn.microsoft.com/azure/synapse-analytics/data-integration/concepts-data-factory-differences?WT.mc_id=AZ-MVP-5002880#available-features-in-adf--azure-synapse-analytics>)

[Azure Fabric documentation](<https://learn.microsoft.com/fabric/?WT.mc_id=AZ-MVP-5002880>)

[Welcome to Azure Stream Analytics](<https://learn.microsoft.com/azure/stream-analytics/stream-analytics-introduction?WT.mc_id=AZ-MVP-5002880>)

[4 common analytics scenarios to build business agility](<https://azure.microsoft.com/blog/4-common-analytics-scenarios-to-build-business-agility/?WT.mc_id=AZ-MVP-5002880>)

## Module 6: App architecture

[Design an application architecture solution](<https://learn.microsoft.com/training/modules/design-application-architecture/?WT.mc_id=AZ-MVP-5002880>)

[How will you decide between using events or messages?](<https://learn.microsoft.com/azure/event-grid/compare-messaging-services#event-vs-message-services?WT.mc_id=AZ-MVP-5002880>)

[Events](<https://learn.microsoft.com/azure/event-grid/compare-messaging-services?WT.mc_id=AZ-MVP-5002880#event>)

[Messages](<https://learn.microsoft.com/azure/event-grid/compare-messaging-services?WT.mc_id=AZ-MVP-5002880#message>)

[Azure Queue storage](<https://learn.microsoft.com/azure/storage/queues/storage-queues-introduction?WT.mc_id=AZ-MVP-5002880>)

[Messaging solutions –whiteboard and discussion (notes)](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-azure-and-service-bus-queues-compared-contrasted?WT.mc_id=AZ-MVP-5002880>)

[In what scenarios would you use an Azure Service Bus Topic?](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-queues-topics-subscriptions#topics-and-subscriptions?WT.mc_id=AZ-MVP-5002880>)

[If the message payload is larger than 64 KB in size, what options do you have?](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-azure-and-service-bus-queues-compared-contrasted#capacity-and-quotas?WT.mc_id=AZ-MVP-5002880>)

[If the message payload is larger than 64 KB in size, what options do you have?](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-premium-messaging#large-messages-support?WT.mc_id=AZ-MVP-5002880>)

[Azure Service Bus queues](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-queues-topics-subscriptions?WT.mc_id=AZ-MVP-5002880>)

[Storage queues and Service Bus queues - compared and contrasted](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-azure-and-service-bus-queues-compared-contrasted#foundational-capabilities?WT.mc_id=AZ-MVP-5002880>)

[Overview of transaction processing in Azure Service Bus](<https://learn.microsoft.com/azure/service-bus-messaging/service-bus-transactions?WT.mc_id=AZ-MVP-5002880>)

[Azure Event Hubs — A big data streaming platform and event ingestion service](<https://learn.microsoft.com/azure/event-hubs/event-hubs-about?WT.mc_id=AZ-MVP-5002880>)

[Use event hub from Apache Kafka app](<https://learn.microsoft.com/azure/event-hubs/event-hubs-for-kafka-ecosystem-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Event Grid](<https://learn.microsoft.com/azure/event-grid/overview?WT.mc_id=AZ-MVP-5002880>)

[When to use IoT hub](<https://learn.microsoft.com/learn/modules/introduction-to-iot-hub/4-when-to-use-iot-hub?WT.mc_id=AZ-MVP-5002880>)

[IoT Concepts and Azure IoT Hub](<https://learn.microsoft.com/azure/iot-hub/iot-concepts-and-iot-hub?WT.mc_id=AZ-MVP-5002880>)

[Connecting IoT Devices to Azure: IoT Hub and Event Hubs](<https://learn.microsoft.com/azure/iot-hub/iot-hub-compare-event-hubs?WT.mc_id=AZ-MVP-5002880>)

[Caching guidance](<https://learn.microsoft.com/azure/architecture/best-practices/caching?WT.mc_id=AZ-MVP-5002880?toc=%2Fazure%2Fredis-cache%2Ftoc.json>)

[Azure Cache for Redis Retirement](<https://techcommunity.microsoft.com/blog/azure-managed-redis/azure-cache-for-redis-retirement-what-to-know-and-how-to-prepare/4458721?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Managed Redis?](<https://learn.microsoft.com/azure/redis/overview?WT.mc_id=AZ-MVP-5002880>)

[Choosing the right tier](<https://learn.microsoft.com/azure/redis/overview?WT.mc_id=AZ-MVP-5002880#choosing-the-right-tier>)

[Migrate from Basic, Standard, Premium, and Enterprise tiers to Azure Managed Redis](<https://learn.microsoft.com/azure/redis/migrate/migrate-overview?WT.mc_id=AZ-MVP-5002880?source=recommendations>)

[Azure API Management](<https://learn.microsoft.com/azure/api-management/api-management-key-concepts?WT.mc_id=AZ-MVP-5002880>)

[What is Infrastructure as Code?](<https://learn.microsoft.com/devops/deliver/what-is-infrastructure-as-code?WT.mc_id=AZ-MVP-5002880>)

[Azure Resource Manager (ARM) templates](<https://learn.microsoft.com/azure/azure-resource-manager/templates/overview?WT.mc_id=AZ-MVP-5002880>)

[Bicep](<https://learn.microsoft.com/azure/azure-resource-manager/bicep/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Update Manager](<https://learn.microsoft.com/ss/azure/update-manager/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure DevOps documentation](<https://learn.microsoft.com/azure/devops?WT.mc_id=AZ-MVP-5002880>)

[GitHub Actions](<https://learn.github.com/actions?WT.mc_id=AZ-MVP-5002880>)

[Terraform by Hashicorp](<https://www.terraform.io/?WT.mc_id=AZ-MVP-5002880>)

[Jenkins](<https://www.jenkins.io/?WT.mc_id=AZ-MVP-5002880>)

[Python with Pulumi](<https://devblogs.microsoft.com/devops/infrastructure-as-code-azure-python-wpulumi/?WT.mc_id=AZ-MVP-5002880>)

[Chef Automate](<https://docs.chef.io/automate/?WT.mc_id=AZ-MVP-5002880>)

[Ansible](<https://learn.microsoft.com/azure/developer/ansible/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Chaos Studio](<https://azure.microsoft.com/services/chaos-studio/?WT.mc_id=AZ-MVP-5002880>)

[Azure App Configuration](<https://learn.microsoft.com/azure/azure-app-configuration/overview?WT.mc_id=AZ-MVP-5002880>)

[Case Study – Application architecture](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/06-Apparchitecture.html?WT.mc_id=AZ-MVP-5002880>)

[Serverless Functions reference architectures](<https://learn.microsoft.com/azure/architecture/serverless-quest/reference-architectures?WT.mc_id=AZ-MVP-5002880>)

[Serverless event-driven architecture](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/serverless-event-processing-filtering?WT.mc_id=AZ-MVP-5002880>)

[IoT Connected Platform](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/iot-connected-platform?WT.mc_id=AZ-MVP-5002880>)

[Application integration using Azure Event Grid](<https://learn.microsoft.com/azure/architecture/solution-ideas/articles/application-integration-using-event-grid?WT.mc_id=AZ-MVP-5002880>)

## Module 7: Identity

[Design Authentication and Authorization Solutions](<https://learn.microsoft.com/training/modules/design-authentication-authorization-solutions/?WT.mc_id=AZ-MVP-5002880>)

[Zero Trust Model](<https://www.microsoft.com/security/business/zero-trust?WT.mc_id=AZ-MVP-5002880>)

[Azure identity management security overview](<https://learn.microsoft.com/azure/security/fundamentals/identity-management-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Microsoft Entra ID?-](<https://learn.microsoft.com/entra/fundamentals/whatis?WT.mc_id=AZ-MVP-5002880>)

[Why would you consider Microsoft Entra B2B?](<https://learn.microsoft.com/entra/external-id/external-identities-overview?WT.mc_id=AZ-MVP-5002880>)

[Can you enforce MFA for guest accounts, even when they do not have this configured?](<https://learn.microsoft.com/entra/external-id/b2b-tutorial-require-mfa?WT.mc_id=AZ-MVP-5002880>)

[Will you use a centralized or de-centralized approach? For example, inviting guests.](<https://learn.microsoft.com/entra/external-id/add-users-information-worker?WT.mc_id=AZ-MVP-5002880>)

[Will you use a centralized or de-centralized approach? For example, inviting guests.](<https://learn.microsoft.com/entra/external-id/invite-internal-users?WT.mc_id=AZ-MVP-5002880>)

[How will you decide to use self-service sign-up flow?](<https://learn.microsoft.com/entra/external-id/self-service-sign-up-user-flow?WT.mc_id=AZ-MVP-5002880>)

[Microsoft Entra B2B best practices](<https://learn.microsoft.com/entra/external-id/b2b-fundamentals?WT.mc_id=AZ-MVP-5002880>)

[Azure AD B2C end of sale](<https://learn.microsoft.com/en-us/azure/active-directory-b2c/faq?tabs=app-reg-ga#azure-ad-b2c-end-of-sale?WT.mc_id=AZ-MVP-5002880>)

[Conditional Access](<https://learn.microsoft.com/entra/identity/conditional-access/overview?WT.mc_id=AZ-MVP-5002880>)

[What is Entra ID protection?](<https://learn.microsoft.com/entra/id-protection/overview-identity-protection?WT.mc_id=AZ-MVP-5002880>)

[What are access reviews?](<https://learn.microsoft.com/entra/id-governance/access-reviews-overview?WT.mc_id=AZ-MVP-5002880>)

[Managed identities](<https://learn.microsoft.com/entra/identity/managed-identities-azure-resources/overview?WT.mc_id=AZ-MVP-5002880>)

[Infrastructure protection](<https://learn.microsoft.com/training/modules/azure-well-architected-security/?WT.mc_id=AZ-MVP-5002880>)

[Application and service principal objects in Azure Active Directory](<https://learn.microsoft.com/entra/identity-platform/app-objects-and-service-principals?WT.mc_id=AZ-MVP-5002880>)

[Azure Key Vault basic concepts](<https://learn.microsoft.com/azure/key-vault/general/basic-concepts?WT.mc_id=AZ-MVP-5002880>)

[Case Study – Authentication and authorization](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/07-Access.html?WT.mc_id=AZ-MVP-5002880>)

[Understand Microsoft Entra ID](<https://learn.microsoft.com/training/modules/understand-azure-active-directory/?WT.mc_id=AZ-MVP-5002880>)

[Plan, implement, and administer conditional access](<https://learn.microsoft.com/training/modules/plan-implement-administer-conditional-access/?WT.mc_id=AZ-MVP-5002880>)

[Design, develop, and manage access reviews](<https://learn.microsoft.com/training/modules/plan-implement-manage-access-review/?WT.mc_id=AZ-MVP-5002880>)

[Configure and manage secrets in Azure key vault](<https://learn.microsoft.com/learn/modules/configure-and-manage-azure-key-vault/?WT.mc_id=AZ-MVP-5002880>)

[Manage secrets in your server apps with Azure key vault](<https://learn.microsoft.com/learn/modules/manage-secrets-with-azure-key-vault/?WT.mc_id=AZ-MVP-5002880>)

## Module 8: Monitor/Log

[Design a solution to log and monitor Azure resources](<https://learn.microsoft.com/training/modules/design-solution-to-log-monitor-azure-resources/?WT.mc_id=AZ-MVP-5002880>)

[Azure Monitor features](<https://learn.microsoft.com/azure/azure-monitor/overview?WT.mc_id=AZ-MVP-5002880>)

[Best practices for monitoring cloud applications](<https://learn.microsoft.com/azure/architecture/best-practices/monitoring?WT.mc_id=AZ-MVP-5002880>)

[Sources of monitoring data for Azure Monitor and their data collection methods](<https://learn.microsoft.com/azure/azure-monitor/data-sources?WT.mc_id=AZ-MVP-5002880>)

[Overview of Log Analytics in Azure Monitor](<https://learn.microsoft.com/azure/azure-monitor/logs/log-analytics-overview?WT.mc_id=AZ-MVP-5002880>)

[Designing your Azure Monitor Logs deployment](<https://learn.microsoft.com/azure/azure-monitor/platform/design-logs-deployment?WT.mc_id=AZ-MVP-5002880>)

[Overview of Azure Monitor agents](<https://learn.microsoft.com/azure/azure-monitor/platform/agents-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Workbooks](<https://learn.microsoft.com/azure/azure-monitor/visualize/workbooks-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Application Insights?](<https://learn.microsoft.com/azure/azure-monitor/app/app-insights-overview?WT.mc_id=AZ-MVP-5002880>)

[Data Explorer](<https://azure.microsoft.com/services/data-explorer/?WT.mc_id=AZ-MVP-5002880>)

[Design a full-stack monitoring strategy on Azure](<https://learn.microsoft.com/training/modules/design-monitoring-strategy-on-azure/?WT.mc_id=AZ-MVP-5002880>)

[Analyze your Azure infrastructure by using Azure Monitor logs](<https://learn.microsoft.com/learn/modules/analyze-infrastructure-with-azure-monitor-logs/?WT.mc_id=AZ-MVP-5002880>)

[Monitor your Azure virtual machines with Azure Monitor](<https://learn.microsoft.com/training/modules/monitor-azure-vm-using-diagnostic-data/?WT.mc_id=AZ-MVP-5002880>)

[Monitor app performance](<https://learn.microsoft.com/training/modules/monitor-app-performance/?WT.mc_id=AZ-MVP-5002880>)

## Module 9: Network

[Design a network infrastructure solution](<https://learn.microsoft.com/training/modules/design-network-solutions/?WT.mc_id=AZ-MVP-5002880>)

[What are design considerations for Azure virtual networks?](<https://learn.microsoft.com/azure/virtual-network/virtual-network-vnet-plan-design-arm?WT.mc_id=AZ-MVP-5002880>)

[Defense in Depth (video)](<https://learn.microsoft.com/shows/azure-videos/defense-in-depth-security-in-azure?WT.mc_id=AZ-MVP-5002880>)

[Traditional Azure networking topology](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/traditional-azure-networking-topology?WT.mc_id=AZ-MVP-5002880>)

[VPN Gateway topology and design](<https://learn.microsoft.com/azure/vpn-gateway/design?WT.mc_id=AZ-MVP-5002880>)

[What is ExpressRoute](<https://learn.microsoft.com/azure/expressroute/expressroute-introduction?WT.mc_id=AZ-MVP-5002880>)

[Virtual WAN network topology](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/virtual-wan-network-topology?WT.mc_id=AZ-MVP-5002880>)

[Decision tree for load balancing in Azure](<https://learn.microsoft.com/azure/architecture/guide/technology-choices/load-balancing-overview?WT.mc_id=AZ-MVP-5002880#decision-tree-for-load-balancing-in-azure>)

[Point out that the Portal has information that will help you choose a solution](<https://portal.azure.com/?feature.customportal=false#blade/Microsoft_Azure_Network/LoadBalancingHubMenuBlade/overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Load Balancer?](<https://learn.microsoft.com/azure/load-balancer/load-balancer-overview?WT.mc_id=AZ-MVP-5002880>)

[Load balancing options](<https://learn.microsoft.com/azure/architecture/guide/technology-choices/load-balancing-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Application Gateway?](<https://learn.microsoft.com/azure/application-gateway/overview?WT.mc_id=AZ-MVP-5002880>)

[Well-Architected Framework perspective on Azure Application Gateway v2](<https://learn.microsoft.com/azure/well-architected/service-guides/azure-application-gateway?WT.mc_id=AZ-MVP-5002880>)

[What is Traffic Manager?](<https://learn.microsoft.com/azure/traffic-manager/traffic-manager-overview?WT.mc_id=AZ-MVP-5002880>)

[Multi-region load balancing with Traffic Manager, Azure Firewall, and Application Gateway](<https://learn.microsoft.com/azure/architecture/high-availability/reference-architecture-traffic-manager-application-gateway?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Front Door?](<https://learn.microsoft.com/azure/frontdoor/front-door-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Well-Architected Framework perspective on Azure Front Door](<https://learn.microsoft.com/azure/well-architected/service-guides/azure-front-door?WT.mc_id=AZ-MVP-5002880>)

[What is a content delivery network on Azure?](<https://learn.microsoft.com/azure/cdn/cdn-overview?WT.mc_id=AZ-MVP-5002880>)

[Comparison between Azure Front Door and Azure CDN services](<https://learn.microsoft.com/azure/frontdoor/front-door-cdn-comparison?WT.mc_id=AZ-MVP-5002880>)

[Virtual Network service endpoints](<https://learn.microsoft.com/azure/virtual-network/virtual-network-service-endpoints-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Private Link?](<https://learn.microsoft.com/azure/private-link/private-link-overview?WT.mc_id=AZ-MVP-5002880>)

[Recommendations for networking and connectivity](<https://learn.microsoft.com/azure/well-architected/security/networking?WT.mc_id=AZ-MVP-5002880>)

[Network Security Groups](<https://learn.microsoft.com/azure/virtual-network/network-security-groups-overview?WT.mc_id=AZ-MVP-5002880>)

[Azure best practices for network security](<https://learn.microsoft.com/azure/security/fundamentals/network-best-practices?WT.mc_id=AZ-MVP-5002880>)

[Azure Firewall (Learn)](<https://learn.microsoft.com/learn/modules/introduction-azure-firewall/?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Firewall?](<https://learn.microsoft.com/azure/firewall/overview?WT.mc_id=AZ-MVP-5002880>)

[Azure Well-Architected Framework perspective on Azure Firewall](<https://learn.microsoft.com/azure/well-architected/service-guides/azure-firewall?WT.mc_id=AZ-MVP-5002880>)

[Web Application Firewall](<https://learn.microsoft.com/azure/web-application-firewall/overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure DDoS protection?](<https://learn.microsoft.com/azure/ddos-protection/ddos-protection-overview?WT.mc_id=AZ-MVP-5002880>)

[DDoS Protection](<https://learn.microsoft.com/azure/ddos-protection/ddos-protection-reference-architectures?WT.mc_id=AZ-MVP-5002880>)

[About Azure DDoS Protection Tier Comparison](<https://learn.microsoft.com/azure/ddos-protection/ddos-protection-sku-comparison?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Bastion?](<https://learn.microsoft.com/azure/bastion/bastion-overview?WT.mc_id=AZ-MVP-5002880>)

[Just-in-time machine access](<https://learn.microsoft.com/azure/defender-for-cloud/just-in-time-access-overview?tabs=defender-for-container-arch-aks?WT.mc_id=AZ-MVP-5002880>)

[Case Study – BI enterprise application](<https://microsoftlearning.github.io/AZ-305-DesigningMicrosoftAzureInfrastructureSolutions/Instructions/CaseStudy/09-Networking?WT.mc_id=AZ-MVP-5002880>)

[AZ-700 Designing and implementing networking solutions (learning path)](<https://learn.microsoft.com/training/paths/design-implement-microsoft-azure-networking-solutions-az-700/?WT.mc_id=AZ-MVP-5002880>)

[Architecture network infrastructure (learning path)](<https://learn.microsoft.com/training/paths/architect-network-infrastructure/?WT.mc_id=AZ-MVP-5002880>)

[Distribute your services across Azure virtual networks](<https://learn.microsoft.com/training/modules/integrate-vnets-with-vnet-peering/?WT.mc_id=AZ-MVP-5002880>)

[Secure and isolate access using network security groups](<https://learn.microsoft.com/training/modules/secure-and-isolate-with-nsg-and-service-endpoints/?WT.mc_id=AZ-MVP-5002880>)

## Module 10: BCDR

[Design a business continuity solution](<https://learn.microsoft.com/training/modules/design-solution-for-backup-disaster-recovery/?WT.mc_id=AZ-MVP-5002880>)

[Recommendations for designing a disaster recovery strategy](<https://learn.microsoft.com/azure/well-architected/reliability/disaster-recovery?WT.mc_id=AZ-MVP-5002880>)

[Enterprise-scale business continuity and disaster recovery](<https://learn.microsoft.com/azure/cloud-adoption-framework/ready/enterprise-scale/business-continuity-and-disaster-recovery?WT.mc_id=AZ-MVP-5002880>)

[Azure Backup Service documentation](<https://learn.microsoft.com/azure/backup/?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Backup?](<https://learn.microsoft.com/azure/backup/backup-overview?WT.mc_id=AZ-MVP-5002880>)

[In what scenarios can you use Azure Backup?](<https://learn.microsoft.com/azure/backup/backup-support-matrix?WT.mc_id=AZ-MVP-5002880>)

[What will you consider when determining what to backup and how long to retain backups?](<https://learn.microsoft.com/azure/backup/backup-azure-vm-backup-faq?WT.mc_id=AZ-MVP-5002880>)

[What will you consider when determining what to backup and how long to retain backups?](<https://learn.microsoft.com/azure/backup/archive-tier-support?WT.mc_id=AZ-MVP-5002880>)

[Recovery Services vaults overview](<https://learn.microsoft.com/azure/backup/backup-azure-recovery-services-vault-overview?WT.mc_id=AZ-MVP-5002880>)

[Vault considerations](<https://learn.microsoft.com/azure/backup/guidance-best-practices#vault-considerations?WT.mc_id=AZ-MVP-5002880>)

[Backup policy considerations](<https://learn.microsoft.com/azure/backup/guidance-best-practices#backup-policy-considerations?WT.mc_id=AZ-MVP-5002880>)

[What are the Azure Blob storage features you can use to recover data without Azure Backup?](<https://learn.microsoft.com/azure/storage/blobs/data-protection-overview?WT.mc_id=AZ-MVP-5002880>)

[Container soft delete](<https://learn.microsoft.com/azure/storage/blobs/soft-delete-container-enable?WT.mc_id=AZ-MVP-5002880>)

[Blob soft delete](<https://learn.microsoft.com/azure/storage/blobs/soft-delete-blob-enable?WT.mc_id=AZ-MVP-5002880>)

[Blob versioning](<https://learn.microsoft.com/azure/storage/blobs/versioning-enable?WT.mc_id=AZ-MVP-5002880>)

[What are your options for a Point-in-time restore on Azure Blob storage?](<https://learn.microsoft.com/azure/storage/blobs/point-in-time-restore-overview?WT.mc_id=AZ-MVP-5002880>)

[Overview of share snapshots for Azure Files](<https://learn.microsoft.com/azure/storage/files/storage-snapshots-files?WT.mc_id=AZ-MVP-5002880>)

[Azure virtual machines backups](<https://learn.microsoft.com/azure/backup/backup-azure-vms-introduction?WT.mc_id=AZ-MVP-5002880>)

[Monitoring and Alerting considerations](<https://learn.microsoft.com/azure/backup/guidance-best-practices#monitoring-and-alerting?WT.mc_id=AZ-MVP-5002880>)

[Backup cloud and on-premises workloads to cloud](<https://learn.microsoft.com/azure/backup/guidance-best-practices?WT.mc_id=AZ-MVP-5002880>)

[What will you consider when determining how to backup your Azure SQL database?](<https://learn.microsoft.com/azure/azure-sql/database/automated-backups-overview?WT.mc_id=AZ-MVP-5002880?tabs=single-database>)

[What will you consider when determining how to restore your Azure SQL database?](<https://learn.microsoft.com/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview?WT.mc_id=AZ-MVP-5002880>)

[Full backups](<https://learn.microsoft.com/sql/relational-databases/backup-restore/full-database-backups-sql-server?WT.mc_id=AZ-MVP-5002880>)

[Differential backups](<https://learn.microsoft.com/sql/relational-databases/backup-restore/differential-backups-sql-server?WT.mc_id=AZ-MVP-5002880>)

[Transaction log backups](<https://learn.microsoft.com/sql/relational-databases/backup-restore/transaction-log-backups-sql-server?WT.mc_id=AZ-MVP-5002880>)

[Recover using backups](<https://learn.microsoft.com/azure/azure-sql/database/recovery-using-backups?WT.mc_id=AZ-MVP-5002880>)

[Why would you choose Azure Site Recovery over another (3rd-party) solution?](<https://learn.microsoft.com/azure/site-recovery/site-recovery-overview?WT.mc_id=AZ-MVP-5002880>)

[Why would you combine Azure Site Recovery with Azure Backup?](<https://learn.microsoft.com/azure/site-recovery/site-recovery-backup-interoperability?WT.mc_id=AZ-MVP-5002880>)

[Azure to Azure disaster recovery architecture](<https://learn.microsoft.com/azure/site-recovery/azure-to-azure-architecture?WT.mc_id=AZ-MVP-5002880>)

[Protect your virtual machines by using Azure Backup](<https://learn.microsoft.com/training/modules/protect-virtual-machines-with-azure-backup/?WT.mc_id=AZ-MVP-5002880>)

[Disaster recovery and backup](<https://learn.microsoft.com/learn/modules/cmu-disaster-recovery-backup/?WT.mc_id=AZ-MVP-5002880>)

[Back up and restore your Azure SQL database](<https://learn.microsoft.com/learn/modules/backup-restore-azure-sql/?WT.mc_id=AZ-MVP-5002880>)

[Protect your Azure infrastructure with Azure Site Recovery](<https://learn.microsoft.com/learn/modules/protect-infrastructure-with-site-recovery/?WT.mc_id=AZ-MVP-5002880>)

[Design your site recovery solution in Azure](<https://learn.microsoft.com/learn/modules/design-your-site-recovery-solution-in-azure/?WT.mc_id=AZ-MVP-5002880>)

## Module 11: Migrate

[Design a migration solution](<https://learn.microsoft.com/training/modules/design-migrations/?WT.mc_id=AZ-MVP-5002880>)

[Azure Migrate documentation](<https://learn.microsoft.com/azure/migrate/?WT.mc_id=AZ-MVP-5002880>)

[Cloud adoption scenarios](<https://learn.microsoft.com/azure/cloud-adoption-framework/scenarios?WT.mc_id=AZ-MVP-5002880>)

[Review product migration scenarios](<https://learn.microsoft.com/azure/cloud-adoption-framework/migrate/scenarios>)

[Migration deployment checklist](<https://learn.microsoft.com/azure/cloud-adoption-framework/migrate/azure-migration-guide/migrate?WT.mc_id=AZ-MVP-5002880?tabs=Tools>)

[Migration guide: SQL Server to Azure SQL Database](<https://learn.microsoft.com/data-migration/sql-server/database/guide?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Database Migration Service?](https://learn.microsoft.com/azure/dms/dms-overview>?WT.mc_id=AZ-MVP-5002880)

[Planning for an Azure File Sync deployment](<https://learn.microsoft.com/azure/storage/file-sync/file-sync-planning?WT.mc_id=AZ-MVP-5002880>)

[Migrate to SMB Azure File Shares](<https://learn.microsoft.com/azure/storage/files/storage-files-migration-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Storage Mover](<https://learn.microsoft.com/azure/storage-mover/service-overview?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Import/Export service?](<https://learn.microsoft.com/azure/import-export/storage-import-export-service?WT.mc_id=AZ-MVP-5002880>)

[Export large amounts of data from Azure by using Azure Import/Export (Learn)](<https://learn.microsoft.com/learn/modules/export-data-with-azure-import-export/?WT.mc_id=AZ-MVP-5002880>)

[Consider the Import/Export Service](<https://learn.microsoft.com/azure/storage/common/storage-use-azcopy-v10?WT.mc_id=AZ-MVP-5002880>)

[Azure Data Box (marketing)](<https://azure.microsoft.com/products/databox?WT.mc_id=AZ-MVP-5002880>)

[What is Azure Data Box?](<https://learn.microsoft.com/azure/databox/data-box-overview?WT.mc_id=AZ-MVP-5002880>)

[Migrate data offline to Azure File Sync with Azure Data Box](<https://learn.microsoft.com/azure/storage/files/storage-files-migration-server-hybrid-databox?WT.mc_id=AZ-MVP-5002880>)

[Move large amounts of data to the cloud by using Azure Data Box family (Learn)](<https://learn.microsoft.com/learn/modules/move-data-with-azure-data-box/?WT.mc_id=AZ-MVP-5002880>)