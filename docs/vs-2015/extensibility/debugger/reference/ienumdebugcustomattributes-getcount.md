---
title: "IEnumDebugCustomAttributes::GetCount | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IEnumCustomAttributes::GetCount"
helpviewer_keywords: 
  - "IEnumDebugCustomAttributes::GetCount"
ms.assetid: fafe826f-4ebf-4572-b2a3-d5dd2916c12f
caps.latest.revision: 10
ms.author: "gregvanl"
manager: "ghogen"
---
# IEnumDebugCustomAttributes::GetCount
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IEnumDebugCustomAttributes::GetCount](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/ienumdebugcustomattributes-getcount).  
  
Gets the number of custom attributes in an enumerator.  
  
## Syntax  
  
```cpp#  
HRESULT GetCount(   
   ULONG* pcelt  
);  
```  
  
```csharp  
int GetCount(  
   out uint pcelt  
);  
```  
  
#### Parameters  
 `pcelt`  
 [out] Returns the number of elements in the enumeration.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 This method is not part of the customary COM enumeration interface which specifies that only `Next`, `Clone`, `Skip`, and `Reset` need to be implemented.  
  
## See Also  
 [IEnumDebugCustomAttributes](../../../extensibility/debugger/reference/ienumdebugcustomattributes.md)

