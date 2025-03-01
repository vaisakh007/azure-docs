---
title: Solution architectures using Azure NetApp Files | Microsoft Docs
description: Provides references to best practices for solution architectures using Azure NetApp Files.
services: azure-netapp-files
documentationcenter: ''
author: b-hchen
manager: ''
editor: ''

ms.assetid:
ms.service: azure-netapp-files
ms.workload: storage
ms.tgt_pltfrm: na
ms.topic: conceptual
ms.date: 01/28/2022
ms.author: anfdocs
---
# Solution architectures using Azure NetApp Files
This article provides references to best practices that can help you understand the solution architectures for using Azure NetApp Files.  

The following diagram summarizes the categories of solution architectures that Azure NetApp Files offers:

![Solution architecture categories](../media/azure-netapp-files/solution-architecture-categories.png)

## Linux OSS Apps and Database solutions

This section provides references for solutions for Linux OSS applications and databases. 

### Linux OSS Apps

* [AIX UNIX on-premises to Azure Linux migration - Azure Example Scenarios](/azure/architecture/example-scenario/unix-migration/migrate-aix-azure-linux)
* [Leverage Azure NetApp Files for R Studio workloads](https://techcommunity.microsoft.com/t5/azure-storage-blog/leverage-azure-netapp-files-for-r-studio-workloads/ba-p/2935878)

### Mainframe refactor

* [General mainframe refactor to Azure - Azure Example Scenarios](/azure/architecture/example-scenario/mainframe/general-mainframe-refactor)
* [Refactor mainframe applications with Advanced - Azure Example Scenarios](/azure/architecture/example-scenario/mainframe/refactor-mainframe-applications-advanced)

### Oracle

* [Oracle Database with Azure NetApp Files - Azure Example Scenarios](/azure/architecture/example-scenario/file-storage/oracle-azure-netapp-files)
* [Oracle Databases on Microsoft Azure Using Azure NetApp Files](https://www.netapp.com/media/17105-tr4780.pdf)
* [Oracle VM images and their deployment on Microsoft Azure: Shared storage configuration options](../virtual-machines/workloads/oracle/oracle-vm-solutions.md#shared-storage-configuration-options)
* [Oracle database performance on Azure NetApp Files single volumes](performance-oracle-single-volumes.md)
* [Benefits of using Azure NetApp Files with Oracle Database](solutions-benefits-azure-netapp-files-oracle-database.md)

### Machine Learning
*	[Cloudera Machine Learning](https://docs.cloudera.com/machine-learning/cloud/requirements-azure/topics/ml-requirements-azure.html)
*	[Distributed training in Azure: Lane detection - Solution design](https://www.netapp.com/media/32427-tr-4896-design.pdf)
*	[Distributed training in Azure: Click-Through Rate Prediction – Solution design](https://docs.netapp.com/us-en/netapp-solutions/ai/aks-anf_introduction.html)

### Education

* [Moodle deployment with Azure NetApp Files - Azure Example Scenarios](/azure/architecture/example-scenario/file-storage/moodle-azure-netapp-files)
* [Moodle on Azure NetApp Files NFS storage](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-netapp-files-for-nfs-storage-with-moodle/ba-p/2300630)

## Windows Apps and SQL Server solutions

This section provides references for Windows applications and SQL Server solutions.

### File sharing and Global File Caching

* [Enterprise file shares with disaster recovery - Azure Example Scenarios](/azure/architecture/example-scenario/file-storage/enterprise-file-shares-disaster-recovery)
* [Disaster Recovery for Enterprise File Shares with Azure NetApp Files and DFS Namespaces](https://techcommunity.microsoft.com/t5/azure-architecture-blog/disaster-recovery-for-enterprise-file-shares/ba-p/2808757)
* [Build Your Own Azure NFS? Wrestling Linux File Shares into Cloud](https://cloud.netapp.com/blog/ma-anf-blg-build-your-own-linux-nfs-file-shares)
* [Globally Distributed Enterprise File Sharing with Azure NetApp Files and NetApp Global File Cache](https://f.hubspotusercontent20.net/hubfs/525875/NA-580-0521-Architecture-Doc-R3.pdf)
* [Cloud Compliance for Azure NetApp Files](https://cloud.netapp.com/hubfs/Cloud%20Compliance%20for%20Azure%20NetApp%20Files%20-%20November%202020.pdf)

### SQL Server

* [SQL Server on Azure Virtual Machines with Azure NetApp Files - Azure Example Scenarios](/azure/architecture/example-scenario/file-storage/sql-server-azure-netapp-files)
* [SQL Server on Azure Deployment Guide Using Azure NetApp Files](https://techcommunity.microsoft.com/t5/azure-architecture-blog/deploying-sql-server-on-azure-using-azure-netapp-files/ba-p/3023143)
* [Benefits of using Azure NetApp Files for SQL Server deployment](solutions-benefits-azure-netapp-files-sql-server.md)
* [Deploy SQL Server Over SMB with Azure NetApp Files](https://www.youtube.com/watch?v=x7udfcYbibs)
* [Deploy SQL Server Always-On Failover Cluster over SMB with Azure NetApp Files](https://www.youtube.com/watch?v=zuNJ5E07e8Q) 
* [Deploy Always-On Availability Groups with Azure NetApp Files](https://www.youtube.com/watch?v=y3VQmzzeyvc) 

## SAP on Azure solutions

This section provides references to SAP on Azure solutions. 

### Generic SAP and SAP Netweaver 

* [Run SAP NetWeaver in Windows on Azure - Azure Architecture Center](/azure/architecture/reference-architectures/sap/sap-netweaver)
* [SAP applications on Microsoft Azure using Azure NetApp Files](https://www.netapp.com/us/media/tr-4746.pdf)
* [High availability for SAP NetWeaver on Azure VMs on SUSE Linux Enterprise Server with Azure NetApp Files for SAP applications](../virtual-machines/workloads/sap/high-availability-guide-suse-netapp-files.md)
* [High availability for SAP NetWeaver on Azure VMs on Red Hat Enterprise Linux with Azure NetApp Files for SAP applications](../virtual-machines/workloads/sap/high-availability-guide-rhel-netapp-files.md)
* [High availability for SAP NetWeaver on Azure VMs on Windows with Azure NetApp Files (SMB) for SAP applications](../virtual-machines/workloads/sap/high-availability-guide-windows-netapp-files-smb.md)
* [Using Windows DFS-N to support flexible SAPMNT share creation for SMB-based file share](../virtual-machines/workloads/sap/high-availability-guide-windows-dfs.md)
* [High availability for SAP NetWeaver on Azure VMs on Red Hat Enterprise Linux for SAP applications multi-SID guide](../virtual-machines/workloads/sap/high-availability-guide-rhel-multi-sid.md)

### SAP HANA 

* [SAP HANA for Linux VMs in scale-up systems - Azure Architecture Center](/azure/architecture/reference-architectures/sap/run-sap-hana-for-linux-virtual-machines)
* [SAP S/4HANA in Linux on Azure - Azure Architecture Center](/azure/architecture/reference-architectures/sap/sap-s4hana)
* [Run SAP BW/4HANA with Linux VMs - Azure Architecture Center](/azure/architecture/reference-architectures/sap/run-sap-bw4hana-with-linux-virtual-machines)
* [SAP HANA Azure virtual machine storage configurations](../virtual-machines/workloads/sap/hana-vm-operations-storage.md)
* [NFS v4.1 volumes on Azure NetApp Files for SAP HANA](../virtual-machines/workloads/sap/hana-vm-operations-netapp.md)
* [High availability of SAP HANA Scale-up with Azure NetApp Files on Red Hat Enterprise Linux](../virtual-machines/workloads/sap/sap-hana-high-availability-netapp-files-red-hat.md)
* [SAP HANA scale-out with standby node on Azure VMs with Azure NetApp Files on SUSE Linux Enterprise Server](../virtual-machines/workloads/sap/sap-hana-scale-out-standby-netapp-files-suse.md)
* [SAP HANA scale-out with standby node on Azure VMs with Azure NetApp Files on Red Hat Enterprise Linux](../virtual-machines/workloads/sap/sap-hana-scale-out-standby-netapp-files-rhel.md)
* [SAP HANA scale-out with HSR and Pacemaker on RHEL - Azure Virtual Machines](../virtual-machines/workloads/sap/sap-hana-high-availability-scale-out-hsr-rhel.md)
* [Azure Application Consistent Snapshot tool (AzAcSnap)](azacsnap-introduction.md)
* [SAP HANA Disaster Recovery with Azure NetApp Files](https://docs.netapp.com/us-en/netapp-solutions-sap/pdfs/sidebar/SAP_HANA_Disaster_Recovery_with_Azure_NetApp_Files.pdf)

### SAP AnyDB

* [SAP System on Oracle Database on Azure - Azure Architecture Center](/azure/architecture/example-scenario/apps/sap-on-oracle)
* [Oracle Azure Virtual Machines DBMS deployment for SAP workload - Azure Virtual Machines](../virtual-machines/workloads/sap/dbms_guide_oracle.md#oracle-configuration-guidelines-for-sap-installations-in-azure-vms-on-linux)
* [Deploy SAP AnyDB (Oracle 19c) with Azure NetApp Files](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/deploy-sap-anydb-oracle-19c-with-azure-netapp-files/ba-p/2064043)
* [IBM Db2 Azure Virtual Machines DBMS deployment for SAP workload using Azure NetApp Files](../virtual-machines/workloads/sap/dbms_guide_ibm.md#using-azure-netapp-files)

### SAP IQ-NLS

*	[Deploy SAP IQ-NLS HA Solution using Azure NetApp Files on SUSE Linux Enterprise Server](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/deploy-sap-iq-nls-ha-solution-using-azure-netapp-files-on-suse/ba-p/1651172#.X2tDfpNzBh4.linkedin)
* [How to manage SAP IQ License in HA Scenario](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/how-to-manage-sap-iq-license-in-ha-scenario/ba-p/2052583)

### SAP tech community and blog posts 

* [Azure NetApp Files – SAP HANA backup in seconds](https://blog.netapp.com/azure-netapp-files-sap-hana-backup-in-seconds/)
* [Azure NetApp Files – Restore your HANA database from a snapshot backup](https://blog.netapp.com/azure-netapp-files-backup-sap-hana)
* [Azure NetApp Files – SAP HANA offloading backup with Cloud Sync](https://blog.netapp.com/azure-netapp-files-sap-hana)
* [Speed up your SAP HANA system copies using Azure NetApp Files](https://blog.netapp.com/sap-hana-faster-using-azure-netapp-files/)
* [Cloud Volumes ONTAP and Azure NetApp Files: SAP HANA system migration made easy](https://blog.netapp.com/cloud-volumes-ontap-and-azure-netapp-files-sap-hana-system-migration-made-easy/)
* [Architectural Decisions to maximize ANF investment in HANA N+M Scale-Out Architecture - Part 1](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/architectural-decisions-to-maximize-anf-investment-in-hana-n-m/ba-p/2078737)
* [Architectural Decisions to maximize ANF investment in HANA N+M Scale-Out Architecture - Part 2](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/architectural-decisions-to-maximize-anf-investment-in-hana-n-m/ba-p/2117130)
* [Architectural Decisions to maximize ANF investment in HANA N+M Scale-Out Architecture - Part 3](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/architectural-decisions-to-maximize-anf-investment-in-hana-n-m/ba-p/2215948)
* [SAP Landscape sizing and volume consolidation with Azure NetApp Files](https://techcommunity.microsoft.com/t5/sap-on-microsoft/sap-landscape-sizing-and-volume-consolidation-with-anf/m-p/2145572/highlight/true#M14)
* [Gain first hands-on experience with the new automated S/4HANA deployment in Microsoft Azure](https://blogs.sap.com/2021/09/13/gain-first-hands-on-experience-with-the-new-automated-s-4hana-deployment-in-microsoft-azure/)

## Azure VMware Solutions

* [Azure NetApp Files with Azure VMware Solution - Guest OS Mounts](../azure-vmware/netapp-files-with-azure-vmware-solution.md)

## Virtual Desktop Infrastructure solutions

This section provides references for Virtual Desktop infrastructure solutions.

### <a name="windows-virtual-desktop"></a>Azure Virtual Desktop

* [Benefits of using Azure NetApp Files with Azure Virtual Desktop](solutions-windows-virtual-desktop.md)
* [Storage options for FSLogix profile containers in Azure Virtual Desktop](../virtual-desktop/store-fslogix-profile.md#azure-platform-details)
* [Create an FSLogix profile container for a host pool using Azure NetApp Files](../virtual-desktop/create-fslogix-profile-container.md)
* [Azure Virtual Desktop at enterprise scale](/azure/architecture/example-scenario/wvd/windows-virtual-desktop)
* [Microsoft FSLogix for the enterprise - Azure NetApp Files best practices](/azure/architecture/example-scenario/wvd/windows-virtual-desktop-fslogix#azure-netapp-files-best-practices)
* [Setting up Azure NetApp Files for MSIX App Attach](https://techcommunity.microsoft.com/t5/windows-virtual-desktop/setting-up-azure-netapp-files-for-msix-app-attach-step-by-step/m-p/1990021)

### Citrix   

* [Citrix Profile Management with Azure NetApp Files Best Practices Guide](https://www.netapp.com/pdf.html?item=/media/55973-tr-4901.pdf)


## HPC solutions

This section provides references for High Performance Computing (HPC) solutions. 

### Generic HPC

* [Azure NetApp Files: Getting the most out of your cloud storage](https://cloud.netapp.com/hubfs/Resources/ANF%20PERFORMANCE%20TESTING%20IN%20TEMPLATE.pdf)
* [Run MPI workloads with Azure Batch and Azure NetApp Files](https://azure.microsoft.com/resources/run-mpi-workloads-with-azure-batch-and-azure-netapp-files/)
* [Azure Cycle Cloud: CycleCloud HPC environments on Azure NetApp Files](/azure/cyclecloud/overview)

### Oil and gas

* [High performance computing (HPC): Oil and gas in Azure](https://techcommunity.microsoft.com/t5/azure-global/high-performance-computing-hpc-oil-and-gas-in-azure/ba-p/824926)
* [Run reservoir simulation software on Azure](/azure/architecture/example-scenario/infrastructure/reservoir-simulation)

### Electronic design automation (EDA)

* [EDA workloads on Azure NetApp Files - Performance Best Practice](https://techcommunity.microsoft.com/t5/azure-global/eda-workloads-on-azure-netapp-files-performance-best-practice/ba-p/2119979)
* [Benefits of using Azure NetApp Files for electronic design automation](solutions-benefits-azure-netapp-files-electronic-design-automation.md)
* [Azure CycleCloud: EDA HPC Lab with Azure NetApp Files](https://github.com/Azure/cyclecloud-hands-on-labs/blob/master/EDA/README.md)
* [Azure for the semiconductor industry](https://azurecomcdn.azureedge.net/cvt-f40f39cd9de2d875ab0c198a8d7b186350cf0bca161e80d7896941389685d012/mediahandler/files/resourcefiles/azure-for-the-semiconductor-industry/Azure_for_the_Semiconductor_Industry.pdf)

### Analytics

* [SAS on Azure architecture guide - Azure Architecture Center | Azure NetApp Files](/azure/architecture/guide/sas/sas-overview#azure-netapp-files-nfs)
* [Azure NetApp Files: A shared file system to use with SAS Grid on Microsoft Azure](https://communities.sas.com/t5/Administration-and-Deployment/Azure-NetApp-Files-A-shared-file-system-to-use-with-SAS-Grid-on/m-p/705192)
* [Azure NetApp Files: A shared file system to use with SAS Grid on MS Azure – RHEL8.3/nconnect UPDATE](https://communities.sas.com/t5/Administration-and-Deployment/Azure-NetApp-Files-A-shared-file-system-to-use-with-SAS-Grid-on/m-p/722261#M21648)
* [Best Practices for Using Microsoft Azure with SAS®](https://communities.sas.com/t5/Administration-and-Deployment/Best-Practices-for-Using-Microsoft-Azure-with-SAS/m-p/676833#M19680)

## Azure platform services solutions

This section provides solutions for Azure platform services. 

### Azure Kubernetes Services and Kubernetes

* [Astra: protect, recover, and manage your AKS workloads on Azure NetApp Files](https://cloud.netapp.com/hubfs/Astra%20Azure%20Documentation.pdf) 
* [Integrate Azure NetApp Files with Azure Kubernetes Service](../aks/azure-netapp-files.md)
* [Application data protection for AKS workloads on Azure NetApp Files - Azure Example Scenarios](/azure/architecture/example-scenario/file-storage/data-protection-kubernetes-astra-azure-netapp-files)
* [Disaster Recovery of AKS workloads with Astra Control Service and Azure NetApp Files](https://techcommunity.microsoft.com/t5/azure-architecture-blog/disaster-recovery-of-aks-workloads-with-astra-control-service/ba-p/2948089)
* [Protecting MongoDB on AKS/ANF with Astra Control Service using custom execution hooks](https://techcommunity.microsoft.com/t5/azure-architecture-blog/protecting-mongodb-on-aks-anf-with-astra-control-service-using/ba-p/3057574)
* [Comparing and Contrasting the AKS/ANF NFS subdir external provisioner with Astra Trident](https://techcommunity.microsoft.com/t5/azure-architecture-blog/comparing-and-contrasting-the-aks-anf-nfs-subdir-external/ba-p/3057547)
* [Out-of-This-World Kubernetes performance on Azure with Azure NetApp Files](https://cloud.netapp.com/blog/ma-anf-blg-configure-kubernetes-openshift)
* [Azure NetApp Files + Trident = Dynamic and Persistent Storage for Kubernetes](https://anfcommunity.com/2021/02/16/azure-netapp-files-trident-dynamic-and-persistent-storage-for-kubernetes/)
* [Trident - Storage Orchestrator for Containers](https://netapp-trident.readthedocs.io/en/stable-v20.04/kubernetes/operations/tasks/backends/anf.html)
* [Magento e-commerce platform in Azure Kubernetes Service (AKS)](/azure/architecture/example-scenario/magento/magento-azure)

### Azure Red Hat Openshift   

*	[Using Trident to Automate Azure NetApp Files from OpenShift](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/using-trident-to-automate-azure-netapp-files-from-openshift/ba-p/2367351)

### Azure Batch

* [Run MPI workloads with Azure Batch and Azure NetApp Files](https://azure.microsoft.com/resources/run-mpi-workloads-with-azure-batch-and-azure-netapp-files/)
