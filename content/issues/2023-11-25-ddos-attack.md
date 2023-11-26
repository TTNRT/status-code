---
title: DDOS Attack
date: 2023-11-25 13:23:00
resolved: true
resolvedWhen: 2023-11-25 23:31:00
affected:
  - Main Server
  - TTGit
  - CDN
  - TTHost
  - TTWeb
  - STVRadio
  - AssistAI
section: issue
severity: disrupted
---

Earlier today, US East has suffered a DDOS attack from the main server, hosted by NetroCorp. We are unsure on the problem at this time. However, to keep user bandwidth from spaming any further, our staff and administrators have made a decision to enable 'Under Attack Mode' withn our cloudflare account that uses our domain.

This is required when a ddos attack happens to any of our locations that host a service where posabile. Until the situition is resolved, the action will be taken.

## Update 1

We have sent the shutdown signal to our container. Please note that other sites are not affected, including our blog, status site, docs, and health site.

## Update 2

An update from NetroCorp:

> It seems the attack has calmed. We are working on resolving and implementing measures to prevent this from escalating like it did.

We are still looking into this issue, and will continue to update you on this DDOS attack.

## Update 3

There is still no update from NetroCorp as of 11 PM tonight. For this reason, we will be marking this issue as resolved untill an update is published. Also, to prevent other attacks to our container, we have set rules in Cloudflare to block the countrys responsabile. We will not disclose any information on the blocking, but based on data, it should block at least 3 targeted nations for any DDOS attacks. This is to ensure your safety, and also to prevent data loss on our servers.

It may take time for an update to publish, so please understand the actions taken, including our bot fight mode and other security settings in place.