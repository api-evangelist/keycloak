---
title: "Fine-Grained Admin Permissions for Organizations"
url: "https://www.keycloak.org/2026/05/org-fgap"
date: "2026-05-07"
author: "Vlasta Ramik"
feed_url: "https://www.keycloak.org/rss"
---
In Keycloak 26.7.0, Fine-Grained Admin Permissions (FGAP) will support Organizations as a resource type. This means you can grant an administrator permission to manage Org A while only allowing them to view Org B — or restrict their access to a single organization entirely. No more realm-wide all-or-nothing admin access for organizations. The Problem Before this release, administering organizations required the manage-realm role, which grants far broader access than just organizations — it covers realm settings, authentication flows, and much more.
