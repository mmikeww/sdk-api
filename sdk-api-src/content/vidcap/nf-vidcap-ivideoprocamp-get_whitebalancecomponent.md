---
UID: NF:vidcap.IVideoProcAmp.get_WhiteBalanceComponent
title: IVideoProcAmp::get_WhiteBalanceComponent (vidcap.h)
description: The get_WhiteBalanceComponent method returns the camera's white balance, specified as red and blue component values.
old-location: dshow\ivideoprocamp_get_whitebalancecomponent.htm
tech.root: DirectShow
ms.assetid: b9beb89f-df55-4b76-a679-5e27cb0af9fb
ms.date: 12/05/2018
ms.keywords: IVideoProcAmp interface [DirectShow],get_WhiteBalanceComponent method, IVideoProcAmp.get_WhiteBalanceComponent, IVideoProcAmp::get_WhiteBalanceComponent, IVideoProcAmpget_WhiteBalanceComponent, dshow.ivideoprocamp_get_whitebalancecomponent, get_WhiteBalanceComponent, get_WhiteBalanceComponent method [DirectShow], get_WhiteBalanceComponent method [DirectShow],IVideoProcAmp interface, vidcap/IVideoProcAmp::get_WhiteBalanceComponent
ms.topic: method
f1_keywords:
- vidcap/IVideoProcAmp.get_WhiteBalanceComponent
dev_langs:
- c++
req.header: vidcap.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 R2 [desktop apps only]
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
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Vidcap.h
api_name:
- IVideoProcAmp.get_WhiteBalanceComponent
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IVideoProcAmp::get_WhiteBalanceComponent


## -description


The <code>get_WhiteBalanceComponent</code> method returns the camera's white balance, specified as red and blue component values.


## -parameters




### -param pValue1 [out]

Receives the red component.


### -param pValue2 [out]

Receives the blue component.


### -param pFlags [in, out]

Receives one or more flags. See <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/strmif/ne-strmif-videoprocampflags">VideoProcAmpFlags</a>.


## -returns



Returns an <b>HRESULT</b> value.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/vidcap/nn-vidcap-ivideoprocamp">IVideoProcAmp Interface</a>
 

 

