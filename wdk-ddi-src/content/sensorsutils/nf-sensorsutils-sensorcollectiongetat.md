---
UID: NF:sensorsutils.SensorCollectionGetAt
title: SensorCollectionGetAt function (sensorsutils.h)
description: This routine returns the PROPERTYKEY and PROPVARIANT associated with the nth element in the provided sensor collection list.
ms.date: 08/08/2018
keywords: ["SensorCollectionGetAt function"]
tech.root: sensors
ms.keywords: SensorCollectionGetAt
req.header: sensorsutils.h
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
targetos: Windows
ms.custom: RS5
f1_keywords:
 - SensorCollectionGetAt
 - sensorsutils/SensorCollectionGetAt
topic_type:
 - apiref
api_type:
 - LibDef
api_location:
 - sensorsutils.h
api_name:
 - SensorCollectionGetAt
product:
 - Windows
---

# SensorCollectionGetAt function


## -description

This routine returns the PROPERTYKEY and PROPVARIANT associated with the nth element in the provided sensor collection list.

## -parameters

### -param Index [in]

Zero-based index of the element in the pSensorsList.

### -param pSensorsList [in]

Pointer to a sensor collection list.

### -param pKey [out]

Size of data.

### -param pValue [out]

Location of the data.

## -returns

This function returns STATUS_NOT_FOUND if not found, STATUS_SUCCESS otherwise.

## -remarks

## -see-also

