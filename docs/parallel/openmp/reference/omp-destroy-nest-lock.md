---
title: "omp_destroy_nest_lock | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["omp_destroy_nest_lock"]
dev_langs: ["C++"]
helpviewer_keywords: ["omp_destroy_nest_lock OpenMP function"]
ms.assetid: 0ab1352b-668f-43dd-b441-31ec4cc53e68
caps.latest.revision: 9
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# omp_destroy_nest_lock
Uninitializes a nestable lock.  
  
## Syntax  
  
```  
void omp_destroy_nest_lock(  
   omp_nest_lock_t *lock  
);  
```  
  
## Remarks  
 where,  
  
 `lock`  
 A variable of type [omp_nest_lock_t](../../../parallel/openmp/reference/omp-nest-lock-t.md) that was initialized with [omp_init_nest_lock](../../../parallel/openmp/reference/omp-init-nest-lock.md).  
  
## Remarks  
 For more information, see [3.2.2 omp_destroy_lock and omp_destroy_nest_lock Functions](../../../parallel/openmp/3-2-2-omp-destroy-lock-and-omp-destroy-nest-lock-functions.md).  
  
## Example  
 See [omp_init_nest_lock](../../../parallel/openmp/reference/omp-init-nest-lock.md) for an example of using `omp_destroy_nest_lock`.  
  
## See Also  
 [Functions](../../../parallel/openmp/reference/openmp-functions.md)