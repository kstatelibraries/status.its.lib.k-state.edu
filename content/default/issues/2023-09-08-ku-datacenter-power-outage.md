---
title: KU Power Outage, impacting some Library services functionality

draft: false

# Full date: 2019-03-29 17:26:09
date: 2023-09-08 08:30:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration: 1 hours

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: down

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: down

# Full date: 2019-03-29 17:26:09
resolved_on: 2023-09-09 02:34:00

# Affected components, must use exact names defined in site config
affected:
  - Division of Information Technology
  - K-State Libraries
  - Redmine
  - K-REx

twitterFeed: 

# Enable Disqus commenting on this page. This will only works if 
# you added your Disqus identifier in the global config.yml file
# under the disqusShortname option.
# enabledDisqus: true | false
enableComments: false

## Do not change
section: issue

# Short code available in content to display current date
# in a short format. For instance for issue updates.

# {{< track "2019-03-26 15:31:06" >}}

## Enter below issue description and subsequent updates if any
---
{{< track "2023-09-09 02:34:00" >}} - All production resources are back up and running. If you notice issues that appear to be related to the services affected by the outage, please respond to this conversation and submit a [ticket](https://it.lib.k-state.edu/support.php).


{{< track "2023-09-08 08:30:00" >}}
From the Divsion of IT:
> KU has reported a power issue at one of the data centers we occupy in Lawrence. This is affecting a number of services. No estimate on when the issue will be resolved.
>
>
> PDIS,AD connect to sync to azure, Soiltest- Agronomy, Quickbooks, Rundeck, HCO SCCM, multiple SQL databases hosted via HCO servers, **WSUS updates**, Facilites ARC GIS/Esri, Grain Science Feedmill app, Data warehouse BI services, Paycheck Printing, **Deepfreeze**, **Papercut**, **Digital Signage**, Fusion, Lansweeper, on prem Informatica, Timeclock, DUO Proxy, KSRE apps (bookstore), Nacada services, KCCTO/Global campus applications, **APP Relay/SMTP**, Union applications, 25Live, Webmethods issues, ScheduleAll application, KMS, **Connect**, **Advisories**, **K-State Today email**

The current impact on Library systems is some of our systems are not able to send emails out. This includes our ticketing system. However, it is not affecting emails sent from Springshare Products, Alma, or ILLiad.

If you have any questions, please reach out on the [IT Channel](https://teams.microsoft.com/l/channel/19%3a7432bb8f1b4847e9a86de5ca76e89840%40thread.tacv2/IT%2520(Quick%2520Questions%2520and%2520Info)?groupId=7779c5fe-313c-4335-ae3e-615a6345ae93&tenantId=d9a2fa71-d67d-4cb6-b541-06ccaa8013fb)</a> in the K-State Libraries Team.
