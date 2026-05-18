<div align="center">

<img src="https://raw.githubusercontent.com/tkawen/tkawen-com/main/assets/og.png" width="640" alt="TKAWEN — Seven APIs. One Platform. Build anything." />

# TKAWEN

**Seven cloud APIs. One platform. Build anywhere.**

Identity · Connect · Pay · Commerce · Knowledge · Logistics · Developer

[![Website](https://img.shields.io/badge/website-tkawen.com-3b82f6?style=flat-square)](https://tkawen.com)
[![Docs](https://img.shields.io/badge/docs-developer.tkawen.com-f59e0b?style=flat-square)](https://developer.tkawen.com)
[![Status](https://img.shields.io/badge/status-status.tkawen.com-10b981?style=flat-square)](https://status.tkawen.com)
[![License](https://img.shields.io/badge/license-AGPL--3.0-blue?style=flat-square)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Discord](https://img.shields.io/badge/community-discord-5865f2?style=flat-square)](https://discord.gg/tkawen)

</div>

---

## The platform in one paragraph

Most product teams glue together five-to-seven separate vendors — Auth0 for sign-in, Twilio for SMS, Stripe for payments, Shopify for storefronts, Onfleet for delivery, AWS for everything else. TKAWEN replaces that glue layer with **one platform, one API key, one SDK, one monthly invoice**. Seven cloud APIs that ship together, bill together, and integrate together. Free sandbox, no credit card. Pay in your preferred currency from 13 supported. Open-source SDKs under MIT.

## What we ship

| Repository | What it is | Stack | License |
|------------|------------|-------|---------|
| [**tkawen-com**](https://github.com/tkawen/tkawen-com) | Marketing site for tkawen.com — sub-millisecond render | Rust · Axum · Maud | AGPL-3.0 |
| [**tkawen-developer-docs**](https://github.com/tkawen/tkawen-developer-docs) | Public docs at developer.tkawen.com — 17 pages, 4 SDKs | Astro 5 · Starlight | AGPL-3.0 |
| [**tkawen-api**](https://github.com/tkawen/tkawen-api) | Unified API gateway — one Bearer key, seven pillars (alpha) | Rust · Axum · OpenAPI 3.1 | AGPL-3.0 |
| [**oracle**](https://github.com/tkawen/oracle) | TKAWEN Macro Oracle — liquidity-first investing pipeline (research) | — | private |
| [**liqaa-meet**](https://github.com/hartemyaakoub/liqaa-meet) | Self-hostable video meetings — alternative to Zoom | Next.js · LiveKit · Whisper | AGPL-3.0 |

Plus four official SDKs under [**@hartemyaakoub**](https://github.com/hartemyaakoub): JavaScript, PHP, Python, Go — all MIT.

## The seven pillars

| # | API | Replaces | Status |
|---|-----|----------|--------|
| 01 | **Identity** — OIDC SSO, KYC, trust signals | Auth0, Okta, Clerk | live |
| 02 | **Connect** — video, voice, SMS, WhatsApp, email, TTS | Twilio, Zoom, SendGrid | live |
| 03 | **Pay** — cards, wallets, transfers, recurring (13 currencies) | Stripe, Paddle, Recurly | beta |
| 04 | **Commerce** — multi-tenant storefronts, catalog, checkout | Shopify, Square, BigCommerce | live |
| 05 | **Knowledge** — courses, AI tutors, verifiable credentials | Teachable, Coursera, Credly | live |
| 06 | **Logistics** — fleet GPS + multi-carrier shipping | Onfleet, Bringg, ShipBob | live |
| 07 | **Developer Cloud** — gateway, SDKs, OpenAPI, sandbox, status | AWS console, Vercel, Cloudflare | beta |

## Why open

Every SDK we publish is MIT. The reference apps (liqaa-meet, this very marketing site) are AGPL. The OpenAPI spec is Apache-2.0. The compliance docs and architecture decision records are CC-BY.

We are open where it matters because **lock-in is a UX failure, not a moat**. Customers pay us because the integration is faster, the billing is cleaner, and the platform is one thing. Not because their data is held hostage.

## Production proof

- **200+ live merchants** running on the Commerce pillar via [mystoq.com](https://mystoq.com)
- **4,116+ verified users** using the Knowledge pillar via [algeriacertify.com](https://algeriacertify.com)
- **17 documentation pages** in three languages at [developer.tkawen.com](https://developer.tkawen.com)
- **Sub-millisecond render times** on the marketing site (verifiable in `Server-Timing` response header)

## Get started in 60 seconds

```bash
# 1. Sign up (no credit card)
open https://id.tkawen.com/signup

# 2. Install an SDK
npm install @tkawen/sdk
# or  composer require tkawen/sdk
# or  pip install tkawen
# or  go get github.com/hartemyaakoub/tkawen-go

# 3. Make your first call
curl https://api.tkawen.com/v1/health
```

Full quickstart: **[developer.tkawen.com/intro/](https://developer.tkawen.com/intro/)**

## Reach out

| | |
|---|---|
| **Sales & partnerships** | partners@tkawen.com |
| **Security disclosures** | security@tkawen.com |
| **Press & interviews** | press@tkawen.com |
| **General** | DIRECTION@takawen.dz |
| **Community** | [discord.gg/tkawen](https://discord.gg/tkawen) |
| **Status** | [status.tkawen.com](https://status.tkawen.com) |
| **Founder** | [Hartem Yaakoub](https://hartem.tkawen.com) |

---

<div align="center">

**Built with care. Open where it matters.**

[tkawen.com](https://tkawen.com) · [developer docs](https://developer.tkawen.com) · [status](https://status.tkawen.com) · [discord](https://discord.gg/tkawen)

</div>
