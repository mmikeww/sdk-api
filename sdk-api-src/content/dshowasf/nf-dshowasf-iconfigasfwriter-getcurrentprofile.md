---
UID: NF:dshowasf.IConfigAsfWriter.GetCurrentProfile
title: IConfigAsfWriter::GetCurrentProfile (dshowasf.h)
description: The GetCurrentProfile method retrieves the current ASF profile from the WM ASF Writer filter.
old-location: dshow\iconfigasfwriter_getcurrentprofile.htm
tech.root: DirectShow
ms.assetid: 1fa9fc3f-f8fd-42c9-9de2-22717cbb7e91
ms.date: 12/05/2018
ms.keywords: GetCurrentProfile, GetCurrentProfile method [DirectShow], GetCurrentProfile method [DirectShow],IConfigAsfWriter interface, IConfigAsfWriter interface [DirectShow],GetCurrentProfile method, IConfigAsfWriter.GetCurrentProfile, IConfigAsfWriter::GetCurrentProfile, IConfigAsfWriterGetCurrentProfile, dshow.iconfigasfwriter_getcurrentprofile, dshowasf/IConfigAsfWriter::GetCurrentProfile
ms.topic: method
f1_keywords:
- dshowasf/IConfigAsfWriter.GetCurrentProfile
dev_langs:
- c++
req.header: dshowasf.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
- Dshowasf.h
api_name:
- IConfigAsfWriter.GetCurrentProfile
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IConfigAsfWriter::GetCurrentProfile


## -description



The <code>GetCurrentProfile</code> method retrieves the current ASF profile from the <a href="https://docs.microsoft.com/windows/desktop/DirectShow/wm-asf-writer-filter">WM ASF Writer</a> filter.




## -parameters




### -param ppProfile [out]

Receives a pointer to the <a href="https://docs.microsoft.com/windows/desktop/wmformat/iwmprofile">IWMProfile</a> interface of the profile. The caller must release the interface.


## -returns



Returns S_OK if successful, or an <b>HRESULT</b> error code otherwise.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/creating-asf-files-in-directshow">Creating ASF Files in DirectShow</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/dshowasf/nn-dshowasf-iconfigasfwriter">IConfigAsfWriter Interface</a>
 

 

