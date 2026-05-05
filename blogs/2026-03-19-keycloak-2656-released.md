---
title: "Keycloak 26.5.6 released"
url: "https://www.keycloak.org/2026/03/keycloak-2656-released"
date: "Thu, 19 Mar 2026 00:00:00 GMT"
author: ""
feed_url: "https://www.keycloak.org/rss.xml"
---
<p>To download the release go to <a href="https://www.keycloak.org/downloads.html">Keycloak downloads</a>.</p>


<h2>Upgrading</h2>
<p>Before upgrading refer to <a href="https://www.keycloak.org/docs/latest/upgrading/#migration-changes">the migration guide</a> for a complete list of changes.</p>

<h2>All resolved issues</h2>

<h3>Security fixes</h3>
<ul>
<li><a href="https://github.com/keycloak/keycloak/issues/45645">#45645</a> CVE-2026-1180 - Blind Server-Side Request Forgery (SSRF) in Keycloak OIDC Dynamic Client Registration via jwks_uri <code>oidc</code></li>
<li><a href="https://github.com/keycloak/keycloak/issues/45647">#45647</a> CVE-2026-1035 - Keycloak Refresh Token Reuse Bypass via TOCTOU Race Condition <code>oidc</code></li>
<li><a href="https://github.com/keycloak/keycloak/issues/45650">#45650</a> CVE-2025-14777 - Keycloak IDOR in realm client creating/deleting </li>
<li><a href="https://github.com/keycloak/keycloak/issues/45653">#45653</a> CVE-2025-14082 keycloak-server: Keycloak Admin REST API: Improper Access Control leads to sensitive role metadata information disclosure </li>
<li><a href="https://github.com/keycloak/keycloak/issues/46719">#46719</a> CVE-2026-3121 - Keycloak: Privilege escalation via manage-clients permission </li>
<li><a href="https://github.com/keycloak/keycloak/issues/46723">#46723</a> CVE-2026-3190 - Information Disclosure via improper role enforcement in UMA 2.0 Protection API <code>core</code></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46922">#46922</a> CVE-2026-3911 Keycloak: Information disclosure of disabled user attributes via administrative endpoint <code>user-profile</code></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47062">#47062</a> CVE-2026-2366 Authorization Bypass: Unprivileged tokens can enumerate user organization memberships <code>organizations</code></li>
</ul>





<h3>Bugs</h3>
<ul>
<li><a href="https://github.com/keycloak/keycloak/issues/45889">#45889</a> Federated user disabled when external DB unavailable, never re-enabled <span class="badge bg-secondary">storage</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46239">#46239</a> AUTH_SESSION_ID cookie reuse causes cross-user session contamination on re-authentication <span class="badge bg-secondary">authentication</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46296">#46296</a> UsersResource.search briefRepresentation started to return user attributes <span class="badge bg-secondary">admin/api</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46379">#46379</a> Unexpected error when logging out with offline session and external IDP <span class="badge bg-secondary">oidc</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46459">#46459</a> Operator-built DB config: targetServerType=primary not applied / connection validation not working after master-replica failover (26.5.0) <span class="badge bg-secondary">operator</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46588">#46588</a> Partial LDAP sync duration does not follow the defined value in user federation <span class="badge bg-secondary">ldap</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46605">#46605</a> 26.5.4 startup regression with many realms: RealmCacheSession.prepareCachedRealm() scans master admin role composites per realm (O(N²)) <span class="badge bg-secondary">core</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46656">#46656</a> Em-Hyphens in SPI options on cache configuration page <span class="badge bg-secondary">docs</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46663">#46663</a>  JGroups bind port configuration ignored when --cache-embedded-network-bind-port set <span class="badge bg-secondary">infinispan</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/46669">#46669</a> SPIFFE Client assertion throws a NullPointerException if no client is found <span class="badge bg-secondary">token-exchange</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47079">#47079</a> Do not allow fetching organizations of a member if not a member of the current organization <span class="badge bg-secondary">organizations</span></li>
</ul>
