---
UID: NF:wpprecorder.imp_WppRecorderLinkCounters
title: imp_WppRecorderLinkCounters function (wpprecorder.h)
description: The WppRecorderLinkCounters.
old-location: devtest\wpprecorderlinkcounters.htm
tech.root: devtest
ms.date: 02/23/2018
keywords: ["imp_WppRecorderLinkCounters function"]
ms.keywords: WppRecorderLinkCounters, devtest.wpprecorderlinkcounters, imp_WppRecorderLinkCounters, imp_WppRecorderLinkCounters function [Driver Development Tools], wpprecorder/imp_WppRecorderLinkCounters
req.header: wpprecorder.h
req.include-header: 
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
req.typenames: 
f1_keywords:
 - imp_WppRecorderLinkCounters
 - wpprecorder/imp_WppRecorderLinkCounters
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - wpprecorder.h
api_name:
 - imp_WppRecorderLinkCounters
---

# imp_WppRecorderLinkCounters function


## -description

The <b>WppRecorderLinkCounters</b> method  uses a sequence number to merge logs captured in different buffers by a driver.

## -parameters

### -param WppCb

<p>ID of the counter whose current value is to be read.</p>

### -param CounterOwner [in]


ID of the counter whose current value is to be read.

## -returns

Returns STATUS_SUCCESS if the operation succeeds. Otherwise, one of appropriate <a href="/windows-hardware/drivers/kernel/ntstatus-values">NTSTATUS</a> values
