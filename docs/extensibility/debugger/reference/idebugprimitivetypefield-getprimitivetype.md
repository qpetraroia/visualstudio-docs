---
description: "Retrieves the primitive type that is associated with this field."
title: IDebugPrimitiveTypeField::GetPrimitiveType | Microsoft Docs
ms.date: 11/04/2016
ms.topic: reference
helpviewer_keywords:
- GetPrimitiveType
- IDebugPrimitiveTypeField::GetPrimitiveType
ms.assetid: a186c922-bbfe-478c-a744-b21eb4672d8f
author: leslierichardson95
ms.author: lerich
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
- vssdk
dev_langs:
- CPP
- CSharp
---
# IDebugPrimitiveTypeField::GetPrimitiveType

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the primitive type that is associated with this field.

## Syntax

### [C#](#tab/csharp)
```csharp
int GetPrimitiveType (
   out uint pdwType
);
```
### [C++](#tab/cpp)
```cpp
HRESULT GetPrimitiveType (
   DWORD* pdwType
);
```
---

## Parameters
`pdwType`\
[out] Value from the [CorElementType Enumeration](/dotnet/framework/unmanaged-api/metadata/corelementtype-enumeration) that represents the primitive type.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE`.

## See also
- [IDebugPrimitiveTypeField](../../../extensibility/debugger/reference/idebugprimitivetypefield.md)
