---
UID: NF:portcls.IMiniportAudioEngineNode.GetBufferSizeRange
title: IMiniportAudioEngineNode::GetBufferSizeRange
author: windows-driver-content
description: Gets the minimum and maximum buffer size that the hardware audio engine can support.
old-location: audio\iminiportaudioenginenode_getbuffersizerange.htm
tech.root: audio
ms.assetid: 75CBDD4F-618F-4618-9D53-4A8DF40992B0
ms.date: 05/08/2018
ms.keywords: GetBufferSizeRange, GetBufferSizeRange method [Audio Devices], GetBufferSizeRange method [Audio Devices],IMiniportAudioEngineNode interface, IMiniportAudioEngineNode interface [Audio Devices],GetBufferSizeRange method, IMiniportAudioEngineNode.GetBufferSizeRange, IMiniportAudioEngineNode::GetBufferSizeRange, audio.iminiportaudioenginenode_getbuffersizerange, portcls/IMiniportAudioEngineNode::GetBufferSizeRange
ms.topic: method
req.header: portcls.h
req.include-header: 
req.target-type: Universal
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	COM
api_location:
-	Portcls.h
api_name:
-	IMiniportAudioEngineNode.GetBufferSizeRange
product:
- Windows
targetos: Windows
req.typenames: 
---

# IMiniportAudioEngineNode::GetBufferSizeRange


## -description


Gets the minimum and maximum buffer size that the hardware audio engine can support.


## -parameters




### -param ulNodeId [in]

The ID for the node that represents the audio device.


### -param pKsDataFormatWfx [in]

A <a href="https://msdn.microsoft.com/library/windows/hardware/ff537095">KSDATAFORMAT_WAVEFORMATEX</a> structure that represents the audio data format for the audio device.


### -param pBufferSizeRange [out]

A <a href="https://msdn.microsoft.com/library/windows/hardware/hh450864">KSAUDIOENGINE_BUFFER_SIZE_RANGE</a> structure that represents the minimum and maximum buffer size that the hardware audio engine can support at the time when it is called.


## -returns



<b>GetBufferSizeRange</b> returns S_OK, if the call was successful. Otherwise, the method returns an appropriate error 

code.




## -see-also




<a href="https://msdn.microsoft.com/library/windows/hardware/dn302040">IMiniportAudioEngineNode</a>
 

 

