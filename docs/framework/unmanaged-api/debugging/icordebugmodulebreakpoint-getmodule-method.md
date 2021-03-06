---
title: "ICorDebugModuleBreakpoint::GetModule Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugModuleBreakpoint.GetModule"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugModuleBreakpoint::GetModule"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugModuleBreakpoint::GetModule method [.NET Framework debugging]"
  - "GetModule method, ICorDebugModuleBreakpoint interface [.NET Framework debugging]"
ms.assetid: ffd5d9ec-4564-4200-b625-b306eec0ebd7
caps.latest.revision: 10
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugModuleBreakpoint::GetModule Method
Gets an interface pointer to an "ICorDebugModule" that references the module in which this breakpoint is set.  
  
## Syntax  
  
```  
HRESULT GetModule (  
    [out] ICorDebugModule   **ppModule  
);  
```  
  
#### Parameters  
 `ppModule`  
 [out] A pointer to the address of an `ICorDebugModule` interface that references the module in which the breakpoint is set.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 