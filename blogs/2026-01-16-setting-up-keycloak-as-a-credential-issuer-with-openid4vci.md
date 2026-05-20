---
title: "Setting Up Keycloak as a Credential Issuer with OpenID4VCI"
url: "https://www.keycloak.org/2026/01/issue-credentials-over-openid4vci"
date: "Fri, 16 Jan 2026 00:00:00 GMT"
author: "Rodrick Awambeng, Forkim Enjeckayang, Ingrid Kamga, Bertrand Ogen"
feed_url: "https://www.keycloak.org/rss"
---
Before configuring Keycloak, it is helpful to understand its role in decentralized identity ecosystems. As a verifiable credential issuer, Keycloak can issue digitally signed credentials using the OpenID for Verifiable Credential Issuance (OpenID4VCI) protocol, allowing relying parties (also known as verifiers) to independently verify them without contacting the issuer. Keycloak implements OpenID4VCI, enabling the issuance of verifiable credentials (VCs) as digital proofs of identity or attributes.
