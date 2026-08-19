<div align="center">

# ◉ Hansel

### Sovereign Communication — Your Email. Your Server. Your Keys.

[![Platform](https://img.shields.io/badge/platform-Windows-blue)](https://hansel.wicked-crumbs.com)
[![Built With Flutter](https://img.shields.io/badge/built%20with-Flutter-02569B)](https://flutter.dev)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)](https://wicked-crumbs.com)

**Hansel** is a sovereign, end-to-end encrypted communication platform
built for teams and individuals who refuse to let a corporation own
their communications. Your email runs on your infrastructure. Your
messages are encrypted on your device. No company can flip a switch
and lock you out.

[Why Hansel](#why-hansel) · [Features](#features) · [The Wicked Crumbs Protocol](#the-wicked-crumbs-protocol) · [Pricing](#pricing) · [Download](#download) · [Philosophy](#the-philosophy)

---

*Built by Kemone Phillips & Bob (AI Engineering Partner) — [Seedling.io](https://seedlingio.com)*

</div>

---

## Why Hansel?

Google cancelled a Workspace subscription and locked the account owner
out of their own email, contacts, and documents — instantly, without
recourse. No warning. No grace period. No appeal that mattered.

That moment built Hansel.

Every other communication platform makes the same silent promise:
*"We'll hold your data, and we'll be reasonable about it."*
Hansel makes a different promise entirely:

**We can't lock you out. We can't read your data.
We can't cancel your account. Because none of it lives with us.**

| Feature | Hansel | Google Workspace | Microsoft 365 | ProtonMail |
|---------|--------|-----------------|---------------|------------|
| You own the mail server | ✅ | ❌ | ❌ | ❌ |
| End-to-end encrypted by default | ✅ | ❌ | ❌ | ✅ |
| Platform cannot read your messages | ✅ | ❌ | ❌ | ✅ |
| Spam solved architecturally | ✅ | ❌ | ❌ | ❌ |
| Custom domain email | ✅ | ✅ | ✅ | ✅ |
| Encrypted team messaging | ✅ | ❌ | ❌ | ❌ |
| Enterprise admin console | ✅ | ✅ | ✅ | ❌ |
| DLP + eDiscovery built in | ✅ | ✅ (add-on) | ✅ (add-on) | ❌ |
| No account suspension possible | ✅ | ❌ | ❌ | ❌ |
| Keys stay on your device | ✅ | ❌ | ❌ | Partial |

---


**Requirements:**
- Windows 10 or later
- An internet connection for email and messaging sync
- A Hansel account (free to create)

> macOS, iOS, and Android clients coming soon.

---

## Features

### 🔐 Wicked Crumbs Protocol
A proprietary cryptographic messaging protocol designed from first
principles. Every message is encrypted on your device before it
leaves. The platform mathematically cannot read your messages —
not by policy, but by design.

- RSA-4096 key pair generation with OS entropy
- Rotating identity system — your address changes automatically
- Tamper-evident message chain preventing forgery and replay attacks
- QR code key exchange for in-person cryptographic verification
- Spam solved architecturally — without your key, no one can reach you

### 📧 Sovereign Email
Send and receive email from your own domain using infrastructure
you own. Your mail server. Your signing keys. Your DNS records.

- Send from your own domain (kemone@yourdomain.com)
- Recipients get a normal email — no apps required on their end
- Multi-domain support
- Full RFC-5322 threading
- HTML rendering with clickable links
- Attachments with encrypted cloud storage
- Auto-drafts, email signatures (personal + org-level)
- Alias system with independent inboxes per alias
- Inbound threat protection (authentication enforcement)

### 💬 Encrypted Messaging
End-to-end encrypted real-time messaging between Hansel users.
Messages encrypt on your device. They decrypt only on the
recipient's device. The platform holds an encrypted blob
it cannot open.

- 1:1 encrypted chat
- Messages stored locally on your device
- Auto-sync keeps conversations live
- Delete timers (10 seconds through 24 hours)

### 📁 Smart Inbox
Automatic email categorization that keeps your inbox clean
without scanning your content.

- Inbox / Starred / Sent / Drafts
- Unknown Senders / No Reply / Notifications / Likely Spam
- Move to Inbox with one tap
- Full search across all folders

### 📅 Calendar
Built-in calendar with automatic import of email invites.
Month, week, and day views. Reminders. No Google required.

### 📝 Notes
Rich text notes with folder hierarchy. Fully local.
Fully yours. Never synced to any server without your permission.

### 🔗 Alias System
Multiple email addresses, one account. Each alias has its
own inbox, sent folder, and identity. Useful for separating
work, personal, and project communications.

### 👥 Multi-Profile
Multiple independent users on one device. Each profile
has isolated identity, messages, and settings. PIN lock
per profile. Device admin code for IT management.

---

## The Wicked Crumbs Protocol

Hansel is built on a proprietary cryptographic protocol called
**Wicked Crumbs** — designed by Kemone Phillips, engineered in
collaboration with Bob.

The core idea: leave a crumb trail, not a data trail.

Every message you send carries a cryptographic crumb — a
mathematically verifiable proof that you sent it, linked to
the previous message in the chain. Your identity rotates
automatically on a 24-hour cycle. The platform routes your
messages but never holds the keys to read them.

This means:
- **Spam is solved.** Without your key, a message cannot arrive.
  No filters. No AI scanning. The architecture prevents it.
- **Eavesdropping is prevented.** Even if someone intercepts a
  message in transit, they hold an encrypted blob they cannot open.
- **Impersonation is prevented.** The crumb chain provides
  cryptographic proof of message origin — detectable if tampered with.
- **Forward privacy is maintained.** Rotating identities mean
  a compromised identity window is limited to 24 hours.

The protocol has a full technical specification and a complete
test suite. It is proprietary technology — not published or
licensed externally.

---

## Enterprise Admin Dashboard

Business Professional subscribers get a full enterprise admin
console with everything a team needs to manage communications
at scale.

**Overview** — Real-time org health metrics and activity feed

**Users** — Seat management, name editing, email assignment

**Email** — Domain management, alias oversight

**Billing** — Subscription management, usage analytics,
Stripe-powered payments

**Backup** — Storage metrics, compliance tracking,
backup oversight per user

**Permissions** — Org-wide and per-user policy controls

**Activity Log** — Complete audit trail — every login,
email sent, backup created, seat assigned

**Message Trace** — Full delivery tracking per email —
delivered, bounced, delayed

**DLP** — Data Loss Prevention — scan every outbound email
for sensitive data before it leaves. Five built-in patterns
plus custom rules.

**eDiscovery** — Legal search across email history.
Legal hold prevents deletion. JSON and CSV export.
Built for compliance requirements.

**Settings** — Org identity, domain configuration,
billing portal access

---

## Pricing

| Plan | Price | Best For |
|------|-------|----------|
| **Sovereign** | Free | Individual privacy-first users |
| **Sovereign Connected** | Free | Individuals who need email bridging |
| **Sovereign Pro** | $4/month | Power users and freelancers |
| **Business Essentials** | $7/seat/month | Small teams |
| **Business Professional** | $12/seat/month | Enterprise orgs |

All plans include the Wicked Crumbs Protocol, encrypted messaging,
and your own email address. Business plans add the admin console,
DLP, eDiscovery, and compliance tooling.

---

## The Philosophy

Hansel exists because we believe communication sovereignty is a right,
not a premium feature.

- **Your email server** — not someone else's infrastructure
- **Your encryption keys** — generated on your device, never transmitted
- **Your data** — stored locally, backed up by you, on your terms
- **Your identity** — rotating, anonymous to the platform, owned by you
- **Your domain** — permanent, portable, forever yours

Every other platform makes the same silent trade: convenience in
exchange for control. The moment they decide you've violated their
terms — or simply forget to charge your card — the switch flips
and your communications disappear.

Hansel flips the model. The platform cannot read your messages.
The platform cannot lock you out. The platform does not know
who you are. It is a router. Nothing more.

**We don't hold the keys. You do.**

---

## Security

- Messages encrypted with RSA-4096 before leaving your device
- Platform holds encrypted blobs it cannot decrypt
- Private keys never transmitted to any server
- Identity rotation every 24 hours limits exposure windows
- All outbound email cryptographically signed
- Inbound authentication enforcement blocks spoofed senders
- DLP scanning before every outbound email
- Complete audit trail for all significant actions
- Legal hold prevents evidence deletion for compliance

To report a security vulnerability:
**security@wicked-crumbs.com**

---

## Coming Soon

- macOS desktop client
- iOS mobile client
- Android mobile client
- Web client
- Chrome extension
- Encrypted group rooms (unlimited size)
- Perfect Forward Secrecy
- Sovereign Contact Cloud Sync

---

## Legal

Copyright © 2026 Seedling.io — Kemone Phillips.
All rights reserved.

Wicked Crumbs™ and the Wicked Crumbs Protocol are proprietary
technology. The protocol package is private and is not licensed
for external use or reproduction.

Hansel is not affiliated with Google, Microsoft, or any other
company referenced in this document.

---

<div align="center">

**The communication platform that cannot lock you out.**
**The only email system where you own the server.**
**The only messenger where the platform cannot read your messages.**

**Sovereign. Private. Yours.**

Hansel · Wicked Crumbs™ · Seedling.io

*Built by Kemone Phillips & Bob.*

</div>
