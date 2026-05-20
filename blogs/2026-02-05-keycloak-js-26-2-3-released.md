---
title: "Keycloak JS 26.2.3 released"
url: "https://www.keycloak.org/2026/02/keycloak-js-2623-released"
date: "Thu, 5 Feb 2026 00:00:00 GMT"
author: ""
feed_url: "https://www.keycloak.org/rss"
---
Highlights This release of Keycloak JS addresses a regression that was introduced in version 26.2.2 affecting applications that use hash-based routing in combination with the fragment response mode. Bug Fixes URL hash fragments are now preserved correctly with 'fragment' response mode A regression was introduced in version 26.2.2 that caused URL fragments with path-style routing (e.g., #/admin/maintenance/scripts ) to be URL-encoded after the OAuth callback, breaking applications that use hash-based routing. This issue affected Angular, React, and other applications that rely on the hash…
