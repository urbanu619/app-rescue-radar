# Micro App Acquisition Due Diligence Checklist (30+ Items)

By **Joshua Chen** · [About / experience](2026-09-30-about-joshua-chen.md) · urbanu619@gmail.com


Buying a small App or micro-SaaS is not like buying a house. Ownership is scattered across code, domains, trademarks, store accounts, payment rails, API keys, and personal inboxes. If any one of those does not transfer cleanly, you did not buy a business — you bought a liability with a login screen.

Use this checklist before you wire money. Treat every unchecked box as a negotiation point or a walk-away reason.

## Definition

**Micro App acquisition due diligence** is a pre-purchase check that ownership, money, users, tech, store, legal, and ops can move to you with evidence—not screenshots alone. For small Apps and micro-SaaS, title is scattered across code, domain, store account, payment rails, API keys, and inboxes; any piece that does not transfer turns a “business” into a liability.

**Read-only verification** means the seller grants dashboard or export access you can view without withdraw/admin power (for example Stripe, store consoles, analytics). Chart PNGs are not read-only verification.

## FAQ

**What should you check before buying a micro App or micro-SaaS?**  
Confirm transferable ownership (code history, domain, store, subscriptions, data), read-only revenue proof, retention, legal/IP assignment, and that you can operate the product after the seller leaves.

**Why are screenshots not enough?**  
They are marketing artifacts. Read-only verification against payment and store dashboards is what underwrites revenue and refunds.

**What is the fastest way to kill a bad listing?**  
Run ownership and money first. If the seller blocks read-only access, or critical accounts are personal-only and non-assignable, walk or reprice as source code.

**Does this checklist replace a lawyer?**  
No. It is a buyer screening tool for indie and small-studio deals. It does not replace legal, tax, or security advice in your jurisdiction.

**How to use it**

1. Run sections 1–2 on every listing (ownership + money). Kill bad deals early.
2. Run sections 3–7 only after the seller grants read-only access.
3. Section 8 is a red-flag skim. Details live in a separate piece on what not to buy.
4. Technical debt depth (rebuild cost, bus factor, secrets) expands in the companion guide on taking over someone else's codebase.

---

## 1. Transferable assets (title check)

Virtual property has no single deed. Confirm each piece can move to you.

- [ ] Full source code **and** complete Git history (all branches)
- [ ] No critical uncommitted work living only on the seller's machine
- [ ] Domain name, DNS control, and TLS certificates
- [ ] Brand assets: name, logos, design files
- [ ] Production database **and** a tested backup/restore path
- [ ] App Store / Play Console listing (or browser extension store entry)
- [ ] Analytics, monitoring, and error-tracking accounts
- [ ] Subscription / IAP migration path (RevenueCat, Stripe, Paddle, store subs)
- [ ] Third-party API accounts that are **not** personal-only keys
- [ ] Infrastructure (cloud project, hosting, CDN, email sending)
- [ ] Deploy docs and runbooks a stranger can follow
- [ ] Support macros, help center, and customer history the buyer will need
- [ ] Seller transition support window (days/hours, written)

If more than two of the above are "seller will figure it out later," price the deal as source code, not as a going concern.

---

## 2. Financials (read-only proof)

Screenshots are marketing. Dashboards are evidence.

- [ ] Read-only access to Stripe / Paddle / RevenueCat / App Store / Play Console
- [ ] Monthly revenue, refunds, chargebacks, and tax/fees broken out
- [ ] Gross margin after API, hosting, support, and ads
- [ ] MRR/ARR separated from one-time / lifetime deals
- [ ] Annual-plan renewal cliff (how much ARR renews in the next 90 days)
- [ ] Largest-customer concentration (% of revenue)
- [ ] 12+ month trend and any seasonality the seller claims
- [ ] Seller's own labor and "free" founder time **not** hidden inside "profit"

Ask for export CSVs, not just chart PNGs. If they refuse read-only access, stop.

---

## 3. Users and retention

Cumulative signups lie. Cohorts tell the truth.

- [ ] Funnel: signup → activation → paid → retained
- [ ] Cohort retention (not vanity DAU spikes)
- [ ] Active-user trend over 30 / 90 / 365 days
- [ ] Acquisition channels and whether they survive without the founder
- [ ] Review authenticity (rating bombs, review gating, bought installs)
- [ ] Support ticket themes (what breaks, who complains)
- [ ] Cancellation reasons (exit surveys or churn tags)
- [ ] Key accounts tied to the founder's personal relationships

A product that only grows through the seller's Twitter DMs is a job, not an asset.

---

## 4. Technical health (screen, then deep-dive)

This section is a go/no-go screen. Rebuild cost and remediation plans belong in the technical companion.

- [ ] Tests, CI/CD, and a deploy you can reproduce from a clean machine
- [ ] Third-party library licenses (no GPL landmines in a closed product, no abandoned critical deps)
- [ ] Schema clarity; backup restore actually tested, not assumed
- [ ] Cloud bill broken down by service; no mystery spend
- [ ] Secrets inventory; plan to rotate every key on day one
- [ ] Known incidents, CVEs, or "we do not talk about that outage"
- [ ] Bus factor: can anyone but the seller ship a fix?
- [ ] No non-transferable personal API keys in production
- [ ] No unauthorized scraping / data collection baked into the product

If the repo has no history, treat valuation as "rewrite from screenshots."

---

## 5. App stores and distribution

Store listings are distribution. Distribution that cannot transfer is worthless.

- [ ] Listing meets the platform's official transfer / account-change rules
- [ ] Bundle ID / package name ownership is clear
- [ ] Subscriptions and IAPs can migrate without stranding paying users
- [ ] Ratings, reviews, and version history reviewed for policy risk
- [ ] Prior rejections, guideline warnings, or takedown notices disclosed
- [ ] Privacy labels match actual data practices
- [ ] Push, Sign in with Apple, and other entitlement chains documented
- [ ] Certificates, provisioning, signing, and publisher account handoff planned
- [ ] Existing installed base can upgrade cleanly after transfer

---

## 6. Legal and intellectual property

You are buying rights, not vibes.

- [ ] Seller owns the source (or has written assignment from every contractor)
- [ ] Outsourced-dev contracts include IP assignment to the seller
- [ ] Employee / contractor IP assignment on file
- [ ] Trademark and domain chain of title
- [ ] Licenses for images, fonts, music, models, and datasets
- [ ] Terms of service and privacy policy current and transferable
- [ ] Lawful basis to process and transfer customer data to you
- [ ] No pending disputes, chargeback piles, or IP complaints
- [ ] Product name does not collide with a third-party mark
- [ ] Seller has the contractual right to assign customer relationships

Gray-area scrapers, unlicensed IP skins, and "AI wrappers" with no data rights fail here even when revenue looks fine.

---

## 7. Operations (what you inherit on Monday)

- [ ] Support load in hours/week at current volume
- [ ] Daily / weekly maintenance checklist
- [ ] Content or data refresh cadence the product depends on
- [ ] Vendor list with who owns each contract
- [ ] Refund policy and who executes it
- [ ] Alerts and on-call reality (not aspirational dashboards)
- [ ] Backup ownership after the seller disappears
- [ ] Roadmap promises already sold to customers but not shipped
- [ ] Whether the founder's personal brand **is** the acquisition channel

If passive income requires an active founder personality, you are buying a job with a Cap Table of one.

---

## 8. Deal protection

- [ ] Asset purchase agreement (not a handshake + PayPal)
- [ ] Explicit asset schedule attached to the contract
- [ ] Closing conditions written (access, transfer proofs, credential rotation)
- [ ] Escrow through a neutral party
- [ ] Reasonable transition help — and a hard end date
- [ ] Staged payments tied to verified transfer milestones
- [ ] Credential rotation completed before final payment
- [ ] Post-close support window defined in writing
- [ ] Undisclosed liabilities and refund responsibility allocated

---

## 9. Red-flag skim (walk away or reprice)

Any one of these should freeze the deal until explained with evidence:

- [ ] "No time to run it" **and** every metric is falling
- [ ] Huge traffic, tiny revenue, no coherent monetization story
- [ ] Revenue screenshots disagree with read-only dashboards
- [ ] Seller blocks read-only verification
- [ ] One customer is most of the revenue
- [ ] Near-100% churn or extreme refund rates
- [ ] Famous IP used without a transferable license
- [ ] Critical API or publisher account cannot transfer
- [ ] Growth dies if the seller stops posting
- [ ] Code has no version history
- [ ] Spike-then-list: revenue juiced right before the listing
- [ ] Store already warned or dinged the app
- [ ] Business depends on scraping or bypassing platform rules

→ Deeper treatment: *What not to buy* (exclusion signals).

---

## After you buy (or before you walk)

Most painful post-close surprises are not "the code is ugly." They are: a personal Stripe account, a domain on the seller's Google login, an App Store team that never transferred, or a product that only works while one contractor answers Slack.

If the checklist shows a fixable product with broken ownership or ops, that is often a **rebuild or managed-ops** problem — not a "negotiate 10% off" problem.

**Next reads**

- [The real cost of taking over someone else's codebase](2026-09-30-A2-cost-of-taking-over-someone-elses-codebase.md)
- [What not to buy: high-risk signals](2026-09-30-A3-what-not-to-buy-high-risk-signals.md)
- [Three asset types you must not mix](2026-09-30-A4-three-asset-types-you-must-not-mix.md)

**Need help executing, not just checking boxes?**

If you already own a listing — or you are about to — and the gap is engineering, migration, or week-to-week operations:

- Custom rebuild / rescue engineering: urbanu619@gmail.com
- Managed operations after close: urbanu619@gmail.com
- Product brief / intake: *[App Rescue Radar — coming soon]*

This checklist is a screening tool. It does not replace legal, tax, security, or financial advice for your jurisdiction.

---

## Source note (maintainers)

Derived from internal research sections on transferable assets and acquisition diligence. No listing prices, platform fee tables, or seller-reported multiples are included in this page. Revisit store transfer rules and payment-provider policies on the day you publish or reuse.
