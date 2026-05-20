---
title: "JWT Authorization Grant and Identity Chaining in Keycloak 26.5"
url: "https://www.keycloak.org/2026/01/jwt-authorization-grant"
date: "Fri, 23 Jan 2026 00:00:00 GMT"
author: "Giuseppe Graziano"
feed_url: "https://www.keycloak.org/rss"
---
Modern applications and AI agents increasingly operate across distributed trust domains, where each domain is protected by its own OAuth 2.0 Authorization Server. A single request may also traverse multiple resource servers to complete a task. This raises an important challenge: every protected resource must understand who initiated the request , which authorization was granted, and optionally which other resources were accessed before making an authorization decision.
