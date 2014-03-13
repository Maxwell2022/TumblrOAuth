[![Total Downloads](https://poser.pugx.org/maxwell2022/tumblr-oauth/downloads.png)](https://packagist.org/packages/maxwell2022/tumblr-oauth)

This API is based on https://github.com/kertz/twitteroauth
I've forked to add composer support
Initial modification has been done by Lucas

TumblrOAuth
------------

PHP library for working with Tumblr's OAuth API.

Flow Overview
=============

1. Build TumblrOAuth object using client credentials.
2. Request temporary credentials from Tumblr.
3. Build authorize URL for Tumblr.
4. Redirect user to authorize URL.
5. User authorizes access and returns from Tumblr.
6. Rebuild TumblrOAuth object with client credentials and temporary credentials.
7. Get token credentials from Tumblr.
8. Rebuild TumblrOAuth object with client credentials and token credentials.
9. Query Tumblr API.
