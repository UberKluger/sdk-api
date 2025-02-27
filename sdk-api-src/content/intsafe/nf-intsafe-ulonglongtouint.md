---
UID: NF:intsafe.ULongLongToUInt
title: ULongLongToUInt function (intsafe.h)
description: Converts a value of type ULONGLONG to a value of type UINT.
helpviewer_keywords: ["ULongLongToUInt","ULongLongToUInt function [Windows Shell]","_shell_ULongLongToUInt","intsafe/ULongLongToUInt","shell.ULongLongToUInt"]
old-location: shell\ULongLongToUInt.htm
tech.root: shell
ms.assetid: 22ddab76-7f47-4198-830a-5ae88706ef1f
ms.date: 12/05/2018
ms.keywords: ULongLongToUInt, ULongLongToUInt function [Windows Shell], _shell_ULongLongToUInt, intsafe/ULongLongToUInt, shell.ULongLongToUInt
f1_keywords:
- intsafe/ULongLongToUInt
dev_langs:
- c++
req.header: intsafe.h
req.include-header: 
req.target-type: Windows
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
- Intsafe.h
api_name:
- ULongLongToUInt
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ULongLongToUInt function


## -description


Converts a value of type <b>ULONGLONG</b> to a value of type <b>UINT</b>.


## -parameters




### -param ullOperand [in]

Type: <b>ULONGLONG</b>

The value to be converted.


### -param puResult [out]

Type: <b>UINT*</b>

A pointer to the converted value. In the case where the conversion causes a truncation of the original value, the function returns INTSAFE_E_ARITHMETIC_OVERFLOW and this parameter is not valid.


## -returns



Type: <b>HRESULT</b>

If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



This is one of a set of inline functions designed to provide type conversions and perform validity checks with minimal impact on performance.



