---
UID: NC:d3d12umddi.PFND3D12DDI_CREATE_COMMAND_RECORDER_0040
title: PFND3D12DDI_CREATE_COMMAND_RECORDER_0040
author: windows-driver-content
description: Create a command to start recording data.
ms.assetid: 24492843-f40e-4761-b5a5-fe904aafb710
ms.date: 10/19/2018
ms.topic: callback
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
-	apiref
api_type:
-	UserDefined
api_location:
-	d3d12umddi.h
api_name:
-	PFND3D12DDI_CREATE_COMMAND_RECORDER_0040
product: 
- Windows
targetos: Windows
tech.root: display
---

# PFND3D12DDI_CREATE_COMMAND_RECORDER_0040 callback function

## -description

Create a command to start recording data.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CREATE_COMMAND_RECORDER_0040 Pfnd3d12ddiCreateCommandRecorder0040;

// Definition

HRESULT Pfnd3d12ddiCreateCommandRecorder0040
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATE_COMMAND_RECORDER_0040 *
	 D3D12DDI_HCOMMANDRECORDER_0040
)
{...}

PFND3D12DDI_CREATE_COMMAND_RECORDER_0040


```

## -parameters

### -param D3D12DDI_HDEVICE

A handle to the display device (graphics context).

### -param D3D12DDIARG_CREATE_COMMAND_RECORDER_0040

Pointer to a D3D12DDIARG_CREATE_COMMAND_RECORDER_0040 structure that describes the parameters that the user-mode display driver uses to create a command recorder.

### -param D3D12DDI_HCOMMANDRECORDER_0040

The command recorder.

## -returns

Returns an HRESULT.

## -remarks




## -see-also
