---
title: "COR_GC_THREAD_STATS_TYPES Enumeration | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "COR_GC_THREAD_STATS_TYPES"
apilocation: 
  - "mscoree.dll"
apitype: "COM"
f1_keywords: 
  - "COR_GC_THREAD_STATS_TYPES"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "COR_GC_THREAD_STATS_TYPES enumeration [.NET Framework hosting]"
ms.assetid: aa227704-0ab1-4b08-aee2-1f439762162e
caps.latest.revision: 7
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# COR_GC_THREAD_STATS_TYPES Enumeration
Indicates the garbage collection statistics for a thread.  
  
## Syntax  
  
```  
typedef enum {  
    COR_GC_THREAD_HAS_PROMOTED_BYTES  = 0x00000001  
} COR_GC_THREAD_STATS_TYPES;  
```  
  
## Members  
  
|Member|Description|  
|------------|-----------------|  
|`COR_GC_THREAD_HAS_PROMOTED_BYTES`|The thread has bytes that were promoted in the most recent garbage collection.|  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** GCHost.idl, GCHost.h  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [Hosting Enumerations](../../../../docs/framework/unmanaged-api/hosting/hosting-enumerations.md)