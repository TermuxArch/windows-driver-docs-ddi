---
UID: NS:storport._STOR_ADDR_BTL8
title: _STOR_ADDR_BTL8 (storport.h)
description: The _STOR_ADDR_BTL8 structure (storport.h) contains the addressing information for an 8-bit Bus-Target-LUN (BTL8) address.
old-location: storage\stor_addr_btl8.htm
tech.root: storage
ms.date: 03/29/2018
keywords: ["STOR_ADDR_BTL8 structure"]
ms.keywords: "*PSTOR_ADDR_BTL8, PSTOR_ADDR_BTL8, PSTOR_ADDR_BTL8 structure pointer [Storage Devices], STOR_ADDR_BTL8, STOR_ADDR_BTL8 structure [Storage Devices], _STOR_ADDR_BTL8, storage.stor_addr_btl8, storport/PSTOR_ADDR_BTL8, storport/STOR_ADDR_BTL8"
req.header: storport.h
req.include-header: Storport.h, Scsi.h, Minitape.h
req.target-type: Windows
req.target-min-winverclnt: Available starting with Windows 8.
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
req.typenames: STOR_ADDR_BTL8, *PSTOR_ADDR_BTL8
f1_keywords:
 - _STOR_ADDR_BTL8
 - storport/_STOR_ADDR_BTL8
 - PSTOR_ADDR_BTL8
 - storport/PSTOR_ADDR_BTL8
 - STOR_ADDR_BTL8
 - storport/STOR_ADDR_BTL8
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Storport.h
api_name:
 - _STOR_ADDR_BTL8
 - PSTOR_ADDR_BTL8
 - STOR_ADDR_BTL8
---

# _STOR_ADDR_BTL8 structure (storport.h)


## -description

   The <b>STOR_ADDR_BTL8</b> address structure contains the addressing information for an 8-bit Bus-Target-LUN (BTL8) address.

## -struct-fields

### -field Type

The address type. This member is set to <b>STOR_ADDRESS_TYPE_BTL8</b>.

### -field Port

The host bus adapter (HBA) port number.

### -field AddressLength

The byte length of the address. This value is set to <b>STOR_ADDR_BTL8_ADDRESS_LENGTH</b>.

### -field Path

The bus number for the target device.

### -field Target

The target device number.

### -field Lun

The logical unit on the target device.

### -field Reserved

Reserved, set to 0.

## -see-also

<a href="/windows-hardware/drivers/ddi/scsi/ns-scsi-_stor_address">STOR_ADDRESS</a>

