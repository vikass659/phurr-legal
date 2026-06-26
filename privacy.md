---
title: Privacy Policy
permalink: /privacy/
---

# Phurr — Privacy Policy

**Last updated: 26 June 2026**

Phurr ("**Phurr**", "**we**", "**us**") is a peer‑to‑peer file‑sharing app
operated by **[LEGAL ENTITY / Vikas Ninawe]** ("the developer"). This policy
explains what we do — and mostly don't do — with your data.

## The short version

- **Your files are sent device‑to‑device**, over your local Wi‑Fi or Bluetooth.
  They **do not pass through our servers**. We never see, store, or scan them.
- Phurr works **fully as a guest** — no account, no internet, no tracking.
- The only data that ever leaves your device is what you **explicitly opt into**
  (turning on cloud sync, or signing in). Even then it's your **profile**, never
  your transfer activity.
- We don't sell your data, we don't use advertising/tracking identifiers, and we
  don't build a profile of your behaviour.

## 1. Data stored only on your device

The following stays on your device and is never sent to us:

- **Device identity** — a cryptographic key pair (Ed25519) generated on first
  launch and kept in the system secure store (iOS Keychain / Android Keystore).
  Its public "fingerprint" identifies your device to nearby peers.
- **Local profile** — the display name, photo, and optional bio you set.
- **Transfer history** — a local record of files you've sent/received.
- **Received files** — kept in the app's storage until you move or delete them.

Uninstalling the app removes this local data.

## 2. The content you transfer

Files are transferred **directly between devices** over the local network or
Bluetooth, secured in transit. We operate **no relay or cloud storage** for your
files and have **no access** to their contents, names, or recipients.

## 3. Optional cloud account & sync

If — and only if — you tap **"Turn on cloud sync"** or sign in, we create an
account for you on **Supabase** (our backend provider; data hosted in the
**Asia‑Pacific** region) and store:

- your **profile**: display name, optional bio, and (later) avatar image;
- a **device record**: your device fingerprint, platform (iOS/Android/macOS),
  and a label — used to recognise your devices and provide a basic user count.

We **do not** sync your transfer history, file contents, or recipients. You can
use sync **anonymously** (no email, no personal identifier) or by signing in.

## 4. Signing in (Google / Apple)

If you choose to sign in, the provider returns a unique account identifier and,
depending on the provider and your choices, your **name and email address**,
which we store to identify your account across devices. With **Apple** you may
use **Hide My Email** so we only ever see a relay address. Sign‑in is processed
through Supabase Auth using the provider's standard OAuth flow.

## 5. Device permissions and why we ask

- **Local network / Wi‑Fi, Bluetooth** — to discover nearby devices and transfer
  files. This is the core function.
- **Photos / Files** — only when you pick something to send, or choose a profile
  photo. We access only what you select.
- **Camera** — only to scan a QR code to start a transfer.
- **Notifications** (if enabled) — to alert you to incoming transfers.

We do **not** collect location, contacts, advertising identifiers, or microphone
data.

## 6. What we do NOT do

- No advertising or tracking SDKs, no IDFA/GAID, no cross‑app tracking.
- No selling or renting of personal data.
- No server‑side logging of who you send files to or what you send.

## 7. Service providers

- **Supabase** — authentication, database, and storage for the optional account
  (Asia‑Pacific region).
- **Apple / Google** — only if you sign in with them.

_Features we may introduce later will be **opt‑in** and this policy updated
before they collect anything: privacy‑respecting, anonymous, no‑PII usage
analytics; optional rewarded ads you choose to watch; and optional tips/purchases
processed by the Apple App Store / Google Play. We will not enable analytics or
ads without your consent._

## 8. Data retention & deletion

- **Local data** is removed when you uninstall the app.
- **Account data**: you can delete your account and all associated cloud data
  from within the app at any time (Profile → Account → Delete account), which
  removes your `profiles` and `devices` records and any stored avatar.

## 9. Your rights

Depending on where you live (e.g. India's DPDP Act, the EU/UK GDPR, CCPA), you
may have rights to access, correct, export, or delete your personal data, and to
withdraw consent. Because most data is local, you control it directly on your
device; for cloud‑account data, contact us or use in‑app deletion. We don't
discriminate against you for exercising these rights.

## 10. Children

Phurr is not directed to children under **[13 / the age required in your
jurisdiction]**, and we do not knowingly collect their personal data.

## 11. Security

Identity keys are stored in the platform secure enclave; transfers are encrypted
in transit; cloud rows are protected by per‑user access rules (row‑level
security). No system is perfectly secure, but we design to minimise the data
that exists in the first place.

## 12. Changes to this policy

We'll update the "Last updated" date above and, for material changes, notify you
in‑app. Continued use after an update means you accept the revised policy.

## 13. Contact

Questions or requests: **[privacy@phurr.app / your contact email]**
**[Legal entity name and address, if required in your jurisdiction]**
