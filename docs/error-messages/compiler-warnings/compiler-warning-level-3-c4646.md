---
title: "Compiler Warning (level 3) C4646 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C4646"]
dev_langs: ["C++"]
helpviewer_keywords: ["C4646"]
ms.assetid: 23677e8e-603e-40e0-b99a-2e4894a1278e
caps.latest.revision: 7
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Warning (level 3) C4646
function declared with __declspec(noreturn) has non-void return type  
  
 A function marked with the [noreturn](../../cpp/noreturn.md) `__declspec` modifier should have a [void](../../cpp/void-cpp.md) return type.  
  
 The following sample generates C4646:  
  
```  
// C4646.cpp  
// compile with: /W3 /WX  
int __declspec(noreturn) TestFunction()  
{   // C4646  make return type void  
}  
```