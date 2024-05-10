---
section: issue
title: Unexpected downtime on Midwest
date: 2024-05-10T11:24:00.746Z
resolved: true
resolvedWhen: 2024-05-10T20:36:07.256Z
affected:
  - Midwest Proxy
  - TTCloud
  - TTPages
  - API
  - TTVerify
  - AssistAI
severity: down
---
*2024-05-10 11:26:00 AM - We are aware that the Midwest site is currently experiencing downtime issues. Give us some time to figure out what's wrong.*

*2024-05-10 11:36:00 AM - We are suspecting the downtime may be linked to all of the resources being eaten up by a program of some sort. That is not confirmed at this time, but in order conserve traffic coming on site, any forwarded ports are now being cut off for the time being. We will get back to this as soon as we can.*

*2﻿024-05-10 16:32:00 PM - The problem has been found! Seems like our old status site that was running on the server was taking up almost all of the resources, including half of the memory and CPU. The fix was to stop the service running it, and the CPU went back down. This issue is now resolved, and services are now restored.*