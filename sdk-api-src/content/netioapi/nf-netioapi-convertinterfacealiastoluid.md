---
UID: NF:netioapi.ConvertInterfaceAliasToLuid
title: ConvertInterfaceAliasToLuid function (netioapi.h)
description: Converts an interface alias name for a network interface to the locally unique identifier (LUID) for the interface.
old-location: iphlp\convertinterfacealiastoluid.htm
tech.root: IpHlp
ms.assetid: 7fa80938-d475-4ace-b463-a53aac26e88b
ms.date: 12/05/2018
ms.keywords: ConvertInterfaceAliasToLuid, ConvertInterfaceAliasToLuid function [IP Helper], iphlp.convertinterfacealiastoluid, netioapi/ConvertInterfaceAliasToLuid
ms.topic: function
f1_keywords:
- netioapi/ConvertInterfaceAliasToLuid
dev_langs:
- c++
req.header: netioapi.h
req.include-header: Iphlpapi.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Iphlpapi.lib
req.dll: Iphlpapi.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Iphlpapi.dll
api_name:
- ConvertInterfaceAliasToLuid
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ConvertInterfaceAliasToLuid function


## -description


The 
<b>ConvertInterfaceAliasToLuid</b> function converts an interface alias name for a network interface to the locally unique identifier (LUID) for the interface.


## -parameters




### -param InterfaceAlias [in]

A pointer to a <b>NULL</b>-terminated Unicode string containing the alias name of the network interface.


### -param InterfaceLuid [out]

A pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/ifdef/ns-ifdef-net_luid_lh">NET_LUID</a> for this interface.


## -returns



On success, 
<b>ConvertInterfaceAliasToLuid</b> returns NO_ERROR. Any nonzero return value indicates failure and a <b>NULL</b> is returned in the <i>InterfaceLuid</i> parameter. 

<table>
<tr>
<th>Error code</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>ERROR_INVALID_PARAMETER</b></dt>
</dl>
</td>
<td width="60%">
One of the parameters was invalid. This error is returned if either the <i>InterfaceAlias</i> or <i>InterfaceLuid</i> parameter was <b>NULL</b> or if the <i>InterfaceAlias</i> parameter was invalid.

</td>
</tr>
</table>
 




## -remarks



The <b>ConvertInterfaceAliasToLuid</b> function is available on Windows Vistaand later.

The <b>ConvertInterfaceAliasToLuid</b> function is protocol independent and works with network interfaces for both the IPv6 and IPv4 protocol.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceguidtoluid">ConvertInterfaceGuidToLuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceindextoluid">ConvertInterfaceIndexToLuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtoalias">ConvertInterfaceLuidToAlias</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtoguid">ConvertInterfaceLuidToGuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtoindex">ConvertInterfaceLuidToIndex</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtonamea">ConvertInterfaceLuidToNameA</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtonamew">ConvertInterfaceLuidToNameW</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfacenametoluida">ConvertInterfaceNameToLuidA</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfacenametoluidw">ConvertInterfaceNameToLuidW</a>



<a href="https://docs.microsoft.com/windows/desktop/api/ifdef/ns-ifdef-net_luid_lh">NET_LUID</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-if_indextoname">if_indextoname</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-if_nametoindex">if_nametoindex</a>
 

 

