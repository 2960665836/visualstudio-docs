---
title: "IDiaSymbol::get_unmodifiedTypeId | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
ms.assetid: 4f7fc73c-f524-4d7a-b378-a9ab99a96104
caps.latest.revision: 3
author: "mikejo5000"
ms.author: "mikejo"
manager: ghogen
---
# IDiaSymbol::get_unmodifiedTypeId
Retrieves the ID of the original (unmodified) type.  
  
## Syntax  
  
```C++  
HRESULT get_unmodifiedTypeId(   
   DWORD* pRetVal);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] A pointer to a `DWORD` that holds the ID.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.  
  
## See Also  
 [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)