Irritating conferences/events
-----------------------------------
- (\s|#)(ces|Ces|CES)
- (\s|#)(sxsw|Sxsw|SXSW)
- (\s|#)(crunchies|Crunchies|CRUNCHIES)

People re-tweeting things you didn't read last time they tweeted it
-------------
- (?i)(in.*case|if).*you.*missed.*it

Plaintive requests for follows
-------------
- (?i)please.*(\bwatch\b|\bfollow\b)|(\bwatch\b|\bfollow\b).*(me|please|back)

Tweets mentioning four or more other people
-------------
- @[^@]+@[^@]+@[^@]+@

Giant hashtags
-------------
- #[^ ]{15}

Four or more hashtags in single tweet
-------------
- #[^#]+#[^#]+#

Tweets to you containing only a link
--------------
- ^@pkedrosky *https?://[^ ]+$

Tweets containing over-repeated characters
-------------
- ([a-z])/1{4}

Retweet cascades
-------------
- RT[^RT]+RT
