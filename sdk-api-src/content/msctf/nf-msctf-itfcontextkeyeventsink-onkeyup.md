---
UID: NF:msctf.ITfContextKeyEventSink.OnKeyUp
title: ITfContextKeyEventSink::OnKeyUp (msctf.h)
description: ITfContextKeyEventSink::OnKeyUp method
old-location: tsf\itfcontextkeyeventsink_onkeyup.htm
tech.root: TSF
ms.assetid: ed0c6e14-d216-425c-a194-08e8ea85bb92
ms.date: 12/05/2018
ms.keywords: ITfContextKeyEventSink interface [Text Services Framework],OnKeyUp method, ITfContextKeyEventSink.OnKeyUp, ITfContextKeyEventSink::OnKeyUp, OnKeyUp, OnKeyUp method [Text Services Framework], OnKeyUp method [Text Services Framework],ITfContextKeyEventSink interface, _tsf_itfcontextkeyeventsink_onkeyup_ref, msctf/ITfContextKeyEventSink::OnKeyUp, tsf.itfcontextkeyeventsink_onkeyup
ms.topic: method
f1_keywords:
- msctf/ITfContextKeyEventSink.OnKeyUp
dev_langs:
- c++
req.header: msctf.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Msctf.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: Mscandui.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- mscandui.dll
api_name:
- ITfContextKeyEventSink.OnKeyUp
targetos: Windows
req.typenames: 
req.redist: TSF 1.0 on Windows 2000 Professional
ms.custom: 19H1
---

# ITfContextKeyEventSink::OnKeyUp


## -description




## -parameters




### -param wParam [in]

Specifies the virtual-key code of the key. For more information about this parameter, see the wPa<i></i>ram parameter in <a href="https://docs.microsoft.com/windows/desktop/inputdev/wm-keyup">WM_KEYUP</a>.


### -param lParam [in]

Specifies the repeat count, scan code, extended-key flag, context code, previous key-state flag, and transition-state flag of the key. For more information about this parameter, see the <i>lParam</i> parameter in <a href="https://docs.microsoft.com/windows/desktop/inputdev/wm-keyup">WM_KEYUP</a>.


### -param pfEaten [out]

Pointer to a BOOL value that, on exit, indicates if the key event is handled. If this value receives <b>TRUE</b>, the key event is handled. If this value receives <b>FALSE</b>, the key event is not handled.


## -returns



This method can return one of these values.

<table>
<tr>
<th>Value</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method was successful.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/msctf/nn-msctf-itfcontextkeyeventsink">ITfContextKeyEventSink</a>



<a href="https://docs.microsoft.com/windows/desktop/inputdev/wm-keyup">WM_KEYUP</a>
 

 

