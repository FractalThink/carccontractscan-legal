---
title: Privacy Policy
permalink: /privacy
---

# Privacy Policy

**Effective date:** 2026-04-28
**App:** CarContractScan (the "App")
**Operator:** Fractalthink ("we," "us," "our")

This policy explains what information the App collects, how we use it, and who it is shared with. It covers the iOS and Android versions of CarContractScan.

We have written this in plain language. If anything is unclear, email us at `support@fractalthink.com`.

## What the App is for

CarContractScan lets you scan a dealership car-purchase contract with your phone's camera and get a plain-English summary, key dates, and risk flags before you sign. It is **not** legal advice — see the Terms of Service for the full disclaimer.

## Information we collect

The App is built so we collect as little as possible.

### Data you provide to us by using the App

- **Photos of contract pages** that you choose to scan. Photos are uploaded to our servers solely so they can be sent to a third-party language-model provider for analysis (see "Service providers" below). We do **not** retain the photos or the contract text after the analysis request finishes.
- **Anonymous user identifier.** When you first launch the App, RevenueCat (our purchase-management provider) generates an anonymous identifier for your install. We use it to track your purchase entitlement (e.g., how many scan credits you have). This identifier is not linked to your name, email, phone number, or Apple ID.
- **In-App Purchase information.** If you buy scan credits, Apple processes the payment. We receive purchase confirmation from Apple via RevenueCat (transaction ID, product purchased, amount). We do not receive your payment-method details.

### Data the App reads from your device

- **Camera access** — only when you tap the Scan button. The App does not access the camera in the background.
- **Photo library access** — only if you choose to import an existing photo of a contract. The App does not enumerate or read other photos.

### Data we collect automatically

When the App contacts our servers, our servers log:

- A randomly generated scan ID (per scan).
- Your anonymous user identifier.
- Page count, timing, and outcome of each scan request.
- Error codes when something goes wrong.
- An anti-abuse token from Firebase App Check that proves the request came from the App (not a script).
- Your IP address, used to enforce per-IP rate limits and to record security events such as a rate-limit being tripped. Your IP is not linked to your name, account, or any other identifier we hold, and it is retained only as long as the operational logs that contain it (see "Data retention" below).

We do **not** log the contents of your contracts, your device's advertising identifier, or any cross-app activity.

### Data stored on your device

Your acceptance of this Privacy Policy and the Terms of Service is recorded in a small file (`consent.json`) inside the App's private storage on your device. This file never leaves your device. We do not log or sync your consent server-side. If you uninstall the App, the file is removed with it.

## How we use information

We use the information described above only to:

- Run the analysis you requested and return the result.
- Manage your scan credits and purchases.
- Detect and prevent abuse (rate limits, bot detection, killswitch).
- Diagnose errors and improve App reliability.
- Comply with our legal obligations.

We do **not**:

- Sell your personal information.
- Share your information with advertisers.
- Use your contracts to train AI models. Our API agreement with Anthropic also prohibits Anthropic from using API inputs to train its models.
- Build a profile of you across other apps or websites.
- Show you advertising of any kind.

## Service providers

To run the App we share specific data with the following providers. Each is bound by their own privacy practices, linked below.

| Provider | What we send | Why | Their policy |
|---|---|---|---|
| **Anthropic** | Contract pages, scan ID, locale | To analyze the contract and generate the summary | https://www.anthropic.com/privacy |
| **RevenueCat** | Anonymous user ID, purchase events | To manage in-app purchases and entitlements | https://www.revenuecat.com/privacy |
| **Apple** | Standard App Store telemetry, IAP transactions | App distribution and payment processing | https://www.apple.com/legal/privacy/ |
| **Google (Firebase App Check)** | Anti-abuse attestation tokens | To prove requests come from the genuine App, not a script | https://firebase.google.com/support/privacy |
| **Cloudflare** | Standard request metadata | To deliver our backend API to your device | https://www.cloudflare.com/privacypolicy/ |

We host our backend on infrastructure we operate ourselves. We do not use third-party analytics SDKs (no Mixpanel, no Amplitude, no Sentry, no Crashlytics).

## Data retention

- **Contract photos and contract text:** not retained after the analysis request finishes (typically seconds). The third-party language-model provider's retention is governed by its own policy linked above.
- **Anonymous user identifier and purchase history:** retained as long as you have the App installed and tied to your purchase entitlements. Managed primarily by RevenueCat.
- **Server logs (scan IDs, timing, error codes, IP addresses):** retained for the period needed to operate the service, diagnose issues, and meet our legal obligations. We do not retain logs longer than necessary for those purposes.

## Your rights

Because the App does not collect identifying information, we cannot look up "your" data on request — we genuinely do not know which anonymous identifier is yours.

You can:

- **Stop using the App** at any time. Uninstalling removes the local consent record and all on-device data.
- **Reset your anonymous identifier** by uninstalling and reinstalling the App. This will also reset your purchase entitlement (any unconsumed credits you bought from Apple may be restorable via "Restore Purchases" in Settings; consumed credits are not refundable).
- **Contact us** at `support@fractalthink.com` with questions or concerns.

If you are a resident of California, the EU/UK, or another jurisdiction with specific privacy rights (right to know, right to delete, right to portability, etc.), we will honor reasonable requests to the extent we have the data. In most cases we will not — we deliberately do not retain it.

## Children's privacy

The App is not directed to children under 13 (or the equivalent minimum age in your country). We do not knowingly collect information from children. If you believe a child has used the App, contact us and we will investigate.

## Security

We use HTTPS for all network traffic between the App and our backend. Our backend is protected by Firebase App Check (so requests can be cryptographically verified as coming from the genuine App), rate limiting, and a remote killswitch in case of abuse. No system is perfectly secure, but we work to use reasonable safeguards proportionate to the (limited) data we collect.

## Changes to this policy

We may update this policy from time to time. The latest version is always available at `https://legal.fractalthink.com/privacy`.

When we make a substantive change — for example adding a new third-party service or expanding what we collect — we will bump the version constant in the App and you will be asked to re-accept this policy on next launch. Minor edits (typos, clarifications) will not trigger re-acceptance.

## Contact

Email: `support@fractalthink.com`  
Operator: Fractalthink

Postal address (registered agent):  
Northwest Registered Agent  
2501 Chatham Rd. Ste. N  
Springfield, IL 62704

---

*This policy is provided in plain language and is not a substitute for advice from an attorney licensed in your jurisdiction.*
