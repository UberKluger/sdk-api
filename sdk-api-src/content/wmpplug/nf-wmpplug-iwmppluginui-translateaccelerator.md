---
UID: NF:wmpplug.IWMPPluginUI.TranslateAccelerator
title: IWMPPluginUI::TranslateAccelerator (wmpplug.h)
description: The TranslateAccelerator method is called as part of the Windows Media Player message loop to allow the plug-in to intercept and respond to keyboard events.
helpviewer_keywords: ["IWMPPluginUI interface [Windows Media Player]","TranslateAccelerator method","IWMPPluginUI.TranslateAccelerator","IWMPPluginUI::TranslateAccelerator","IWMPPluginUITranslateAccelerator","TranslateAccelerator","TranslateAccelerator method [Windows Media Player]","TranslateAccelerator method [Windows Media Player]","IWMPPluginUI interface","wmp.iwmppluginui_translateaccelerator","wmpplug/IWMPPluginUI::TranslateAccelerator"]
old-location: wmp\iwmppluginui_translateaccelerator.htm
tech.root: WMP
ms.assetid: 0accc3d7-a194-4f89-a90c-ee3ce10d0e27
ms.date: 12/05/2018
ms.keywords: IWMPPluginUI interface [Windows Media Player],TranslateAccelerator method, IWMPPluginUI.TranslateAccelerator, IWMPPluginUI::TranslateAccelerator, IWMPPluginUITranslateAccelerator, TranslateAccelerator, TranslateAccelerator method [Windows Media Player], TranslateAccelerator method [Windows Media Player],IWMPPluginUI interface, wmp.iwmppluginui_translateaccelerator, wmpplug/IWMPPluginUI::TranslateAccelerator
f1_keywords:
- wmpplug/IWMPPluginUI.TranslateAccelerator
dev_langs:
- c++
req.header: wmpplug.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Media Player 9 Series or later.
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
- COM
api_location:
- wmpplug.h
api_name:
- IWMPPluginUI.TranslateAccelerator
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMPPluginUI::TranslateAccelerator


## -description



The <b>TranslateAccelerator</b> method is called as part of the Windows Media Player message loop to allow the plug-in to intercept and respond to keyboard events.




## -parameters




### -param lpmsg [in]

<b>LPMSG</b> structure containing message information from Windows Media Player that the plug-in can respond to.


## -returns



This method returns an <b>HRESULT</b>.




## -remarks



The plug-in can set up an accelerator table to reroute specific keyboard events to appropriate handler methods. If the plug-in chooses not to respond to keyboard events, it should return <b>S_FALSE</b>.

<b>Windows Media Player 10 Mobile: </b>This method is not supported.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmpplug/nn-wmpplug-iwmppluginui">IWMPPluginUI Interface</a>
 

 

