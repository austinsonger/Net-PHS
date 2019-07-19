---toml
title = "Cloudflare - HTTP 502 errors"
date = "2019-07-02T13:52:00.000Z"
severity = "major-outage"
affectedsystems = ["site-delivery"]
resolved = true
---
Cloudflare has some network issues. Customers of cloudflare may be experiencing 502 errors while accessing sites that use Cloudflare.

<!-- Definition of the Incident Updates -->

::: update Monitoring | 2019-07-02T14:50:00.000Z
Description:
Major outage impacted all Cloudflare services globally. Cloudflare saw a massive spike in CPU that caused primary and secondary systems to fall over. Cloudflare shut down the process that was causing the CPU spike. Service restored to normal within ~30 minutes. Cloudflare is now investigating the root cause of what happened.
:::

::: update Resolved | 2019-07-02T14:57:00.000Z
Cloudflare has resolved the issue and services have resumed normal operation.
:::

<!--- language code: en -->
