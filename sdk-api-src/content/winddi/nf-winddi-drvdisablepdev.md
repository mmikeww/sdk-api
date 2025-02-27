---
UID: NF:winddi.DrvDisablePDEV
title: DrvDisablePDEV function (winddi.h)
description: The DrvDisablePDEV function is used by GDI to notify a driver that the specified PDEV is no longer needed.
old-location: display\drvdisablepdev.htm
tech.root: display
ms.assetid: dff04000-e307-4a1c-80fe-d6666929df76
ms.date: 12/05/2018
ms.keywords: DrvDisablePDEV, DrvDisablePDEV function [Display Devices], ddifncs_ff781393-2fad-482c-a91e-1cf0b722441d.xml, display.drvdisablepdev, winddi/DrvDisablePDEV
ms.topic: function
f1_keywords:
- winddi/DrvDisablePDEV
dev_langs:
- c++
req.header: winddi.h
req.include-header: Winddi.h
req.target-type: Desktop
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
- winddi.h
api_name:
- DrvDisablePDEV
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# DrvDisablePDEV function


## -description


The <b>DrvDisablePDEV</b> function is used by GDI to notify a driver that the specified <a href="https://docs.microsoft.com/windows-hardware/drivers/">PDEV</a> is no longer needed.


## -parameters




### -param dhpdev

Handle to the <a href="https://docs.microsoft.com/windows-hardware/drivers/">PDEV</a> of the physical device to be disabled. This value is the handle returned by <a href="https://docs.microsoft.com/windows/desktop/api/winddi/nf-winddi-drvenablepdev">DrvEnablePDEV</a>.


## -returns



None




## -remarks



If the physical device has an enabled surface, GDI calls <b>DrvDisablePDEV</b> after calling <a href="https://docs.microsoft.com/windows/desktop/api/winddi/nf-winddi-drvdisablesurface">DrvDisableSurface</a>. The driver should free any memory and resources used by the PDEV.

<b>DrvDisablePDEV</b> is required for graphics drivers.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/winddi/nf-winddi-drvassertmode">DrvAssertMode</a>



<a href="https://docs.microsoft.com/windows/desktop/api/winddi/nf-winddi-drvdisablesurface">DrvDisableSurface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/winddi/nf-winddi-drvenablepdev">DrvEnablePDEV</a>
 

 

