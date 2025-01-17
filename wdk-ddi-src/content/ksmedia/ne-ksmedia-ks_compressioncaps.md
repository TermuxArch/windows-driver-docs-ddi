---
UID: NE:ksmedia.__unnamed_enum_105
title: KS_CompressionCaps (ksmedia.h)
description: The KS_CompressionCaps enumeration defines compression capabilities of a device.
old-location: stream\ks_compressioncaps.htm
tech.root: stream
ms.date: 04/23/2018
keywords: ["KS_CompressionCaps enumeration"]
ms.keywords: KS_CompressionCaps, KS_CompressionCaps enumeration [Streaming Media Devices], KS_CompressionCaps_CanBFrame, KS_CompressionCaps_CanCrunch, KS_CompressionCaps_CanKeyFrame, KS_CompressionCaps_CanQuality, KS_CompressionCaps_CanWindow, ksmedia/KS_CompressionCaps, ksmedia/KS_CompressionCaps_CanBFrame, ksmedia/KS_CompressionCaps_CanCrunch, ksmedia/KS_CompressionCaps_CanKeyFrame, ksmedia/KS_CompressionCaps_CanQuality, ksmedia/KS_CompressionCaps_CanWindow, stream.ks_compressioncaps, vidcapstruct_77c66492-8105-4cf2-a303-7819d83adbb4.xml
req.header: ksmedia.h
req.include-header: Ksmedia.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
targetos: Windows
req.typenames: KS_CompressionCaps
f1_keywords:
 - KS_CompressionCaps
 - ksmedia/KS_CompressionCaps
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - ksmedia.h
api_name:
 - KS_CompressionCaps
---

# KS_CompressionCaps enumeration


## -description

The KS_CompressionCaps enumeration defines compression capabilities of a device.

## -enum-fields

### -field KS_CompressionCaps_CanQuality

The video compressor supports quality settings.

### -field KS_CompressionCaps_CanCrunch

The video compressor can compress the video to a specified data rate. If a minidriver supports this capability, the <b>dwBitRate</b> member of the <a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-tagks_videoinfoheader">KS_VIDEOINFOHEADER</a> structure specifies the default data rate.

### -field KS_CompressionCaps_CanKeyFrame

The video compressor supports a user-specified key-frame rate.

### -field KS_CompressionCaps_CanBFrame

The video compressor supports a user-specified P frame interval. The frames that occur between the key frames and P frames are bidirectional (B) frames.

### -field KS_CompressionCaps_CanWindow

The video compressor supports a user-specified window size (that is, the number of frames whose average size cannot exceed the specified data rate).

## -see-also

<a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-ksproperty_videocompression_getinfo_s">KSPROPERTY_VIDEOCOMPRESSION_GETINFO_S</a>



<a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-tagks_videoinfoheader">KS_VIDEOINFOHEADER</a>
