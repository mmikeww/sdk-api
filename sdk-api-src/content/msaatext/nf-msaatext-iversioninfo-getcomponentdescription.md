---
UID: NF:msaatext.IVersionInfo.GetComponentDescription
title: IVersionInfo::GetComponentDescription (msaatext.h)
description: Clients call this method to retrieve a description of the component.
old-location: winauto\iversioninfo_iversioninfo__getcomponentdescription.htm
tech.root: WinAuto
ms.assetid: bb689adb-bd94-4c62-b408-33e1aa694c89
ms.date: 12/05/2018
ms.keywords: GetComponentDescription, GetComponentDescription method [Windows Accessibility], GetComponentDescription method [Windows Accessibility],IVersionInfo interface, IVersionInfo interface [Windows Accessibility],GetComponentDescription method, IVersionInfo.GetComponentDescription, IVersionInfo::GetComponentDescription, _msaa_IVersionInfo_GetComponentDescription, msaa.iversioninfo_iversioninfo__getcomponentdescription, msaatext/IVersionInfo::GetComponentDescription, winauto.iversioninfo_iversioninfo__getcomponentdescription
ms.topic: method
f1_keywords:
- msaatext/IVersionInfo.GetComponentDescription
dev_langs:
- c++
req.header: msaatext.h
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
req.dll: Msaatext.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- msaatext.dll
api_name:
- IVersionInfo.GetComponentDescription
targetos: Windows
req.typenames: 
req.redist: Active Accessibility 2.0 RDK on Windows NT 4.0 with SP6 and later and Windows 98
ms.custom: 19H1
---

# IVersionInfo::GetComponentDescription


## -description


Clients call this method to retrieve a description of the component.
		
<div class="alert"><b>Note</b>  Active Accessibility Text Services is deprecated. Please see     
<a href="https://go.microsoft.com/fwlink/p/?linkid=131573">Microsoft Windows Text Services Framework</a>for more information on advanced text input and natural language technologies.
		</div><div> </div>

## -parameters




### -param ulSub [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">ULONG</a></b>

The ordinal position of the component in the tree.


### -param pImplStr [out]

Type: <b>BSTR*</b>

String of the form of "Company, suite, component, version." This is for human consumption and is not expected to be 
			 parsed.


## -returns



Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HRESULT</a></b>

If successful, returns S_OK. If not successful, returns a standard <a href="https://docs.microsoft.com/windows/desktop/WinAuto/return-values">COM error code</a>.



