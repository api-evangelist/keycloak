---
title: "Experimental Shared Signals Framework support in Keycloak"
url: "https://www.keycloak.org/2026/07/experimental-ssf-support"
date: "2026-07-03"
author: "Thomas Darimont"
feed_url: "https://www.keycloak.org/rss"
---
Keycloak now offers experimental support for the OpenID Shared Signals Framework 1.0, letting it act as a Shared Signals Transmitter that pushes signed Security Event Tokens about identity events to subscribed receivers. This closes a gap where revoking a session in Keycloak previously did not immediately sign users out of connected SaaS apps, and it also unlocks integration with Apple Business Manager for device state sync.
