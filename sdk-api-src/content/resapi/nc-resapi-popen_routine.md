---
UID: NC:resapi.POPEN_ROUTINE
title: POPEN_ROUTINE (resapi.h)
description: Opens a resource.
old-location: mscs\open.htm
tech.root: MsCS
ms.assetid: 0a5c10c5-0380-4638-b49d-396be3b3c0dd
ms.date: 12/05/2018
ms.keywords: Open, Open callback, Open callback function [Failover Cluster], POPEN_ROUTINE, POPEN_ROUTINE callback function [Failover Cluster], _wolf_open, mscs.open, resapi/Open, resapi/POPEN_ROUTINE
ms.topic: callback
f1_keywords:
- resapi/Open
dev_langs:
- c++
req.header: resapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008 Enterprise, Windows Server 2008 Datacenter
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
- UserDefined
api_location:
- ResApi.h
api_name:
- Open
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# POPEN_ROUTINE callback function


## -description


Opens a 
    <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resources">resource</a>. The 
    <b>POPEN_ROUTINE</b> type defines a pointer to this function.


## -parameters




### -param ResourceName [in]

Name of the resource to open.


### -param ResourceKey [in]


<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/cluster-database">Cluster database</a> key for the 
       <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/c-gly">cluster</a> that includes the resource represented by 
       <i>ResourceName</i>.


### -param ResourceHandle [in]

Handle to be passed to the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pset_resource_status_routine">SetResourceStatus</a> 
       callback function in the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pstartup_routine">Startup</a> entry-point function.


## -returns



If the operation was successful, <i>Open</i> returns a resource 
       identifier (<b>RESID</b>).

If the operation was not successful, <i>Open</i> returns 
       <b>NULL</b>. Call  <a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-setlasterror">SetLastError</a> to 
       specify that an error has occurred.




## -remarks



The <i>Open</i> entry-point function opens a resource with the name 
     identified by the <i>ResourceName</i> parameter and returns its resource identifier. The 
     resource identifier can be used in future calls to other 
     <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resource-api">Resource API</a> entry points to identify the resource.

Never close the handle represented by the <i>ResourceHandle</i> parameter or use it for any 
     purpose other than passing it to the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resource-monitor">Resource Monitor</a> 
     through either the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-plog_event_routine">LogEvent</a> callback function or the 
     <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pset_resource_status_routine">SetResourceStatus</a> callback function.

For effective implementation strategies of the <i>Open</i> 
     entry-point function, see <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/implementing-open">Implementing Open</a>.


#### Examples

See <a href="https://docs.microsoft.com/previous-versions/aa372246(v=vs.85)">Resource DLL Examples</a>.

<div class="code"></div>



## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-plog_event_routine">LogEvent</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resource-dll-entry-point-functions">Resource DLL Entry-Point Functions</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pset_resource_status_routine">SetResourceStatus</a>
 

 

