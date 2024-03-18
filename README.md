# Task

Analysis of people involvement in spreading ideas through the "success" (no) of "Noon Against Putin” protests.

## Data used

Turnout data collected by Roman Udot - https://twitter.com/romanik_/status/1769626338464284719

## Idea

We can (approximately) know amount of people seeing media mentioning this "Noon Against Putin” stuff.

So:
- if the amount of people here were lower than amount of readers/viewers/etc - than it failed. Means per one viewer of their media there will be less than one participant
- if the amount of people here are roughly similar to the amount of readers/viewers/etc - than it means there are no transfer of their ideas outside their echo chamber
- if the amount of people here are signgificantly more - than... okay

How will we get the amount of people taking part in this protests?

Well, we may use turnout-time data as an indicator. If people collected here after 12:00 17/03/2024 and casted their vote it means that turnout after 12:00 17/03/2024 must be bigger than it is expected.

But the problem is that we need some reference turnout to see how people will behave. Good thing it seems we can approximate turnout using linear regression of two features
- how much time passed since the (3 days) election start
- how much time passed since the beginning of this day

## Result

No noticeable proof of additional turnout.