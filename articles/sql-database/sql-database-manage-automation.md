---
title: Manage Azure SQL Databases using Azure Automation | Microsoft Docs
description: Learn about how the Azure Automation service can be used to manage Azure SQL databases at scale.
services: sql-database, automation
author: CarlRabeler
manager: craigg
ms.service: sql-database
ms.custom: monitor & tune
ms.topic: article
ms.date: 04/01/2018
ms.author: carlrab

---
# Managing Azure SQL Databases using Azure Automation
This guide will introduce you to the Azure Automation service, and how it can be used to simplify management of your Azure SQL databases.

## What is Azure Automation?
[Azure Automation](https://azure.microsoft.com/services/automation/) is an Azure service for simplifying cloud management through process automation. Using Azure Automation, long-running, manual, error-prone, and frequently repeated tasks can be automated to increase reliability, efficiency, and time to value for your organization.

Azure Automation provides a highly-reliable and highly-available workflow execution engine that scales to meet your needs as your organization grows. In Azure Automation, processes can be kicked off manually, by 3rd-party systems, or at scheduled intervals so that tasks happen exactly when needed.

Lower operational overhead and free up IT / DevOps staff to focus on work that adds business value by moving your cloud management tasks to be run automatically by Azure Automation.

## How can Azure Automation help manage Azure SQL databases?
Azure SQL Database can be managed in Azure Automation by using the [Azure SQL Database PowerShell cmdlets](https://docs.microsoft.com/powershell/servicemanagement/azure.sqldatabase/v1.6.1/azure.sqldatabase/) that are available in the [Azure PowerShell tools](/powershell/azure/overview). Azure Automation has these Azure SQL Database PowerShell cmdlets available out of the box, so that you can perform all of your SQL DB management tasks within the service. You can also pair these cmdlets in Azure Automation with the cmdlets for other Azure services, to automate complex tasks across Azure services and 3rd party systems.

Azure Automation also has the ability to communicate with SQL servers directly, by issuing SQL commands using PowerShell.

The [Azure Automation runbook gallery](https://azure.microsoft.com/blog/2014/10/07/introducing-the-azure-automation-runbook-gallery/) contains a variety of product team and community runbooks to get started automating management of Azure SQL Databases, other Azure services, and 3rd party systems. Gallery runbooks include:

* [Run SQL queries against a SQL Server database](https://gallery.technet.microsoft.com/scriptcenter/How-to-use-a-SQL-Command-be77f9d2)
* [Vertically scale (up or down) an Azure SQL Database on a schedule](https://gallery.technet.microsoft.com/scriptcenter/Azure-SQL-Database-e957354f)
* [Truncate a SQL table if its database approaches its maximum size](https://gallery.technet.microsoft.com/scriptcenter/Azure-Automation-Your-SQL-30f8736b)
* [Index tables in an Azure SQL Database if they are highly fragmented](https://gallery.technet.microsoft.com/scriptcenter/Indexes-tables-in-an-Azure-73a2a8ea)

## Next steps
Now that you've learned the basics of Azure Automation and how it can be used to manage Azure SQL databases, follow these links to learn more about Azure Automation.

* [Azure Automation Overview](../automation/automation-intro.md)
* [My first runbook](../automation/automation-first-runbook-graphical.md)
* [Azure Automation learning map](https://azure.microsoft.com/documentation/learning-paths/automation/)
* [Azure Automation: Your SQL Agent in the Cloud](https://azure.microsoft.com/blog/2014/06/26/azure-automation-your-sql-agent-in-the-cloud/) 

