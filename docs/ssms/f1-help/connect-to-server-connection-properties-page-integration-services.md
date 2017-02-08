---
title: "Connect to SSIS Server (Connection Properties) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: "sql-non-specified"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "tools-ssms"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "sql13.ssiseditserverregistration.connectionproperties.f1"
  - "sql13.swb.connecttodts.connectionproperties.f1"
ms.assetid: c2513dab-8415-4e0c-9475-6d4ab97fea7c
caps.latest.revision: 4
author: "stevestein"
ms.author: "sstein"
manager: "jhubbard"
---
# Connect to Server (Connection Properties Page) Integration Services
Use this tab to view or specify options when connecting to [!INCLUDE[msCoName](../../includes/msconame_md.md)] [!INCLUDE[ssISnoversion](../../includes/ssisnoversion_md.md)] or registering [!INCLUDE[ssIS](../../includes/ssis_md.md)] in **Registered Servers**. **Connect** and **Options** only appear in this dialog box when connecting. **Test** and **Save** only appear in this dialog box when registering [!INCLUDE[ssIS](../../includes/ssis_md.md)].  
  
## Options  
**Port number**  
Enter the port number used by [!INCLUDE[ssIS](../../includes/ssis_md.md)].  
  
**Connection time-out**  
Enter the number of seconds to wait for a connection to be established before timing out. The default value is 15 seconds.  
  
**Execution time-out**  
Enter the amount of time in seconds to wait before execution of a task is completed on the server. The default value is zero seconds, which indicates there is no time-out.  
  
**Reset All**  
Replace all manually entered connection property values with the default values.  
  
**Connect**  
Attempt a connection using the listed values.  
  
**Options**  
Click to change the dialog and hide the additional server connection options, such as remembering the password.  
  
**Test**  
When registering [!INCLUDE[ssIS](../../includes/ssis_md.md)] in **Registered Servers**, click to test the connection.  
  
**Save**  
Saves the settings in **Registered Servers**.  
  