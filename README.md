# Mastodon Bookmarklets
Bookmarklets for use browsing the Mastodon social network, including one for remote following

## Remote follow

The eventual intention is for this to be used for all follows, regardless of whether they are for the instance you are on, or not. Why? I can be browsing at instance foo.bar, where I have an account, but still want to use my bar.foo account to follow.

Right now, only other-instance-account(s) functionality is working.

Highlight the @who@foo.bar account identifier and click the bookmarklet.

TODO:

* make it clickable from profile page w/ out having to highlight anything
* ~~trim whitespace? double-click for highliting didn't work on profile page~~
* make it able to have hard-coded options for which accounts you have and prompt to use one (then it needs to populate the page)
* make it work for same-instance follow (w/ no instance name highlighted)
* MAKE IT USE https://mastodon.technology/authorize_follow?acct=arunsathiya%40mastodon.social (bookmarks dedicated to each account)
