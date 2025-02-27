---
UID: NF:rtworkq.RtwqCancelDeadline
title: RtwqCancelDeadline function (rtworkq.h)
description: Cancels a deadline that was previously set with RtwqSetDeadline.
old-location: base\rtwqcanceldeadline.htm
tech.root: ProcThread
ms.assetid: 4128B655-AFF9-4AEF-8EDB-A6DC8DA05FE9
ms.date: 12/05/2018
ms.keywords: RtwqCancelDeadline, RtwqCancelDeadline function, base.rtwqcanceldeadline, rtworkq/RtwqCancelDeadline
ms.topic: function
f1_keywords:
- rtworkq/RtwqCancelDeadline
dev_langs:
- c++
req.header: rtworkq.h
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
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- rtworkq.h
api_name:
- RtwqCancelDeadline
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RtwqCancelDeadline function


## -description


Cancels a deadline that was previously set with <a href="https://docs.microsoft.com/windows/desktop/api/rtworkq/nf-rtworkq-rtwqsetdeadline">RtwqSetDeadline</a>.


## -parameters




### -param pRequest [in]

Receives a handle to the request that can be used to cancel the request by calling <b>RtwqCancelDeadline</b>.


## -returns



If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/rtworkq/nf-rtworkq-rtwqsetdeadline">RtwqSetDeadline</a>
 

 

