---
title: US East Downtime
date: 2023-12-11 05:20:00
resolved: true
resolvedWhen: 2023-12-12 07:46:00
affected:
    - East Proxy
    - TTGit
    - CDN
    - TTWeb
    - TTCloud
    - AssistAI
    - TTGuard
    - STVRadio
section: issue
severity: down
---

US East was recently under a network upgrade from Netrocorp, however a few issues arose from the cracks. A port configuration was lost for the server, and as a result, the server/sites on US East are unreachable at this time. If you need to access them, it may take time as all sites are returning a 502 error. Please review the summeray for more information


## Summary

Hosting log:

[December 10, 2023 9:54 PM] Maintenance in progress
We are conducting network migration. During this, access to your services may become inaccessible. Due to the new network mapping, this needs to happen. Netro Corporation engineers attempted to perform the maintenance without impact, however it has failed to fully implement safely to do such. We are hoping the downtime will be quick, within 30 minutes, but given the history of how things work around here, it may be a bit longer than that. We apologize for any inconvenience that will be caused, and we hope to get things done quickly.

[December 10, 2023 11:58 PM] Update
The internet connection has been restored to Netro Corporation, however we are still working on applying the new network map for users of NetroHost and to allow connections to US East. We apologize for the lack of updates.

[December 11, 2023 2:23 AM] Update
US East is now reporting Bad Gateway on all services. We continue to restore connections soon. Users using NetroHost may not be able to access their instances via SSH for some time. We apologize.

[December 11, 2023 4:55 AM] Resolved
The nature of this upgrade was mostly fine, however a lot of speed bumps were encountered. Unfortunately, due to a misconfiguration, we have lost the port allocation. Our audit log of ports was not completed and so incomplete that it’s not worth looking at. We messed up and let down our NetroHost Users. We apologize for the extreme inconvenience and we do hope issues like this are handled a lot better.  Otherwise, this incident has been resolved.

Our log:

[December 11, 2023 8:03 PM] Update
Server went out once more after some success on our container. This seams to be a firewall from both the management and main access to the servers hosting our services. For the time being, US East, along with the entire container hosting parts of it, will be shutdown. We are not sure on when this issue will be resolved. Untill then, US East will remain offline. We apologize for this insident.

[December 12, 2023 7:47 AM] Resolved
This issue is now resolved and services on US East is restored. We thank you for your patience during this outage.