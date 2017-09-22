---
title: TF30249-The New Team Project Wizard could not retrieve the process template  | Team TFS
description: Occurs an error when the New Team Project Wizard cannot download the process template header information.
ms.prod: visual-studio-tfs-dev14
ms.technology: vs-devops-wit
ms.assetid: 3bdffbfa-9b0d-4222-8630-5e76330a511e
ms.manager: douge
ms.author: kaelli
ms.date: 01/20/2017
---

# TF30249: The New Team Project Wizard could not retrieve the process template information.

**TFS 2017 | TFS 2015 | TFS 2013**

This error occurs when the New Team Project Wizard cannot download the process template header information so the Wizard can display a list of the process templates available on the server. Because the actual process template XML files can be very large (up to 100 megabytes), the wizard downloads the smaller XML header file to save time.  
  
 There are two likely causes for this error:  
  
-   The network is not available.  
  
-   Your user account does not have sufficient permissions to access and download the process template files.  
  
 The following procedures will help you correct the problem.  
  
### To correct this error  
  
1.  Confirm that your local computer is plugged into the network and can access network resources.  
  
2.  Contact your Team Foundation Server administrator to confirm that the server is available on the network.  
  
3.  Contact your Team Foundation Server administrator and ask that the required permission be added to your user account.