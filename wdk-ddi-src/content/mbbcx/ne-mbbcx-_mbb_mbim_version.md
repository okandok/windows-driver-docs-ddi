---
UID: NE:mbbcx._MBB_MBIM_VERSION
title: _MBB_MBIM_VERSION
author: windows-driver-content
description: The MBB_MBIM_VERSION enumeration defines the version of the MBIM specification that a client driver and its device support. 
tech.root: netvista
ms.assetid: 3326d39e-bd84-4740-89cf-7a5971ee4b7e
ms.date: 07/02/2018
ms.topic: enum
ms.keywords: _MBB_MBIM_VERSION, MBB_MBIM_VERSION, 
req.header: mbbcx.h
req.include-header:
req.target-type:
req.target-min-winverclnt: Windows 10, version 1809
req.target-min-winversvr:
req.kmdf-ver: 1.27
req.umdf-ver:
req.ddi-compliance:
req.max-support:
req.typenames: MBB_MBIM_VERSION
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	mbbcx.h
api_name: 
-	_MBB_MBIM_VERSION
product:
- Windows
targetos: Windows
ms.custom: RS5
---

# _MBB_MBIM_VERSION enumeration

## -description

> [!WARNING]
> Some information in this topic relates to prereleased product, which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.
> 
> MBBCx is preview only in Windows 10, version 1809.

The MBB_MBIM_VERSION enumeration defines the version of the MBIM specification that a client driver and its device support. 

## -enum-fields

### -field MBB_MBIM_VERSION1_0 

The client driver and device support the MBIM specification Rev 1.0.

### -field MBB_MBIM_VERSION1_0_ERRATA 

The client driver and device support the MBIM specification Rev 1.0 Errata-1.

## -remarks

Client drivers set the MBIM specification version they support in the **Version** member of the [**MBB_DEVICE_MBIM_PARAMETERS**](ns-mbbcx-_mbb_device_mbim_parameters.md) structure. 

Currently, client drivers must set the value of this field to **MBB_MBIM_VERSION1_0_ERRATA**.

## -see-also
