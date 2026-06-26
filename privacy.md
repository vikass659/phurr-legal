---
title: Privacy Policy
permalink: /privacy/
---

# Phurr — Privacy Policy

**Last updated: 26 June 2026**

This Privacy Policy explains how the Phurr app ("**Phurr**", "**we**", "**us**")
handles information. Phurr is operated by **[LEGAL ENTITY / Vikas Ninawe]**
("the developer"), the **data controller** for any personal data described here.

## The short version

- **Your files are sent device‑to‑device**, over your local Wi‑Fi or Bluetooth.
  They **do not pass through our servers** — we never see, store, or scan them.
- Phurr works **fully as a guest** — no account, no internet, no tracking.
- Data leaves your device **only when you explicitly opt in** (turning on cloud
  sync, or signing in). Even then it's your **profile**, never your transfer
  activity.
- We don't sell your data, use advertising/tracking identifiers, or profile your
  behaviour.

## 1. Data stored only on your device

The following stays on your device and is never sent to us:

- **Device identity** — a cryptographic key pair (Ed25519) generated on first
  launch, kept in the system secure store (iOS Keychain / Android Keystore). Its
  public "fingerprint" identifies your device to nearby peers.
- **Local profile** — the display name, photo, and optional bio you set.
- **Transfer history** — a local record of files you've sent/received.
- **Received files** — kept in the app's storage until you move or delete them.

Uninstalling the app removes this local data.

## 2. The content you transfer

Files transfer **directly between devices** over the local network or Bluetooth,
secured in transit. We operate **no relay or cloud storage** for your files and
have **no access** to their contents, names, or recipients.

## 3. Optional cloud account & sync

If — and only if — you tap **"Turn on cloud sync"** or sign in, we create an
account for you on **Supabase** (our backend provider) and store:

- your **profile**: display name, optional bio, and (later) avatar image;
- a **device record**: device fingerprint, platform (iOS/Android/macOS), and a
  label — used to recognise your devices and provide a basic user count.

We **do not** sync your transfer history, file contents, or recipients. You can
use sync **anonymously** (no email, no personal identifier) or by signing in.

## 4. Signing in (Google / Apple)

If you choose to sign in, the provider returns a unique account identifier and,
depending on the provider and your choices, your **name and email address**,
which we store to identify your account across devices. With **Apple** you may
use **Hide My Email** so we only ever receive a relay address. Sign‑in uses
Supabase Auth via the provider's standard OAuth flow.

## 5. Legal bases for processing (GDPR/UK GDPR, where applicable)

- **Consent** — for creating a cloud account, signing in, and any future opt‑in
  analytics or ads. You may withdraw consent at any time (Section 9).
- **Performance of a contract / legitimate interests** — operating the core
  transfer features you ask for, and keeping the Service secure and functional.

## 6. International data transfers

Our backend (Supabase) currently hosts account data in the **Asia‑Pacific**
region. If you access Phurr from outside that region (e.g. the EU/UK), your
account data is transferred to and processed there. Where required, such
transfers rely on appropriate safeguards (e.g. Standard Contractual Clauses) and
data‑minimisation — we store as little as possible.

## 7. Device permissions and why we ask

- **Local network / Wi‑Fi, Bluetooth** — to discover nearby devices and transfer
  files (the core function).
- **Photos / Files** — only when you pick something to send, or choose a profile
  photo. We access only what you select.
- **Camera** — only to scan a QR code to start a transfer.
- **Notifications** (if enabled) — to alert you to incoming transfers.

We do **not** collect location, contacts, advertising identifiers, or microphone
data.

## 8. What we do NOT do

- No advertising or tracking SDKs, no IDFA/GAID, no cross‑app tracking.
- No selling or renting of personal data.
- No server‑side logging of who you send files to or what you send.

_Features we may add later will be **opt‑in**, and this policy updated before
they collect anything: privacy‑respecting, anonymous, no‑PII usage analytics;
optional rewarded ads you choose to watch; and optional tips/purchases processed
by the Apple App Store / Google Play. We will not enable analytics or ads
without your consent._

## 9. Your choices and rights

Depending on where you live (e.g. **India's DPDP Act 2023**, the EU/UK **GDPR**,
**CCPA/CPRA**), you may have rights to **access, correct, export, delete**, or
restrict your personal data, to **withdraw consent**, and to **lodge a complaint**
with your data‑protection authority. Because most data is local, you control it
directly on your device. For cloud‑account data:

- **Delete in‑app:** Profile → Account → Delete account removes your `profiles`
  and `devices` records and any stored avatar.
- **Or contact us** at the address in Section 13; we respond within the period
  required by applicable law.

We don't discriminate against you for exercising these rights.

## 10. Children

Phurr is a general‑audience utility and is **not directed to children**. In line
with India's DPDP Act, we treat individuals **under 18** as children: if you are
under 18 you may use Phurr only with the consent of a parent or guardian, and we
do not knowingly collect a child's personal data or use it for tracking,
behavioural monitoring, or targeted advertising. If you believe a child has
provided us personal data, contact us and we will delete it.

## 11. Data retention

Local data persists until you delete it or uninstall. Cloud‑account data is kept
while your account exists and deleted when you delete your account (or within a
reasonable period of an inactivity/closure request), except where we must retain
limited records to comply with law.

## 12. Security & breach notification

Identity keys are stored in the platform secure enclave; transfers are encrypted
in transit; cloud rows are protected by per‑user access rules (row‑level
security). No system is perfectly secure, but we minimise the data that exists in
the first place. If a personal‑data breach affecting you occurs, we will notify
you and the relevant authority as required by applicable law.

## 13. Changes & contact

We'll update the "Last updated" date and, for material changes, notify you
in‑app. Continued use after an update means you accept the revised policy.

**Grievance / privacy contact:** **[privacy@phurr.app / your contact email]**
**[Data controller legal name and address — required under GDPR and DPDP]**

_For India (DPDP Act): the above is your point of contact for grievances; we aim
to acknowledge and resolve requests within the timelines set by the Act._
