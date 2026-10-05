# Awesome-Identity-Access-Management-IAM

## Top Identity & Access Management (IAM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Workforce & Customer Identity, SSO, MFA, Directory Services, Privileged Access, Identity Governance & Lifecycle Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity & Access Management (IAM)**. These systems handle authentication, authorization, single sign-on, multi-factor authentication, user lifecycle, privileged access, and identity governance across workforce and customer use cases.



**Examples** include Microsoft Entra ID (Azure AD), Okta, Ping Identity, CyberArk, ForgeRock, OneLogin, JumpCloud, SailPoint, Auth0, and IBM Security Verify (the category leaders).



**Open-source emphasis**: Enterprise IAM is dominated by commercial platforms. Strong open-source options—**Keycloak**, **Authentik**, **Ory**, **FreeIPA**, **Zitadel**, **Authelia**, and others—provide full-featured, self-hosted identity providers. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Microsoft Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  

  Microsoft’s cloud identity platform providing SSO, Conditional Access, MFA, identity protection, and deep integration with Microsoft 365 and Azure.



- **[Okta](https://www.okta.com/)**  

  Leading independent identity platform for workforce and customer identity with extensive app integrations, SSO, MFA, and lifecycle management.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise IAM and CIAM platform (including former ForgeRock capabilities) strong in hybrid federation, complex authentication, and customer identity.



- **[CyberArk](https://www.cyberark.com/)**  

  Security-first identity platform specializing in privileged access management (PAM), endpoint privilege, and identity security.



- **[ForgeRock](https://www.forgerock.com/)**  

  Now part of the broader Ping Identity portfolio; historically a flexible identity platform for complex workforce and customer scenarios.



- **[OneLogin](https://www.onelogin.com/)**  

  Cloud IAM solution focused on SSO, MFA, and directory integration for mid-market and enterprise customers.



- **[JumpCloud](https://jumpcloud.com/)**  

  Cloud directory and IAM platform popular with SMBs and mixed-OS environments, combining directory, SSO, and device management.



- **[SailPoint](https://www.sailpoint.com/)**  

  Leading identity governance and administration (IGA) platform for access certification, lifecycle, and compliance.



- **[Auth0](https://auth0.com/)**  

  Developer-centric identity platform (part of Okta) for authentication, authorization, and customer identity use cases.



- **[IBM Security Verify](https://www.ibm.com/products/verify-identity)**  

  IBM’s identity and access management suite covering workforce, privileged, and customer identity with strong governance features.



## Open-Source GitHub Projects

- **[Keycloak](https://github.com/keycloak/keycloak)**  

  The leading open-source identity and access management solution—supports OIDC, SAML, user federation, SSO, MFA, fine-grained authorization, and identity brokering.



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Modern, flexible open-source identity provider with a clean UI, extensive protocol support, and strong self-hosting experience.



- **[Ory](https://github.com/ory)**  

  Suite of open-source identity components (Kratos, Hydra, Oathkeeper, Keto) for authentication, OAuth2/OIDC, access control, and zero-trust architectures.



- **[FreeIPA](https://github.com/freeipa/freeipa)**  

  Open-source identity management system combining LDAP, Kerberos, DNS, and certificate services—ideal for Linux infrastructure identity.



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Cloud-native open-source identity and access management platform with multi-tenancy, modern APIs, and strong developer experience.



- **[Authelia](https://github.com/authelia/authelia)**  

  Open-source authentication and authorization server providing 2FA and SSO for reverse proxies and self-hosted applications.



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  Modern, simple open-source identity management focused on security and ease of administration for Unix and Linux environments.



- **[Gluu / Janssen Project](https://github.com/JanssenProject)**  

  Open-source identity platform (successor efforts to Gluu) supporting OIDC, SAML, SCIM, and FIDO2 for enterprise and compliance use cases.



- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  

  Open-source identity and access management server with strong API and federation capabilities.



- **[Documentation and Keycloak / Ory / Authentik playbooks](https://www.keycloak.org/docs)**  

  Guides for deploying production-grade open IAM, federation, and multi-factor setups.



### Additional Strong Open-Source Options

- Deploying **Keycloak** or **Authentik** as a full-featured identity provider for workforce or customer identity.

- Using **Ory** components for microservices-oriented or API-first identity architectures.

- Leveraging **FreeIPA** for infrastructure-level Linux identity and Kerberos.

- Accepting that large-scale enterprise governance, extensive SaaS integration catalogs, advanced privileged access, and managed global availability still favor commercial platforms (Entra ID, Okta, Ping, CyberArk, SailPoint, etc.).

- Focusing open-source efforts on data ownership, customization, and avoiding per-user licensing costs.



**Frameworks for building custom systems**: Stand up Keycloak or Authentik for SSO/MFA → federate with existing directories → protect APIs with Ory Oathkeeper or similar → apply fine-grained authorization. Suitable for organizations that need full control of identity data. Most large enterprises combine commercial IAM with selective open-source components.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity systems are critical security infrastructure. Open-source IAM requires proper hardening, monitoring, and operational expertise. This list is not security or compliance advice.



---

**Made for identity architects, security engineers, and open IAM advocates.**

Let's keep identity secure, controlled, and as open as practical.
