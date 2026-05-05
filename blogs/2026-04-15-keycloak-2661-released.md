---
title: "Keycloak 26.6.1 released"
url: "https://www.keycloak.org/2026/04/keycloak-2661-released"
date: "Wed, 15 Apr 2026 00:00:00 GMT"
author: ""
feed_url: "https://www.keycloak.org/rss.xml"
---
<p>To download the release go to <a href="https://www.keycloak.org/downloads.html">Keycloak downloads</a>.</p>


<h2>Upgrading</h2>
<p>Before upgrading refer to <a href="https://www.keycloak.org/docs/latest/upgrading/#migration-changes">the migration guide</a> for a complete list of changes.</p>

<h2>All resolved issues</h2>

<h3>Security fixes</h3>
<ul>
<li><a href="https://github.com/keycloak/keycloak/issues/47276">#47276</a> CVE-2026-4366 Blind Server-Side Request Forgery (SSRF) via HTTP Redirect Handling <code>core</code></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47619">#47619</a> CVE-2026-4633 Keycloak user enumeration via identity-first login <code>core</code></li>
</ul>




<h3>Enhancements</h3>
<ul>
<li><a href="https://github.com/keycloak/keycloak/issues/47839">#47839</a> Update CloudNativePG to 1.29 </li>
<li><a href="https://github.com/keycloak/keycloak/issues/47909">#47909</a> Database data at rest encryption </li>
</ul>

<h3>Bugs</h3>
<ul>
<li><a href="https://github.com/keycloak/keycloak/issues/47435">#47435</a> AuroraDB IT CI workflow not cleaning up databases <span class="badge bg-secondary">testsuite</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47737">#47737</a> deploy-testsuite profile is incomplete, causing discrete testsuite execution to fail <span class="badge bg-secondary">testsuite</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47776">#47776</a> False session type of access token in offline_access refresh token flow with scope parameter without offline_access scope <span class="badge bg-secondary">oidc</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47827">#47827</a> az vm create fails with JSON parsing error <span class="badge bg-secondary">ci</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47872">#47872</a> v26.6.0 Operator flood logs with warnings <span class="badge bg-secondary">operator</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47889">#47889</a> Not possible to sync latest keycloak-admin-client to keycloak-client <span class="badge bg-secondary">admin/client-java</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47904">#47904</a> @keycloak/keycloak-admin-client fails to install in version 26.6.0 <span class="badge bg-secondary">admin/client-js</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47905">#47905</a> invalid package reference in keycloak-admin-ui <span class="badge bg-secondary">admin/ui</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47908">#47908</a> MigrateTo26_6_0 modifies custom browser flows, breaking existing realm authentication <span class="badge bg-secondary">organizations</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47929">#47929</a> User profile multiselect options not highlighted as selected in dropdown <span class="badge bg-secondary">admin/ui</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/47955">#47955</a> IdentityProviderAuthenticator creates an infinite redirect loop when an IdP returns an error (e.g. access_denied) and the login was initiated with kc_idp_hint <span class="badge bg-secondary">identity-brokering</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/48015">#48015</a> Missing explicit docs anchor for organizations <span class="badge bg-secondary">docs</span></li>
<li><a href="https://github.com/keycloak/keycloak/issues/48032">#48032</a> Endpoint Response Text during Bootstrap contains Typo: Boostrap <span class="badge bg-secondary">dist/quarkus</span></li>
</ul>
