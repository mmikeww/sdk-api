---
UID: NF:bdaiface.IBDA_DiseqCommand.put_DiseqUseToneBurst
title: IBDA_DiseqCommand::put_DiseqUseToneBurst (bdaiface.h)
description: Enables or disables Tone-Burst commands.
old-location: mstv\ibda_diseqcommand_put_disequsetoneburst.htm
tech.root: mstv
ms.assetid: 23523ac9-19e0-4247-a697-24d6f1c07285
ms.date: 12/05/2018
ms.keywords: IBDA_DiseqCommand interface [Microsoft TV Technologies],put_DiseqUseToneBurst method, IBDA_DiseqCommand.put_DiseqUseToneBurst, IBDA_DiseqCommand::put_DiseqUseToneBurst, bdaiface/IBDA_DiseqCommand::put_DiseqUseToneBurst, mstv.ibda_diseqcommand_put_disequsetoneburst, put_DiseqUseToneBurst, put_DiseqUseToneBurst method [Microsoft TV Technologies], put_DiseqUseToneBurst method [Microsoft TV Technologies],IBDA_DiseqCommand interface
ms.topic: method
f1_keywords:
- bdaiface/IBDA_DiseqCommand.put_DiseqUseToneBurst
dev_langs:
- c++
req.header: bdaiface.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
- IBDA_DiseqCommand.put_DiseqUseToneBurst
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IBDA_DiseqCommand::put_DiseqUseToneBurst


## -description


Enables or disables Tone-Burst commands.


## -parameters




### -param bUseToneBurst [in]

If <b>TRUE</b>, Tone-Burst commands are enabled. Otherwise, Tone-Burst commands are disabled.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



The Tone-Burst command uses a 22-kHz carrier signal to select either source position A or source position B. 

Typically the driver enables or disables Tone-Burst as needed when the application calls <a href="https://docs.microsoft.com/windows/desktop/api/bdaiface/nf-bdaiface-ibda_diseqcommand-put_diseqlnbsource">IBDA_DiseqCommand::put_DiseqLNBSource</a>. However, you can use  the <b>put_DiseqUseToneBurst</b> method to switch this mode on or off, either to improve channel switching or to maintain compatibility with particular equipment. Note that using Tone-Burst can increase  the amount of time required for tuning by about 40 milliseconds.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/bdaiface/nn-bdaiface-ibda_diseqcommand">IBDA_DiseqCommand</a>
 

 

