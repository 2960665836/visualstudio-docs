---
title: "IDebugReference2::Compare | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugReference2::Compare"
helpviewer_keywords: 
  - "IDebugReference2::Compare"
ms.assetid: 3361c495-2673-4b7c-82e3-dee74e1fa58d
caps.latest.revision: 10
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
---
# IDebugReference2::Compare
Compares one reference to another. Reserved for future use.  
  
## Syntax  
  
```cpp  
HRESULT Compare (   
   REFERENCE_COMPARE dwCompare,  
   IDebugReference2* pReference  
);  
```  
  
```csharp  
int Compare (   
   enum_REFERENCE_COMPARE dwCompare,  
   IDebugReference2       pReference  
);  
```  
  
#### Parameters  
 `dwCompare`  
 [in] A value from the [REFERENCE_COMPARE](../../../extensibility/debugger/reference/reference-compare.md) enumeration that specifies the comparison operation, for example, equal to, less than, or greater than.  
  
 `pReference`  
 [in] An [IDebugReference2](../../../extensibility/debugger/reference/idebugreference2.md) object representing the reference to be compared to.  
  
## Return Value  
 Always returns `E_NOTIMPL`.  
  
## See Also  
 [IDebugReference2](../../../extensibility/debugger/reference/idebugreference2.md)   
 [REFERENCE_COMPARE](../../../extensibility/debugger/reference/reference-compare.md)