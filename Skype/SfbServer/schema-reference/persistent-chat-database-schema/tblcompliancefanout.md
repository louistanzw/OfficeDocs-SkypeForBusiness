---
title: "tblComplianceFanout"
ms.reviewer: 
ms.author: v-cichur
author: cichur
manager: serdars
ms.date: 3/9/2015
audience: ITPro
ms.topic: article
ms.prod: skype-for-business-itpro
f1.keywords:
- NOCSH
ms.localizationpriority: medium
ms.assetid: f5d9f342-a7cb-4b54-baa6-e656256b75ad
description: "tblComplianceFanout contains all servers that processed a compliance event."
---

# tblComplianceFanout
 
tblComplianceFanout contains all servers that processed a compliance event.
  
**Columns**

|**Column**|**Type**|**Description**|
|:-----|:-----|:-----|
|fanoutEventID  <br/> |int  <br/> |Event ID.  <br/> |
|fanoutServerID  <br/> |int  <br/> |Server identity (corresponding to tblServerIdentity.serverID table).  <br/> |
   
**Key**

|**Column**|**Description**|
|:-----|:-----|
|fanoutEventID  <br/> |Foreign key with lookup in tblComplianceData.cmplEventID table.  <br/> |
   

