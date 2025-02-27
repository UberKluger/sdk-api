---
UID: NF:rpcproxy.CStdStubBuffer_Connect
title: CStdStubBuffer_Connect function (rpcproxy.h)
description: The CStdStubBuffer_Connect function implements the IRpcStubBuffer::Connect method and connects the server object to the stub.
helpviewer_keywords: ["CStdStubBuffer_Connect","CStdStubBuffer_Connect function [RPC]","rpc.cstdstubbuffer_connect","rpcproxy/CStdStubBuffer_Connect"]
old-location: rpc\cstdstubbuffer_connect.htm
tech.root: Rpc
ms.assetid: 73aacc1f-b501-4e63-b69a-e64a85664f79
ms.date: 12/05/2018
ms.keywords: CStdStubBuffer_Connect, CStdStubBuffer_Connect function [RPC], rpc.cstdstubbuffer_connect, rpcproxy/CStdStubBuffer_Connect
f1_keywords:
- rpcproxy/CStdStubBuffer_Connect
dev_langs:
- c++
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: RpcRT4.lib
req.dll: RpcRT4.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- RpcRT4.dll
api_name:
- CStdStubBuffer_Connect
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# CStdStubBuffer_Connect function


## -description


<p class="CCE_Message">[CStdStubBuffer_Connect is not supported and may be altered or unavailable in the future.]

The <b>CStdStubBuffer_Connect</b> function implements the  <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-connect">IRpcStubBuffer::Connect</a> method and connects the server object to the stub.


## -parameters




### -param This [in]

Pointer to  the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-irpcstubbuffer">IRpcStubBuffer</a> object. 


### -param pUnkServer [in]

Pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface of the server object. 


## -returns



Returns S_OK if success. Returns E_NOINTERFACE on error.




## -remarks



This function is used internally by proxies that are generated by MIDL.



