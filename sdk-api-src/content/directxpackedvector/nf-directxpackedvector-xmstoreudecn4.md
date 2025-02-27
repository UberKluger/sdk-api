---
UID: NF:directxpackedvector.XMStoreUDecN4
title: XMStoreUDecN4 function (directxpackedvector.h)
description: Stores an XMVECTOR in an XMUDECN4.
helpviewer_keywords: ["DirectX::PackedVector.XMStoreUDecN4","XMStoreUDecN4","XMStoreUDecN4 method [DirectX Math Support APIs]","dxmath.xmstoreudecn4"]
old-location: dxmath\xmstoreudecn4.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.storing.XMStoreUDecN4(XMUDECN4@,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: DirectX::PackedVector.XMStoreUDecN4, XMStoreUDecN4, XMStoreUDecN4 method [DirectX Math Support APIs], dxmath.xmstoreudecn4
f1_keywords:
- directxpackedvector/XMStoreUDecN4
dev_langs:
- c++
req.header: directxpackedvector.h
req.include-header: DirectXPackedVector.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: DirectX::PackedVector
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
- directxpackedvector.inl
api_name:
- XMStoreUDecN4
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMStoreUDecN4 function


## -description


Stores an <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvector-data-type">XMVECTOR</a> in an <a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/ns-directxpackedvector-xmudecn4">XMUDECN4</a>.


## -parameters




### -param pDestination [out]

Address at which to store the data.


### -param V [in]

Vector containing the data to store.


## -returns



None.




## -remarks



The following pseudocode demonstrates the operation of the function.


```
XMVECTOR N;	
static const XMVECTOR  Scale = {1023.0f, 1023.0f, 1023.0f, 3.0f};

assert(pDestination);

N = XMVectorClamp(V, XMVectorZero(), g_XMOne);
N = XMVectorMultiply(N, Scale);

pDestination->v = ((uint32_t)N.v[3] << 30) |
                  (((uint32_t)N.v[2] & 0x3FF) << 20) |
                  (((uint32_t)N.v[1] & 0x3FF) << 10) |
                  (((uint32_t)N.v[0] & 0x3FF));
```


<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-storage">DirectXMath Library Vector Store Functions</a>
 

 

