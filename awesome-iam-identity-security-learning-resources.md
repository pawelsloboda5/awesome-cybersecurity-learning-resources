# Awesome IAM & Identity Security Learning Resources

Identity and Access Management (IAM) has moved from "AD + LDAP" to a sprawling ecosystem of OAuth 2.0, OIDC, SAML 2.0, SCIM, FIDO2/WebAuthn/passkeys, mTLS, workload identity, and privileged access management (PAM). The Verizon DBIR consistently shows identity-based attacks dominating modern breaches, so this is now one of the most demanded specializations in security.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [IAM Tools & Platforms](#iam-tools--platforms)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [OAuth 2 in Action by Justin Richer, Antonio Sanso (Manning)](https://www.manning.com/books/oauth-2-in-action)
2. [API Security in Action by Neil Madden (Manning)](https://www.manning.com/books/api-security-in-action) - Best practical IAM + API book.
3. [Solving Identity Management in Modern Applications by Yvonne Wilson, Abhishek Hingnikar (Apress)](https://link.springer.com/book/10.1007/978-1-4842-5095-2)
4. [Advanced API Security: OAuth 2.0 and Beyond by Prabath Siriwardena](https://link.springer.com/book/10.1007/978-1-4842-2050-4)
5. [OpenID Connect in Action by Prabath Siriwardena (Manning)](https://www.manning.com/books/openid-connect-in-action)
6. [Keycloak - Identity and Access Management for Modern Applications by Stian Thorgersen, Pedro Igor Silva (Packt)](https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications/9781800562493)
7. [Identity Attack Vectors by Morey Haber, Darran Rolls (Apress)](https://link.springer.com/book/10.1007/978-1-4842-5165-2)
8. [Microsoft Azure AD / Entra ID books (John Savill's content, Microsoft Press series)](https://www.microsoftpressstore.com/)

## Videos
1. [Justin Richer / OAuth talks](https://www.youtube.com/results?search_query=justin+richer+oauth)
2. [OktaDev YouTube channel](https://www.youtube.com/@OktaDev)
3. [Identiverse / Gartner IAM Summit keynotes](https://identiverse.com/)
4. [Cloud Native Identity / OpenID Foundation webinars](https://openid.net/)
5. [Microsoft Identity Platform devs channel](https://www.youtube.com/@MicrosoftDeveloper)
6. [Dirk-jan Mollema talks on Entra ID attacks](https://dirkjanm.io/)
7. [Nestori Syynimaa (AADInternals) talks](https://aadinternals.com/)

## Free/Paid Courses
### Free
1. [OAuth 2.0 Simplified by Aaron Parecki (book + free online)](https://www.oauth.com/)
2. [Auth0 - Identity 101 guides (free)](https://auth0.com/docs/get-started)
3. [Okta Developer tutorials](https://developer.okta.com/docs/guides/)
4. [Microsoft Learn - Identity learning paths (free)](https://learn.microsoft.com/en-us/training/browse/?products=azure-active-directory)
5. [IAM explained by Alex Xu / ByteByteGo](https://blog.bytebytego.com/)
6. [Identity at the Center podcast](https://www.identityatthecenter.com/)
7. [FIDO Alliance developer resources](https://fidoalliance.org/developers/)
8. [webauthn.guide](https://webauthn.guide/)

### Paid
9. [Pluralsight - OAuth, OpenID Connect, SAML paths](https://www.pluralsight.com/search?q=oauth)
10. [SANS SEC530 (Identity-focused defense components)](https://www.sans.org/cyber-security-courses/defensible-security-architecture-and-engineering/)
11. [(ISC)2 CISSP / CIAM specialization materials](https://www.isc2.org/)
12. [Okta / Auth0 / Ping / Microsoft certification paths](https://www.okta.com/services/training/)
13. [CIAM-P (Certified IAM Professional)](https://certifications.identitymanagementinstitute.org/)

## Free/Paid Labs
1. [OAuth 2.0 Playground by Google](https://developers.google.com/oauthplayground/)
2. [OpenID Connect Playground by Auth0](https://openidconnect.net/)
3. [Keycloak Quickstart](https://www.keycloak.org/getting-started/getting-started-docker) - Self-host a full IAM server in minutes.
4. [Self-hosted Dex, Authelia, Authentik](https://www.authelia.com/)
5. [PortSwigger Web Security Academy - Authentication, OAuth, SSRF-in-OAuth labs](https://portswigger.net/web-security/authentication)
6. [BadZure + PurpleCloud + XMGoat](https://github.com/mvelazc0/BadZure) - Vulnerable Entra ID / Azure AD labs.
7. [Ping Identity / Okta developer sandboxes (free tier)](https://developer.okta.com/signup/)
8. [WebAuthn.io](https://webauthn.io/) - Try passkeys.
9. [Attack Defense identity / AD labs](https://attackdefense.com/)

## IAM Tools & Platforms
### IdP / SSO / Auth (SaaS)
1. [Okta](https://www.okta.com/) / [Auth0 (by Okta)](https://auth0.com/)
2. [Microsoft Entra ID (formerly Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)
3. [Ping Identity](https://www.pingidentity.com/)
4. [ForgeRock (now part of Ping)](https://www.forgerock.com/)
5. [Duo Security (by Cisco)](https://duo.com/)
6. [OneLogin (by One Identity)](https://www.onelogin.com/)
7. [JumpCloud](https://jumpcloud.com/)

### IdP / SSO (self-hosted / OSS)
8. [Keycloak by Red Hat](https://www.keycloak.org/)
9. [Authentik](https://goauthentik.io/)
10. [Authelia](https://www.authelia.com/)
11. [Zitadel](https://zitadel.com/)
12. [Ory Hydra / Kratos / Keto](https://www.ory.sh/)
13. [Gluu](https://www.gluu.org/)
14. [Dex](https://dexidp.io/) - OIDC with upstream connectors.

### Privileged Access Management (PAM)
15. [CyberArk](https://www.cyberark.com/) / [BeyondTrust](https://www.beyondtrust.com/) / [Delinea (Thycotic + Centrify)](https://delinea.com/)
16. [Teleport (SSH/Kubernetes/DB PAM, open-source core)](https://goteleport.com/)
17. [HashiCorp Boundary / Vault](https://www.vaultproject.io/)
18. [StrongDM](https://www.strongdm.com/)
19. [JIT / Netflix BLESS / Okta Advanced Server Access](https://github.com/Netflix/bless)

### Identity Governance / ITDR / CIEM
20. [SailPoint IdentityNow / IIQ](https://www.sailpoint.com/)
21. [Saviynt](https://saviynt.com/)
22. [Microsoft Entra ID Governance](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id-governance)
23. [Semperis Directory Services Protector / Purple Knight](https://www.semperis.com/)
24. [Silverfort](https://www.silverfort.com/)
25. [Permiso](https://permiso.io/) / [Clutch Security](https://clutch.security/) / [Oasis Security](https://oasis.security/) - Non-human identity (NHI) / secretsless.

### FIDO2 / Passkeys
26. [YubiKey (Yubico)](https://www.yubico.com/) / [SoloKeys](https://solokeys.com/)
27. [webauthn.io / WebAuthn testing tools](https://webauthn.io/)
28. [Apple / Google / Microsoft passkey implementations](https://www.passkeys.com/)

## Certifications
1. [Okta Certified Professional / Administrator / Consultant](https://www.okta.com/services/training/certification/)
2. [Microsoft SC-300 - Identity and Access Administrator Associate](https://learn.microsoft.com/en-us/certifications/identity-and-access-administrator/)
3. [Microsoft SC-100 - Cybersecurity Architect Expert (identity-heavy)](https://learn.microsoft.com/en-us/certifications/cybersecurity-architect-expert/)
4. [Ping Identity Certified Professional / Consultant](https://www.pingidentity.com/en/resources/training/certification.html)
5. [SailPoint IdentityNow / IIQ certifications](https://www.sailpoint.com/services/training/certification/)
6. [CyberArk Defender / Sentry / Guardian](https://www.cyberark.com/customer-support/training/)
7. [IAPP CIPP / CIPM / CIPT (privacy-focused, adjacent)](https://iapp.org/certify/)
8. [CIAM-P / CIMP by Identity Management Institute](https://certifications.identitymanagementinstitute.org/)
9. [(ISC)2 CISSP and CCSP - significant IAM domains](https://www.isc2.org/)

## Blogs/Articles
1. [Aaron Parecki blog](https://aaronparecki.com/) - OAuth standards author.
2. [Justin Richer blog](https://bspk.io/blog/)
3. [OAuth 2.0 official site and spec index](https://oauth.net/2/)
4. [OpenID Foundation specs and certified deployments](https://openid.net/developers/certified/)
5. [FIDO Alliance + passkeys.dev](https://passkeys.dev/)
6. [IETF OAuth Working Group drafts](https://datatracker.ietf.org/wg/oauth/documents/)
7. [RFC 6749 (OAuth 2.0), RFC 8628 (Device Flow), RFC 8705 (mTLS), RFC 9068 (JWT Access Tokens), RFC 8725 (JWT BCP), RFC 9449 (DPoP)](https://datatracker.ietf.org/)
8. [OAuth 2.1 draft](https://oauth.net/2.1/)
9. [NIST SP 800-63-4 (Digital Identity Guidelines, 2024 revision)](https://pages.nist.gov/800-63-4/)
10. [OWASP Authentication / Session / Access Control Cheat Sheets](https://cheatsheetseries.owasp.org/)
11. [Microsoft Identity blog](https://techcommunity.microsoft.com/category/microsoft-entra/blog)
12. [Auth0 blog](https://auth0.com/blog/)
13. [Okta Developer blog](https://developer.okta.com/blog/)
14. [Dirk-jan Mollema - dirkjanm.io (Entra ID research)](https://dirkjanm.io/)
15. [SpecterOps identity research](https://posts.specterops.io/)
16. [Identity Theft Resource Center breach reports](https://www.idtheftcenter.org/publications/)
17. [Awesome IAM GitHub](https://github.com/kdeldycke/awesome-iam)
18. [The Passkey Index by Mozilla](https://www.passkeyindex.com/)
