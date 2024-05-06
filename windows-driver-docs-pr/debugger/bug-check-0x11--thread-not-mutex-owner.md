---
title: Bug Check 0x11 THREAD_NOT_MUTEX_OWNER
description: The THREAD_NOT_MUTEX_OWNER bug check has a value of 0x00000011.This bug check appears very infrequently.
keywords: ["Bug Check 0x11 THREAD_NOT_MUTEX_OWNER", "THREAD_NOT_MUTEX_OWNER"]
ms.date: 05/23/2017
topic_type:
- apiref
ms.topic: reference
api_name:
- THREAD_NOT_MUTEX_OWNER
api_type:
- NA
---

# Bug Check 0x11: THREAD\_NOT\_MUTEX\_OWNER


The THREAD\_NOT\_MUTEX\_OWNER bug check has a value of 0x00000011.

This rare bug check occurs when a thread tries to release a mutex it doesn't own. It likely signifies deeper inconsistencies within the system, such as issues in memory management or conflicts in the system's internal processes.

> [!IMPORTANT]
> This article is for programmers. If you're a customer who has received a blue screen error code while using your computer, see [Troubleshoot blue screen errors](https://www.windows.com/stopcode).


 

 




