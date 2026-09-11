---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for Nautora

**Last updated: August 3, 2026**

Nautora ("the app") is a mobile client for [Portainer](https://www.portainer.io/) that lets you manage your own
Docker and Kubernetes environments from your phone. This policy explains how the app handles your information.

## The short version

**Nautora does not collect your data.** There is no analytics, no tracking, no advertising, and no user account.
The developer operates **no servers** and receives **no personal information** from the app.

## Data stored on your device

To function, the app stores the following **locally on your device only**:

- **Connection settings** for the Portainer instances you add — server URL, a display name, and the TLS certificate
  fingerprint used for security — in the app's local database.
- **API keys / credentials** you enter, stored in the operating system's secure storage (Apple **Keychain** on iOS,
  Android **Keystore**), encrypted by the OS.

This information never leaves your device except to communicate **directly** with the Portainer server(s) **you**
configure. It is not sent to the developer or to any third party.

## Network connections

The app connects **only** to the Portainer instances you add, using the address and credentials you provide. There is
no intermediary server — your device talks straight to your server. The developer cannot see this traffic or its contents.

## Purchases

Nautora offers a one-time "Pro" unlock. Payments are processed entirely by the **Apple App Store** or **Google Play**
under their own terms. Nautora does **not** receive or store your payment details. Apple and Google may provide the
developer with aggregated, non-identifying sales information as described in their respective policies.

## Diagnostics and logs

Any error logs, container logs, or pod logs shown in the app are retrieved from **your** servers and kept **on your
device**. Nothing is uploaded automatically. If you choose to report a problem (for example, on GitHub), only the
information **you** paste into the report is shared — please remove any server addresses, API keys, or other secrets first.

## Third parties

Nautora integrates **no** third-party analytics, advertising, or tracking SDKs. The only third parties involved are
Apple and Google, solely for app distribution and purchase processing.

## Children's privacy

Nautora is a developer tool and is not directed at children. It collects no personal data from anyone.

## Changes to this policy

We may update this policy; the "Last updated" date above will change accordingly. Material changes will be noted in the
app's release notes or in this repository.

## Contact

Questions or privacy requests: open an issue at [https://github.com/nautora/nautora.github.io/issues](https://github.com/nautora/nautora.github.io/issues).

---

<sub>Nautora is an independent application and is not affiliated with, endorsed by, or sponsored by Portainer.io Limited.
"Portainer" is a trademark of its respective owner and is used here only to describe compatibility. "Docker" and
"Kubernetes" are trademarks of their respective owners.</sub>
