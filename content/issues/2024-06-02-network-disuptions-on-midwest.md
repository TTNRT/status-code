---
section: issue
title: Network disuptions on Midwest
date: 2024-06-02T12:55:09.450Z
resolved: false
draft: false
informational: false
pin: false
resolvedWhen: 2024-06-02T12:55:12.760Z
affected:
  - Midwest Proxy
  - TTCloud
  - API
  - TTVerify
severity: disrupted
---
*2024/06/01 21:28:00 - We are aware of a network disruption to the Midwest site that resulted of unexpected downtime to all services on site. We are unsure on the cause of the issue at this time. We will try to investigate the issue to identify what's wrong. We* apologize *for any inconvenience that resulted from this.*

*2024/06/02 8:55:00 - Our team has found nothing wrong or cause on why this downtime is occurring. While the cause is currently unknown, we have concluded that our Docker containers used for some of our services is the reason behind it all. To reproduce this issue, some of our services such as our CI interface and Feedback system will be moved to our US East server. Right now, some services are reachable via the Cloudflare tunnels system. The web server will be accessible later today depending on how the situation progresses.*