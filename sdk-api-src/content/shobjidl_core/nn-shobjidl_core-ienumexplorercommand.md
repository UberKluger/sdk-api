---
UID: NN:shobjidl_core.IEnumExplorerCommand
title: IEnumExplorerCommand (shobjidl_core.h)
description: Provided by an IExplorerCommandProvider. This interface contains the enumeration of commands to be put into the command bar.
helpviewer_keywords: ["IEnumExplorerCommand","IEnumExplorerCommand interface [Windows Shell]","IEnumExplorerCommand interface [Windows Shell]","described","_shell_IEnumExplorerCommand","shell.IEnumExplorerCommand","shobjidl_core/IEnumExplorerCommand"]
old-location: shell\IEnumExplorerCommand.htm
tech.root: shell
ms.assetid: c9a21e84-dd95-413a-b9db-e02008185bef
ms.date: 12/05/2018
ms.keywords: IEnumExplorerCommand, IEnumExplorerCommand interface [Windows Shell], IEnumExplorerCommand interface [Windows Shell],described, _shell_IEnumExplorerCommand, shell.IEnumExplorerCommand, shobjidl_core/IEnumExplorerCommand
f1_keywords:
- shobjidl_core/IEnumExplorerCommand
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
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
- shobjidl_core.h
api_name:
- IEnumExplorerCommand
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IEnumExplorerCommand interface


## -description


Provided by an <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-iexplorercommandprovider">IExplorerCommandProvider</a>. This interface contains the enumeration of commands to be put into the command bar.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IEnumExplorerCommand</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IEnumExplorerCommand</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IEnumExplorerCommand</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ienumexplorercommand-clone">Clone</a>
</td>
<td align="left" width="63%">
Not currently implemented.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ienumexplorercommand-next">Next</a>
</td>
<td align="left" width="63%">
Retrieves a specified number of elements that directly follow the current element.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ienumexplorercommand-reset">Reset</a>
</td>
<td align="left" width="63%">
Resets the enumeration to 0.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ienumexplorercommand-skip">Skip</a>
</td>
<td align="left" width="63%">
Not currently implemented.

</td>
</tr>
</table> 


## -remarks



None of the methods of this interface should talk to network resources. They are called on the UI thread; communicating with network resources would cause the UI to stop responding.



