---
UID: NF:comcat.IEnumGUID.Reset
title: IEnumGUID::Reset (comcat.h)
description: Resets the enumeration sequence to the beginning.
old-location: com\ienumguid_reset.htm
tech.root: com
ms.assetid: 5f31c45a-c7a2-4cdc-a468-76a31a9ba1e9
ms.date: 12/05/2018
ms.keywords: IEnumGUID interface [COM],Reset method, IEnumGUID.Reset, IEnumGUID::Reset, Reset, Reset method [COM], Reset method [COM],IEnumGUID interface, _com_ienumguid_reset, com.ienumguid_reset, comcat/IEnumGUID::Reset
ms.topic: method
f1_keywords:
- comcat/IEnumGUID.Reset
dev_langs:
- c++
req.header: comcat.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: ComCat.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- ComCat.h
api_name:
- IEnumGUID.Reset
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IEnumGUID::Reset


## -description


Resets the enumeration sequence to the beginning.


## -parameters






## -returns



The return value is S_OK.




## -remarks



There is no guarantee that the same set of objects will be enumerated after the reset operation has completed. A static collection is reset to the beginning, but it can be too expensive for some collections, such as files in a directory, to guarantee this condition.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/comcat/nn-comcat-ienumguid">IEnumGUID</a>
 

 

