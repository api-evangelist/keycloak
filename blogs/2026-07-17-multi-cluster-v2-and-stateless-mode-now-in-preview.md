---
title: "Multi-Cluster v2 and Stateless Mode now in Preview"
url: "https://www.keycloak.org/2026/07/multi-cluster-v2-and-stateless-mode"
date: "2026-07-17"
author: "Alexander Schwartz"
feed_url: "https://www.keycloak.org/rss"
---
Starting with Keycloak 26.7, the stateless feature is available as a preview. It fundamentally simplifies how Keycloak handles volatile data — authentication sessions, action tokens, and brute-force counters move from embedded or external Infinispan caches to the database. The result: Keycloak deployments that are easier to operate, more resilient, and ready for multi-cluster setups without an external Infinispan cluster.
