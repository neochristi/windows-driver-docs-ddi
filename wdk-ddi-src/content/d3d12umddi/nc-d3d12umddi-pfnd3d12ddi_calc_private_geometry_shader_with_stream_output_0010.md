---
UID: NC:d3d12umddi.PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010
title: PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 (d3d12umddi.h)
description: Calculates the geometry shader with stream output.
ms.assetid: 7d7a0dce-ff3a-42d7-8b8c-e24c59f8f1fe
ms.date: 10/19/2018
ms.topic: callback
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010"
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt: Windows 10
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
- PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010
product: 
- Windows
targetos: Windows
tech.root: display
dev_langs:
 - c++
ms.custom: RS5
---

# PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 callback function

## -description

Calculates the geometry shader with stream output.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 Pfnd3d12ddiCalcPrivateGeometryShaderWithStreamOutput0010; 

// Definition

SIZE_T Pfnd3d12ddiCalcPrivateGeometryShaderWithStreamOutput0010 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 *
)
{...}

PFND3D12DDI_CALC_PRIVATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 


```

## -parameters

### -param Arg1

A handle to the display device (graphics context).
 
### -param *

Pointer to a D3D12DDIARG_CREATE_GEOMETRY_SHADER_WITH_STREAM_OUTPUT_0010 structure.

## -returns

Returns SIZE_T.

## -remarks




## -see-also
