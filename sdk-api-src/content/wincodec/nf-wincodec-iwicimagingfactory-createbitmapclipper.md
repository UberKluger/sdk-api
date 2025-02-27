---
UID: NF:wincodec.IWICImagingFactory.CreateBitmapClipper
title: IWICImagingFactory::CreateBitmapClipper (wincodec.h)
description: Creates a new instance of an IWICBitmapClipper object.
helpviewer_keywords: ["CreateBitmapClipper","CreateBitmapClipper method [Windows Imaging Component]","CreateBitmapClipper method [Windows Imaging Component]","IWICImagingFactory interface","IWICImagingFactory interface [Windows Imaging Component]","CreateBitmapClipper method","IWICImagingFactory.CreateBitmapClipper","IWICImagingFactory::CreateBitmapClipper","_wic_codec_iwicimagingfactory_createbitmapclipper","wic._wic_codec_iwicimagingfactory_createbitmapclipper","wincodec/IWICImagingFactory::CreateBitmapClipper"]
old-location: wic\_wic_codec_iwicimagingfactory_createbitmapclipper.htm
tech.root: wic
ms.assetid: 0764fee2-0767-41a4-a681-b831abb04119
ms.date: 12/05/2018
ms.keywords: CreateBitmapClipper, CreateBitmapClipper method [Windows Imaging Component], CreateBitmapClipper method [Windows Imaging Component],IWICImagingFactory interface, IWICImagingFactory interface [Windows Imaging Component],CreateBitmapClipper method, IWICImagingFactory.CreateBitmapClipper, IWICImagingFactory::CreateBitmapClipper, _wic_codec_iwicimagingfactory_createbitmapclipper, wic._wic_codec_iwicimagingfactory_createbitmapclipper, wincodec/IWICImagingFactory::CreateBitmapClipper
f1_keywords:
- wincodec/IWICImagingFactory.CreateBitmapClipper
dev_langs:
- c++
req.header: wincodec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Wincodec.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Windowscodecs.lib
req.dll: Windowscodecs.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windowscodecs.dll
api_name:
- IWICImagingFactory.CreateBitmapClipper
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWICImagingFactory::CreateBitmapClipper


## -description


Creates a new instance of an <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapclipper">IWICBitmapClipper</a> object.


## -parameters




### -param ppIBitmapClipper [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapclipper">IWICBitmapClipper</a>**</b>

A pointer that receives a pointer to a new <a href="https://docs.microsoft.com/windows/desktop/api/wincodec/nn-wincodec-iwicbitmapclipper">IWICBitmapClipper</a>.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



