---
title: "How to: Build Multiple Configurations Simultaneously | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: ba830937-3317-4674-8cc2-c0cd565603c5
caps.latest.revision: 10
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
---
# How to: Build Multiple Configurations Simultaneously
You can build most types of projects with multiple, or even all, of their build configurations at the same time by using the **Batch Build** dialog box. However, you can't build the following types of projects in multiple build configurations at the same time:  
  
1.  [!INCLUDE[win8_appname_long](../debugger/includes/win8_appname_long_md.md)] apps built for Windows using JavaScript.  
  
2.  All Visual Basic projects.  
  
 For more information about build configurations, see [Understanding Build Configurations](../ide/understanding-build-configurations.md).  
  
### To build a project in multiple build configurations  
  
1.  On the menu bar, choose **Build**, **Batch Build**.  
  
2.  In the **Build** column, select the check boxes for the configurations in which you want to build a project.  
  
    > [!TIP]
    >  To edit or create a build configuration for a solution, choose **Build**, **Configuration Manager** on the menu bar to open the **Configuration Manager** dialog box. After you have edited a build configuration for a solution, choose the **Rebuild** button in the **Batch Build** dialog box to update all build configurations for the projects in the solution.  
  
3.  Choose the **Build** or **Rebuild** buttons to build the project with the configurations that you specified.  
  
## See Also  
 [How to: Create and Edit Configurations](../ide/how-to-create-and-edit-configurations.md)   
 [Understanding Build Configurations](../ide/understanding-build-configurations.md)   
 [Building Multiple Projects in Parallel](../msbuild/building-multiple-projects-in-parallel-with-msbuild.md)