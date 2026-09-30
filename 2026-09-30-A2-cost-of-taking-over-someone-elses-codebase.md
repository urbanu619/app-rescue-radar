# The Real Cost of Taking Over Someone Else's Codebase

By **Joshua Chen** · [About / experience](2026-09-30-about-joshua-chen.md) · urbanu619@gmail.com


The listing price is not what you pay. After close you inherit: a deploy you cannot reproduce, secrets you must rotate, a store transfer that takes weeks, and a product that only the seller knows how to baby-sit.

This companion expands the **technical** and **store** sections of the [acquisition due diligence checklist](2026-09-30-A1-micro-app-acquisition-due-diligence-checklist.md). It is a cost model, not a quote. Use it to decide whether you are buying a business, buying a rewrite, or walking away.

---

## What "taking over" actually includes

Transferable assets are not the same as operable assets. You need all of:

| Layer | What must land on your side | Failure mode if it does not |
| --- | --- | --- |
| Code | Full Git history, all branches, no laptop-only patches | You own a zip of unknowns |
| Runtime | Cloud project, DNS, certs, email sending, CDN | Site dies mid-migration |
| Money | Stripe/Paddle/RevenueCat/store subs under your entity | Paying users stranded |
| Store | Bundle ID, signing, publisher account per platform rules | Listing stuck on seller |
| Data | DB + tested restore + lawful transfer of customer data | You cannot ship or support |
| Ops | Runbooks, alerts, vendor logins, support history | You are on-call blind |

If any row is soft, add a line item below — do not "hope the seller helps."

---

## Cost buckets (price these before you bid)

Think in **your hours × your rate**, plus cash for vendors and store friction. Ranges below are planning bands for a solo or small team on a typical micro App / SaaS — not market rates.

### 1. Access and forensics (usually 1–3 days)

- Reproduce local build from a clean machine
- Map environments (dev / staging / prod) and who owns each cloud bill
- Inventory secrets; assume every key is compromised until rotated
- Diff "what runs in prod" vs "what is in the repo"

**Walk-away signal:** prod depends on uncommitted code or a personal laptop.

### 2. Credential and vendor rotation (usually 1–5 days, calendar time often longer)

- Rotate every API key, DB password, webhook secret, signing cert
- Move domain, DNS, and TLS off the seller's registrar login
- Recreate or transfer analytics, error tracking, email, SMS, auth providers
- Confirm third-party ToS allow account change (some do not)

**Walk-away signal:** critical API is on a personal key that cannot be reassigned.

### 3. Store and subscription migration (calendar weeks, not hours)

- Check official transfer rules for App Store / Play / extension stores **on the day you close**
- Migrate or rebuild IAP / subscription products without breaking renewals
- Re-sign, re-provision, and ship a no-op or patch release under your account
- Handle Sign in with Apple, push, and entitlement chains

**Walk-away signal:** seller cannot meet platform transfer conditions, or paid users cannot move.

### 4. Stability tax (ongoing; front-load the first 30 days)

- CI that actually runs; one path to deploy
- Backup restore drill (not a checkbox in a wiki)
- Dependency audit: abandoned packages, license traps, known CVEs
- Incident history: what broke last, what was never fixed

**Walk-away signal:** no tests, no deploy docs, and only the seller can ship.

### 5. Product debt you are buying on purpose

Only pay for debt you can fix and that unlocks value:

| Debt type | Often worth buying | Usually a rewrite |
| --- | --- | --- |
| Missing Android / second platform | You have the skill and distribution already exists | No users, no ranking |
| Bad paywall, real retention | Pricing/UX fix | Fake retention, bought installs |
| Content / SEO layer missing | You know the channel | Generic AI shell, no niche |
| i18n into a market you know | Clear demand signal | "We will translate later" with zero research |

Score **rescue fit** (can *you* fix the core problem?) before you score code elegance.

### 6. Hidden labor the P&L omitted

Sellers often exclude:

- Their own support hours
- Manual ops (CSV imports, content refreshes, "just restart the box")
- One contractor who answers Slack at 2 a.m.

Convert that into your hours. If the profit only exists because labor is free, you bought a job.

---

## A simple bid formula

```text
Max bid ≈
  value of transferable distribution and recurring revenue you can verify
  − cost of buckets 1–4 (migration & stability)
  − cost of bucket 5 you commit to in 90 days
  − buffer for refunds, chargebacks, and seller fade
```

Never invert it: do not start from asking price and "make the costs fit."

If verified recurring revenue is near zero, drop revenue multiples entirely. Compare to **rebuild cost** and **time-to-store** — that is a Type C asset ([three asset types](2026-09-30-A4-three-asset-types-you-must-not-mix.md)).

---

## Questions that expose real cost fast

Ask for answers in writing, with read-only proof where possible:

1. Can a stranger deploy from a clean clone in under a day? Show the doc.
2. What breaks if your personal GitHub / Google / Apple ID disappears tomorrow?
3. List every vendor login and whether it is corporate or personal.
4. When was the last production restore from backup?
5. Which subscriptions fail if the store listing does not transfer in 30 days?
6. Who is the bus factor for the last three production incidents?
7. What did you promise customers that is not shipped?
8. What percentage of new users last quarter came from a channel you personally own?

Any refusal to answer 1–3 is a diligence failure, not a negotiation style.

---

## When the right move is rebuild, not acquire

Acquire (or hire a rebuild) when:

- Distribution or brand search is real and transferable, but the codebase is a liability
- Store presence matters and a clean rewrite still keeps the listing / SEO path
- You need a maintainable stack for [managed operations](#need-the-migration-done) after close

Walk when:

- Nothing transfers except a zip
- Growth dies without the seller's face
- The product depends on scraping, gray IP, or a platform loophole ([exclusion list](2026-09-30-A3-what-not-to-buy-high-risk-signals.md))

---

## Need the migration done

If the checklist already told you the deal is fixable but heavy:

- Rescue engineering / codebase takeover: urbanu619@gmail.com
- Post-close managed operations: urbanu619@gmail.com
- Intake brief: *[App Rescue Radar — coming soon]*

Related:

- [Due diligence checklist (30+)](2026-09-30-A1-micro-app-acquisition-due-diligence-checklist.md)
- [What not to buy](2026-09-30-A3-what-not-to-buy-high-risk-signals.md)
- [Three asset types](2026-09-30-A4-three-asset-types-you-must-not-mix.md)

This page is a planning framework. It is not a fixed-price quote and does not replace legal, security, or tax advice.

---

## Source note (maintainers)

Derived from internal research on technical diligence, store transfer, transferable assets, and scoring dimensions. No seller financials or platform fee tables included. Re-check store transfer and payment-provider policies on publish day.
