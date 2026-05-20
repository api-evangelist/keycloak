---
title: "Keycloak JS 26.2.4 released"
url: "https://www.keycloak.org/2026/04/keycloak-js-2624-released"
date: "Wed, 22 Apr 2026 00:00:00 GMT"
author: ""
feed_url: "https://www.keycloak.org/rss"
---
Highlights This release of Keycloak JS addresses two regressions in the Cordova adapter that were introduced in version 26.2.1 . Bug Fixes Cordova adapter no longer triggers duplicate authentication requests A regression introduced in version 26.2.1 caused the Cordova in-app browser to fire multiple loadstart events before the token exchange completed, resulting in concurrent authentication requests that could fail the login flow. The completed flag is now set before awaiting the token exchange, preventing duplicate processing of the redirect URI. keycloak/keycloak-js#208 Cordova in-app…
