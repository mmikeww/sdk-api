---
UID: NF:bdaiface.IBDA_NameValueService.GetValue
title: IBDA_NameValueService::GetValue (bdaiface.h)
description: Gets a value by name.
old-location: mstv\ibda_namevalueservice_getvalue.htm
tech.root: mstv
ms.assetid: d240f991-8f15-4d37-a292-91c7e3dff27d
ms.date: 12/05/2018
ms.keywords: GetValue, GetValue method [Microsoft TV Technologies], GetValue method [Microsoft TV Technologies],IBDA_NameValueService interface, IBDA_NameValueService interface [Microsoft TV Technologies],GetValue method, IBDA_NameValueService.GetValue, IBDA_NameValueService::GetValue, bdaiface/IBDA_NameValueService::GetValue, mstv.ibda_namevalueservice_getvalue
ms.topic: method
f1_keywords:
- bdaiface/IBDA_NameValueService.GetValue
dev_langs:
- c++
req.header: bdaiface.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Bdaiface.idl
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
- bdaiface.h
api_name:
- IBDA_NameValueService.GetValue
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IBDA_NameValueService::GetValue


## -description


Gets a value by name.


## -parameters




### -param bstrName [in]

The name of the value to retrieve.


### -param bstrLanguage [in]

The language for the value. If the value of the name/value pair is localizable, this string must contain an ISO 639-2 language code with a dash followed by an ISO 3166 country/region code. Otherwise, this parameter may contain an empty string.


### -param pbstrValue [out]

Receives the value as a <b>BSTR</b>. The caller must free the <b>BSTR</b> by calling <b>SysFreeString</b>.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/bdaiface/nn-bdaiface-ibda_namevalueservice">IBDA_NameValueService</a>
 

 

