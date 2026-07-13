---
title: "Geosearch - now with type filtering"
url: "https://blog.opencagedata.com/post/geosearch-with-type-filtering"
date: "2026-06-30"
feed_url: "https://blog.opencagedata.com/feed.xml"
---
Hi everyone, following on from our announcement last month of adding postcode to our geosearch / autosuggest widget , I am pleased to report another improvement: our geosearch / autosuggest widget now supports filtering by type of result. We have added a new field to the geosearch JSON response: _type , just like in our geocoding results, where we list the type of place the result is (for example: city or state or village ). In addition we now all you to set the field _type as a parameter to limit results only to certain types (you can specify either a single type or multiple as a comma separa
