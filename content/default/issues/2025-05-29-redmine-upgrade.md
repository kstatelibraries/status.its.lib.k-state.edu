---
title: Library Ticketing System Upgrade

draft: false

# Full date: 2019-03-29 17:26:09
date: 2025-05-29 09:30:00

# Status: "resolved" | "in_progress" | "scheduled"
status: "resolved"

# This message will be taken out of the flow of events
# and displayed at top of page or below the header
# as long as its status is marked as in_progress
# pinned: (empty) | top | belowheader
pinned: 

# Duration for "scheduled" issues: Raw text, ie 5mn, 1h, 1 hour,..
duration: 15 minutes

# Max severity: will be displayed when issue is resolved, in the past events section
# Max_severity: ok | disrupted | down | monitoring | maintenance
max_severity: maintenance

# Current severity: used for current issue display
# current_severity: ok | disrupted | down | monitoring | maintenance
current_severity: disrupted

# Full date: 2019-03-29 17:26:09
resolved_on: 2025-05-29 09:35:00

# Affected components, must use exact names defined in site config
affected:
  - Redmine

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
{{< track "2025-05-29 09:35:00" >}}
Upgrade Completed

We will be performing an upgrade of our Ticketing system at 9:30AM this morning. Less than 15 minutes of service interuption is expected.
