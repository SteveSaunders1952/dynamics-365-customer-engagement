---
title: "Automate your business processes in Customer Engagement (Developer Guide for Dynamics 365 for Customer Engagement apps)| MicrosoftDocs"
description: "Learn about automating your business processess. A business process can be of two types: automated processes that rely solely on communication among applications based on a set of rules, and interactive processes that also rely on people to initiate and run the process, and to make the appropriate decisions during the running of the process."
ms.custom: 
ms.date: 10/31/2017
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
applies_to: 
  - Dynamics 365 for Customer Engagement (online)
helpviewer_keywords: 
  - process
  - workflow
ms.assetid: 3ef415ed-d815-45de-8a7c-398b80d23cbd
caps.latest.revision: 51
author: JimDaly
ms.author: jdaly
manager: amyla
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# Automate your business processes in Customer Engagement apps

[!INCLUDE[](../includes/cc_applies_to_update_9_0_0.md)]

Business processes are an integral part of any enterprise software application. A business process can be of two types: *automated* processes that rely solely on 
communication among applications based on a set of rules, and *interactive* processes that also rely on people to initiate and run the process, and to make the 
appropriate decisions during the running of the process.  
<!-- TODO: Do you really mean online here?-->  
 In [!INCLUDE[pn_dynamics_crm_online](../includes/pn-dynamics-crm-online.md)] apps, a process enables you to create and manage your automated and 
interactive business processes. While the name has been changed from workflow to *process*, the entity that’s used to implement a process is still called 
*workflow*. A [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] apps process provides many out-of-the-box components that business users and administrators 
can use to model their business processes. [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] apps also offers developers a mechanism to extend and customize 
the standard behavior of processes to achieve the functionality that their business applications require by allowing them to develop custom components.  
  
 A [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] apps process is based on the 
[Windows Workflow Foundation](https://msdn.microsoft.com/netframework/aa663328.aspx) programming model. 
[!INCLUDE[pn_Windows_Workflow_Foundation](../includes/pn-windows-workflow-foundation.md)] provides a runtime engine, a framework, a base library of activities, 
and default implementations of the runtime services. The [!INCLUDE[pn_Windows_Workflow_Foundation](../includes/pn-windows-workflow-foundation.md)] runtime engine 
manages process execution, and supports processes that can remain active for extended periods of time. It preserves the state of process execution during computer 
shutdown and restart.  
  
## In This Section  
 [Choose a Process (Workflow) Type for Your Automation](process-categories.md)  
  
 [Process Architecture for Dynamics 365 for Customer Engagement apps](process-architecture.md)  
  
 [Workflow and Process Entities](workflow-process-entities.md)  
  
 [Supported Types, Triggers, and Entities for Process](supported-types-triggers-entities-actions-processes.md)  
  
 [Custom Workflow Activities (Workflow Assemblies)](custom-workflow-activities-workflow-assemblies.md) 
  
 [Model the business process flow](model-business-process-flows.md)  
  
 [Create real-time workflows](create-real-time-workflows.md)  
  
 [Create Your Own Custom Operations](create-own-actions.md)  
  
 [Use Dialogs in Dynamics 365 for Customer Engagement apps](use-dialogs-guided-processes.md)  
  
 [Sample Code for Process and Workflow](sample-code-processes.md)  
  
## Related Sections  
 [Software Development Kit for Dynamics 365 for Customer Engagement apps](developer-guide.md)  
  
 [Write Plug-Ins for Dynamics 365 for Customer Engagement apps](write-plugin-extend-business-processes.md)  
  
 [Understanding the Asynchronous Service](asynchronous-service.md)
