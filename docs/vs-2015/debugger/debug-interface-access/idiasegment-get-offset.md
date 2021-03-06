---
title: "IDiaSegment::get_offset | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IDiaSegment::get_offset method"
ms.assetid: 97415ac6-b072-4e3c-9dd3-73087ae605fc
caps.latest.revision: 11
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaSegment::get_offset
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaSegment::get_offset](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiasegment-get-offset).  
  
Retrieves the offset, in segments, where the section begins.  
  
## Syntax  
  
```cpp#  
HRESULT get_offset (   
   DWORD* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns the offset, in segments, where the section begins.  
  
## Return Value  
 If successful, returns `S_OK`. Returns `S_FALSE` if this property is not supported. Otherwise, returns an error code.  
  
## See Also  
 [IDiaSegment](../../debugger/debug-interface-access/idiasegment.md)



