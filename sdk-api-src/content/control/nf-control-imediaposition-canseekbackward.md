---
UID: NF:control.IMediaPosition.CanSeekBackward
title: IMediaPosition::CanSeekBackward (control.h)
description: The CanSeekBackward method determines whether the filter graph can seek backward in the stream.
helpviewer_keywords: ["CanSeekBackward","CanSeekBackward method [DirectShow]","CanSeekBackward method [DirectShow]","IMediaPosition interface","IMediaPosition interface [DirectShow]","CanSeekBackward method","IMediaPosition.CanSeekBackward","IMediaPosition::CanSeekBackward","IMediaPositionCanSeekBackward","control/IMediaPosition::CanSeekBackward","dshow.imediaposition_canseekbackward"]
old-location: dshow\imediaposition_canseekbackward.htm
tech.root: dshow
ms.assetid: 8152553a-173b-4f0b-bcdf-b9c20912921d
ms.date: 12/05/2018
ms.keywords: CanSeekBackward, CanSeekBackward method [DirectShow], CanSeekBackward method [DirectShow],IMediaPosition interface, IMediaPosition interface [DirectShow],CanSeekBackward method, IMediaPosition.CanSeekBackward, IMediaPosition::CanSeekBackward, IMediaPositionCanSeekBackward, control/IMediaPosition::CanSeekBackward, dshow.imediaposition_canseekbackward
f1_keywords:
- control/IMediaPosition.CanSeekBackward
dev_langs:
- c++
req.header: control.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IMediaPosition.CanSeekBackward
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMediaPosition::CanSeekBackward


## -description



The <code>CanSeekBackward</code> method determines whether the filter graph can seek backward in the stream.




## -parameters




### -param pCanSeekBackward [out]

Pointer to a variable that receives the value OATRUE if the graph can seek backward, or OAFALSE otherwise.


## -returns



Returns an <b>HRESULT</b> value. Possible values include the following.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_NOTIMPL</b></dt>
</dl>
</td>
<td width="60%">
Not implemented.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
<b>NULL</b> pointer argument.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/control/nn-control-imediaposition">IMediaPosition Interface</a>
 

 

