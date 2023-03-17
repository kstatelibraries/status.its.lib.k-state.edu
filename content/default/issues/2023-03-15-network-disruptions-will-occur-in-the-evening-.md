---
title: Network disruptions will occur in the evening on March 15th

draft: false

# Full date: 2019-03-29 17:26:09
date: 2023-03-15 18:00:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration: 12 hours minutes

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: maintenance

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: ok

# Full date: 2019-03-29 17:26:09
resolved_on: 2023-03-16 06:00:00

# Affected components, must use exact names defined in site config
affected:
  - Information Technology
  - K-State Libraries

# If set and the status is in_progress, this feed will be embedded
# in the event display. Leave empty for no Twitter feed.
# Possible URL formats:
# See:  https://help.twitter.com/en/using-twitter/embed-twitter-feed
#
# - Profile: Display public Tweets from any user on Twitter:
#    https://twitter.com/weeblrpress
#  
# - Likes: Show all Tweets a specific user has marked as likes.
#    https://twitter.com/TwitterDev/likes
#
# - List: Show Tweets from public Lists that you own and/or subscribe to.
#    https://twitter.com/TwitterDev/lists/national-parks
# 
# - Collection: Show Tweets from a curated collection.
#    https://twitter.com/TwitterDev/timelines/539487832448843776
#
# - Moment: Show Tweets from a public moment.
#    https://twitter.com/i/moments/625792726546558977
#
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
# {{< track "" >}}

## Enter below issue description and subsequent updates if any
---
{{< track "2023-03-15 09:02:00" >}} -- The Start Time has Changed to 6PM this evening.

The evening of March 15th Campus IT will be performing maintenance to the campus network starting at 6:00PM. Hale Library will have brief outages during the maintenance periord while intenret traffic is routed over the different pathways on campus.

> During the work, if basic functionality (Internet connectivity, routing, GlobalProtect, VPN, or building connectivity does not work, the issues will be worked on to try to find a resolution. If we run into unforeseen issues where this functionality is not performing correctly and doesn’t appear that it will be in a timely manner, we will reach a point where we roll back to the original hardware. If problems can be resolved quickly enough, we will reschedule for March 16th for the same 6:00pm to 6am March 17th.
