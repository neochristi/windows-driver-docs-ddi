---
UID: NC:d3d12umddi.PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE
title: PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE (d3d12umddi.h)
description: Determines the size of the user-mode display driver's private region of memory for a hull or domain shader.
ms.assetid: 40bbfdfa-e310-4e77-9e8c-2800a64f6bcb
ms.date: 10/19/2018
ms.topic: callback
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE"
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
- apiref
api_type: 
- UserDefined
api_location: 
- d3d12umddi.h
api_name: 
- PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE
product: 
- Windows
targetos: Windows
tech.root: display
dev_langs:
 - c++
ms.custom: RS5
---

# PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE callback function

## -description

Determines the size of the user-mode display driver's private region of memory for a hull or domain shader.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE Pfnd3d12ddiCalcPrivateTessellationShaderSize; 

// Definition

SIZE_T Pfnd3d12ddiCalcPrivateTessellationShaderSize 
(
	 D3D12DDI_HDEVICE
	CONST UINT *pShaderCode
	 D3D12DDI_HROOTSIGNATURE
	CONST D3D12DDIARG_TESSELLATION_IO_SIGNATURES *
)
{...}

PFND3D12DDI_CALC_PRIVATE_TESSELLATION_SHADER_SIZE 


```

## -parameters

### -param D3D12DDI_HDEVICE

A handle to the display device (graphics context).

### -param *pShaderCode

Pointer to a shader code.

### -param D3D12DDI_HROOTSIGNATURE

A handle to a root signature.

### -param *

Pointer to a D3D12DDIARG_TESSELLATION_IO_SIGNATURES structure.



## -returns

Returns SIZE_T.
