---
title: US Midwest migration
date: 2024-02-29T09:13:00.746Z
resolved: false
#resolvedWhen: 2024-03-03T13:30:00.746Z
affected:
    - Midwest Proxy
    - TTCloud
    - TTPages
    - API
section: issue
severity: down
---

We are planning on doing a quick migration of the current US Midwest server to a different server with smaller specs for our services. In addition to these changes, we are also planning on migrating our Mastodon site to US East due to the storage amount it takes. TTCloud is not affected by this. Please note that Mastodon may take time to work or even work while the migration is in progress. TTPages may be moved as well. The API is not effected. This migration for the server will start 6:30 PM tonight, and the stated services effective for moving to US East will be moved on Friday at the least. You should keep in mind of any outages this may cause during this time.

## Summary
2024-02-29 4:20 PM - Seams like the Mastodon migration went well as expected. We did it a bit early then we planned. This service will be off the list as the service is responding to requests and the streaming is online. If you see any issues, please email us.

2024-03-01 6:01 PM - The migration has begon. Any services hosted on US Midwest will become inaccessible. Updates will published while the migration is in progress.

2024-03-01 10:57 PM - The migration was successful. Before hosting the new server, we will test to ensure that everything went well.

2024-03-02 1:55 PM - There seams to be issues reguarding the server. Around the time the migration was finished, we made sure that everything was going well for the server. However, the server showed no output to the screen we used to check for any issues. The boot text did show before this. The CEO at the time of the migration was complety unaware on the progress, so we can't tell if there were any errors during the timing of it. For now, some services will be operated on US East for time being until service is restored on US Midwest.

2024-03-03 12:39 AM - We managed to install a clean copy of Debian to the new server and put in the backups from the old server. Since the server works well without any errors, we are going to power on the server later today as the midnight hours is effecting the CEO at the momment. This issue will be closed at 1:30 PM as the migration is complete.
