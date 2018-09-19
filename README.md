# Mastodon Bookmarklets for Chrome
Bookmarklets for use with the Mastodon social network

## Smart follow

Follow an account you have highlighted on a page.

For people with **one account at one instance**: Highlight the text for a Mastodon account and click this to follow them. This is useful, for example, if you see someone post their account info on a blog or elsewhere outside of Mastodon.

For people with **multiple accounts**: Make your follow come from the correct instance. 

NOTE: This bookmarklet also attempts to locate an account without it being selected. Tested at a few instances, it will try to find an account when you are looking at its profile on Mastodon (in a column or in its own page).

Install instructions [here](https://sophware.github.io/mastodon-bookmarklets/)

TODO:

* [x] make it clickable from profile page or column w/ out having to highlight anything
* [x] make it clickable for short account IDs (like @one instead of @one@two.three) and when the initial @ is forgotton (foo@bar.com instead of @foo@bar.com) 
* [x] trim whitespace? double-click for highliting didn't work on profile page
* [x] MAKE IT USE https://mastodon.technology/authorize_follow?acct=foo@bar.social (bookmarks dedicated to each account)
