---
UID: NC:d3d12umddi.PFND3D12DDI_UMD_CALLBACK_METHOD
title: PFND3D12DDI_UMD_CALLBACK_METHOD
author: windows-driver-content
description: Used by the user mode driver to complete a context.
tech.root: display
ms.assetid: ae1f4e0e-f801-41b1-a283-dd9ec9559e45
ms.author: windowsdriverdev
ms.date: 04/04/2019
ms.topic: callback
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_UMD_CALLBACK_METHOD"
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt: Windows 10, version 1903
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
 - PFND3D12DDI_UMD_CALLBACK_METHOD
product:
- Windows
targetos: Windows
dev_langs:
 - c++
ms.custom: D3D12 Release 6, Build rev 3., 19H1
---

# PFND3D12DDI_UMD_CALLBACK_METHOD callback function

## -description

Used by the user mode driver to complete a context.

## -prototype

```
//Declaration

PFND3D12DDI_UMD_CALLBACK_METHOD Pfnd3d12ddiUmdCallbackMethod; 

// Definition

void Pfnd3d12ddiUmdCallbackMethod 
(
	void *pContext
)
{...}

```

## -parameters

### -param *pContext

A pointer to the context.

## -returns

Returns void.

## -remarks

## -see-also
