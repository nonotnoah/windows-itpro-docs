---
title: Configure Hybrid Windows Hello for Business Settings (Windows Hello for Business)
description: Learn how to configure Windows Hello for Business settings in hybrid certificate trust deployment.
keywords: identity, PIN, biometric, Hello, passport, WHFB, hybrid, certificate-trust
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security, mobile
audience: ITPro
author: GitPrakhar13
ms.author: prsriva
manager: dansimp
ms.collection: M365-identity-device-management
ms.topic: article
localizationpriority: medium
ms.date: 4/30/2021
ms.reviewer: 
---
# Configure Hybrid Azure AD joined Windows Hello for Business

**Applies to**

- Windows 10, version 1703 or later
- Windows 11
- Hybrid deployment
- Certificate trust

Your environment is federated and you are ready to configure your hybrid environment for Windows Hello for business using the certificate trust model.  
> [!IMPORTANT]
> If your environment is not federated, review the [New Installation baseline](hello-hybrid-cert-new-install.md) section of this deployment document to learn how to federate your environment for your Windows Hello for Business deployment.  

The configuration for Windows Hello for Business is grouped in four categories.  These categories are: 

- [Active Directory](hello-hybrid-cert-whfb-settings-ad.md)
- [Public Key Infrastructure](hello-hybrid-cert-whfb-settings-pki.md)
- [Active Directory Federation Services](hello-hybrid-cert-whfb-settings-adfs.md)
- [Group Policy](hello-hybrid-cert-whfb-settings-policy.md)

For the most efficient deployment, configure these technologies in order beginning with the Active Directory configuration

> [!div class="step-by-step"]
> [Configure Active Directory >](hello-hybrid-cert-whfb-settings-ad.md)

<br><br>

<hr>

## Follow the Windows Hello for Business hybrid certificate trust deployment guide
1. [Overview](hello-hybrid-cert-trust.md)
2. [Prerequisites](hello-hybrid-cert-trust-prereqs.md)
3. [New Installation Baseline](hello-hybrid-cert-new-install.md)
4. [Configure Azure Device Registration](hello-hybrid-cert-trust-devreg.md)
5. Configure Windows Hello for Business settings (*You are here*)
6. [Sign-in and Provision](hello-hybrid-cert-whfb-provision.md)
