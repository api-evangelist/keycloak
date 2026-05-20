---
title: "Federated client authentication - no more secrets"
url: "https://www.keycloak.org/2026/01/federated-client-authentication"
date: "Mon, 26 Jan 2026 00:00:00 GMT"
author: "Stian Thorgersen"
feed_url: "https://www.keycloak.org/rss"
---
Keycloak has from day one supported identity brokering, allowing users to authenticate via an external OpenID Connect or SAML 2.0 identity provider. With federated client authentication it is now possible to authenticate OpenID Connect clients through external identity providers as well. Depending on the environment the clients is running in this can eliminate the need for managing secrets for clients altogether.
