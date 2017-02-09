---
title: "SQLSetScrollOptions (Desktop Database Drivers) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: "sql-non-specified"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "drivers"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "SQLSetScrollOptions function [ODBC], Desktop Database Drivers"
ms.assetid: 51d643ed-015b-4639-969a-9491d9875aca
caps.latest.revision: 5
author: "MightyPen"
ms.author: "genemi"
manager: "jhubbard"
---
# SQLSetScrollOptions (Desktop Database Drivers)
Forward and static cursors are supported for SQL_CONCUR_READ_ONLY.  
  
 Only keyset-driven cursors are supported for an *fConcurrency* argument of SQL_CONCUR_LOCK.  
  
 An *fConcurrency* argument of SQL_CONCUR_ROWVER is not supported.  
  
 Dynamic cursors and mixed cursors are not supported.