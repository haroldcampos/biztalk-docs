---
description: "Learn more about: Error - First Input to Table Extractor Functoid Not Valid"
title: "Error - First Input to Table Extractor Functoid Not Valid"
ms.custom: ""
ms.date: "06/08/2017"
ms.prod: "biztalk-server"
ms.reviewer: ""
ms.suite: ""
ms.topic: "article"
f1_keywords: 
  - "bts10.map.error.firstInputToTableExtractorNotValid"
---
# Error - First Input to Table Extractor Functoid Not Valid
**Error Code**  
  
 btm1019  
  
 **Explanation**  
  
 The first input parameter to the indicated **Table Extractor** functoid is not a link from a **Table Looping** functoid, as required.  
  
 **User Action**  
  
 Create a link between the indicated **Table Extractor** functoid and the appropriate **Table Looping** functoid by dragging one of them to the other. The former functoid must be located to the right of the latter functoid in a map grid page. Also, using the **Configure \<Functoid\> Functoid** dialog box, ensure that the newly created link is the first input parameter to the indicated **Table Extractor** functoid.
