---
title: "New release (v4.0.0) of our PHP SDK"
url: "https://blog.opencagedata.com/post/new-release-our-php-geocoding-sdk"
date: "2026-06-13"
author: ""
feed_url: "https://blog.opencagedata.com/feed.xml"
---
Good news for PHP developers using our geocoding API - version 4.0.0 of opencage/geocode has been released. The new version of the SDK brings with it some meaningful changes, hence why we bumped to v4.0.0. Specifically Minimum PHP is now 8.2 (was 8.0). Guzzle replaces the internal cURL/ fopen logic. The SDK now depends on guzzlehttp/guzzle ^7.0 , which Composer installs automatically. There is no longer a cURL/ fopen fallback and no need to fiddle with allow_url_fopen . Dedicated reverse...
