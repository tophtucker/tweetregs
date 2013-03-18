Tweetbot deeplink syntax
----------
- tweetbot:///mute/keyword?mentions=1&text=9to5mac
- http://tapbots.com/tweetbot/mute?url=tweetbot%3A%2F%2F%2Fmute%2Fkeyword%3Fregex%3D1%26text%3D%2528%253Fi%2529%2523%253Foscars%253F
Not sure what the functional difference is.

Favorites
---------
- @[^@]+@[^@]+@[^@]+@
- #[^ ]{15}
- #[^#]+#[^#]+#
- ^@tophtucker *https?://[^ ]+$
- ([a-z])/1{4}
- [Bb]ig\s?[Dd]ata
- (?i)(swag|yolo)

Conferences/events
-----------------------------------
- (?i)(\s|#)(ces)
- (?i)(\s|#)(sxsw)
- (?i)(\s|#)(crunchies)
- (?i)(#?\bted(\d{4})?\b|long beach)
- (?i)#?oscars?|award|nomination|speech|best picture|actor|actress|(S|s)eth ?(MacFarlane|McFarlane)|Fonda|Nicholson

People re-tweeting things you ignored the last time they tweeted it
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

Public conversations that have nothing to do with you
-------------
- ^\.@\w+\s+[A-Z]

Annoying people
-------------
- @?[Ll]ance\s?[Aa]rmstrong

Tech geekery
-------------
- [Ss]ocial\s?[Gg]raph
- [Gg]raph\s?[Ss]earch 
- [Bb]ig\s?[Dd]ata

Not so humble brags
- (?i)(swag|yolo)

Superbowl silliness
-------------
- (?i)(super ?bowls?|49ers|ravens|foot ?ball|half ?times?|kick ?off|touch ?downs?|field ?goals?|NFL|(first|second|third|fourth) quarters?|over ?times?|final scores)
