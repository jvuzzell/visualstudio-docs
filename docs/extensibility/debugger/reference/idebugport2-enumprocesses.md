---
title: "IDebugPort2::EnumProcesses | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: reference
f1_keywords:
  - "IDebugPort2::EnumProcesses"
helpviewer_keywords:
  - "IDebugPort2::EnumProcesses"
ms.assetid: aafb32c5-5790-4807-a448-878a80256438
author: "gregvanl"
ms.author: "gregvanl"
manager: jillfra
ms.workload:
  - "vssdk"
---
# IDebugPort2::EnumProcesses
Returns a list of all the processes running on a port.

## Syntax

```cpp
HRESULT EnumProcesses( 
   IEnumDebugProcesses2** ppEnum
);
```

```csharp
int EnumProcesses( 
   out IEnumDebugProcesses2 ppEnum
);
```

#### Parameters
 `ppEnum`

 [out] Returns an [IEnumDebugProcesses2](../../../extensibility/debugger/reference/ienumdebugprocesses2.md) object that contains a list of all the processes running on a port.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See Also
- [IDebugPort2](../../../extensibility/debugger/reference/idebugport2.md)
- [IEnumDebugProcesses2](../../../extensibility/debugger/reference/ienumdebugprocesses2.md)