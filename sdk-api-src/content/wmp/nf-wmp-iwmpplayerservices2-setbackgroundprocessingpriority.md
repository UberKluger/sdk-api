---
UID: NF:wmp.IWMPPlayerServices2.setBackgroundProcessingPriority
title: IWMPPlayerServices2::setBackgroundProcessingPriority (wmp.h)
description: The setBackgroundProcessingPriority method specifies a priority level for general background processing tasks.
helpviewer_keywords: ["IWMPPlayerServices2 interface [Windows Media Player]","setBackgroundProcessingPriority method","IWMPPlayerServices2.setBackgroundProcessingPriority","IWMPPlayerServices2::setBackgroundProcessingPriority","IWMPPlayerServices2setBackgroundProcessingPriority","setBackgroundProcessingPriority","setBackgroundProcessingPriority method [Windows Media Player]","setBackgroundProcessingPriority method [Windows Media Player]","IWMPPlayerServices2 interface","wmp.iwmpplayerservices2_setbackgroundprocessingpriority","wmp/IWMPPlayerServices2::setBackgroundProcessingPriority"]
old-location: wmp\iwmpplayerservices2_setbackgroundprocessingpriority.htm
tech.root: WMP
ms.assetid: 1e3536d2-006b-4019-a9c5-c460135cf555
ms.date: 12/05/2018
ms.keywords: IWMPPlayerServices2 interface [Windows Media Player],setBackgroundProcessingPriority method, IWMPPlayerServices2.setBackgroundProcessingPriority, IWMPPlayerServices2::setBackgroundProcessingPriority, IWMPPlayerServices2setBackgroundProcessingPriority, setBackgroundProcessingPriority, setBackgroundProcessingPriority method [Windows Media Player], setBackgroundProcessingPriority method [Windows Media Player],IWMPPlayerServices2 interface, wmp.iwmpplayerservices2_setbackgroundprocessingpriority, wmp/IWMPPlayerServices2::setBackgroundProcessingPriority
f1_keywords:
- wmp/IWMPPlayerServices2.setBackgroundProcessingPriority
dev_langs:
- c++
req.header: wmp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Media Player 10 or later.
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
req.dll: Wmp.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- wmp.dll
api_name:
- IWMPPlayerServices2.setBackgroundProcessingPriority
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMPPlayerServices2::setBackgroundProcessingPriority


## -description



The <b>setBackgroundProcessingPriority</b> method specifies a priority level for general background processing tasks.




## -parameters




### -param bstrPriority [in]

<b>BSTR</b> containing one of the following values: "High", "Normal", "Off", or "Urgent".


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>S_OK</td>
<td>The method succeeded.</td>
</tr>
</table>
 




## -remarks



This method is used only when remoting the Windows Media Player control.

<b>Windows Media Player 10 Mobile: </b>This method is not supported.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmp/nn-wmp-iwmpplayerservices2">IWMPPlayerServices2 Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/WMP/remoting-the-windows-media-player-control">Remoting the Windows Media Player Control</a>
 

 

