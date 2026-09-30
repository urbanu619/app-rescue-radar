---
title: "Three Asset Types You Must Not Price the Same Way"
description: "Type A operating business, Type B distribution, and Type C source-only—how to classify marketplace listings before you bid."
permalink: /asset-types/
---

# Three Asset Types You Must Not Price the Same Way

By **Joshua Chen** · [About / experience](about.md) · urbanu619@gmail.com


Marketplaces mix three different things under one "SaaS for sale" headline. Mix up the type, and you will apply the wrong valuation, the wrong diligence, and the wrong post-close plan.

Classify first. Diligence second. Bid last.

## Definition

**Type A / B / C** is a three-way classification for marketplace listings so you do not price source code like a business:

- **Type A — operating small business:** verified recurring revenue, active users, ongoing acquisition, seller can grant read-only proof. Underwrite with profit, churn, concentration, and transfer.
- **Type B — distribution without working monetization:** real transferable attention (store rank, SEO, community, newsletter, organic installs) but weak or broken charging. You are buying a channel, not a P&L.
- **Type C — product / source-only:** built or “dev complete,” little or no real users or revenue. Compare to rebuild cost; never apply ARR multiples.

## FAQ

**What are the three asset types when buying a micro-SaaS?**  
Type A (operating business), Type B (distribution without monetization), and Type C (source / finished product without proof of use).

**Why can’t you use the same valuation for all three?**  
Type A is priced on durable profit and risk. Type B is priced on transferable attention plus your monetization plan. Type C is priced on rebuild and time-to-ship. Mixing them is how buyers overpay.

**How do you classify a listing quickly?**  
If verified recurring revenue and retention exist → A. Else if verified transferable distribution exists → B. Else → C.

**Is a “dev complete” App with no users a business?**  
No. That is Type C. Treat it as software and listing experience, not as SaaS priced on multiples.

---

## Type A — Operating small business

**What it is:** recurring revenue, active users, ongoing acquisition, seller can grant read-only proof.

**You are buying:** a going concern (plus the usual transfer mess).

**How to underwrite:**

- Verify MRR/ARR, refunds, concentration, churn, trend
- Confirm acquisition survives without the founder
- Confirm store, domain, payments, and data can transfer
- Value against durable profit and risk — not against "cool stack"

**Wrong move:** treating it like a source dump because the UI is ugly.

**Right diligence weight:** finance + retention + transfer (full [checklist](due-diligence-checklist.md)).

---

## Type B — Distribution without working monetization

**What it is:** real store rank, SEO, community, newsletter, or organic installs — but weak or broken charging.

**You are buying:** attention and habit, not a P&L.

**How to underwrite:**

- Prove the traffic/installs are real and **transferable**
- Explain in one paragraph how *you* will monetize without killing retention
- Price the channel; treat code as optional

**Wrong move:** paying a business multiple for "potential" with no payers.

**Right diligence weight:** distribution quality + transfer + your fix plan ([codebase cost](codebase-takeover-cost.md) only for what you will keep).

---

## Type C — Product / source-only finished goods

**What it is:** built (or "dev complete"), little or no real users or revenue. Screenshots and a repo.

**You are buying:** time saved versus building from zero — maybe a store shell.

**How to underwrite:**

- Compare to rebuild cost and time-to-ship
- Inspect code quality, licenses, and transfer of any listing
- Do **not** wrap it in SaaS revenue-multiple language

**Wrong move:** "It is cheap at $X because SaaS sells at N× ARR" when ARR is approximately zero.

**Right diligence weight:** technical + IP + store shell. Skip fantasy cohort analysis.

---

## Side-by-side

| | Type A Business | Type B Distribution | Type C Source |
| --- | --- | --- | --- |
| Proof that matters | Read-only revenue & cohorts | Rankings, SEO, owned channels | Repo + licenses + rebuild estimate |
| Primary risk | Churn, concentration, transfer | Traffic quality, monetization miss | You rebuild anyway |
| Valuation anchor | Verified profit & durability | Cost to buy equivalent attention | Rebuild / outsource cost |
| Post-close job | Operate and improve | Install a paywall / offer | Rewrite or productize |
| Common seller story | "No time" | "Bad at marketing" | "Dev complete, needs launch" |

---

## What is actually worth buying (inside any type)

Regardless of A/B/C, durable value clusters in four places:

1. **Verified distribution** — organic search, store search, real community, transferable content/brand demand. Prefer this over clever code.
2. **Verified user behavior** — DAU/WAU/MAU trends, paid conversion, retention cohorts, refunds — not lifetime signup counts.
3. **Fully transferable package** — code history, domain, store, subs, APIs, infra, docs, support handoff.
4. **A problem you know how to fix** — traffic without monetization, one platform missing, wrong market language, bad paywall, missing content engine.

If none of the four show up, you are browsing, not acquiring.

---

## How mix-ups happen on listing pages

- Type C listed next to Type A with the same template fields ("MRR", "multiples")
- Type B sold with a story about "easy upside" and no payers
- Type A with collapsing metrics sold as Type B "brand asset"
- Side-project marketplaces where **most** inventory is Type C (code), not a business

Your first annotation on every listing should be a single letter: **A, B, or C**. If you cannot choose, you do not understand the asset yet.

---

## Decision rule

```text
If verified recurring revenue + retention → underwrite as A
Else if verified transferable distribution → underwrite as B
Else → underwrite as C (rebuild lens only)
```

Then run type-appropriate diligence. Use the [exclusion list](what-not-to-buy.md) before you fall in love with the demo.

Multiples and "why prices look low" are a separate topic *(A6, after light verification)*. Do not borrow a multiple until the type is A and the profit is real.

---

## When classification says "build instead"

- You need Type A outcomes but only Type C inventory fits your niche
- Type B distribution exists in your head, not on the listing
- Transfer and IP will never be clean

That is a **custom build** problem:

- Custom product build: urbanu619@gmail.com
- Rescue / takeover engineering on a Type A/B with ugly code: urbanu619@gmail.com
- Intake: *[App Rescue Radar — coming soon]*

Related:

- [Due diligence checklist](due-diligence-checklist.md)
- [Cost of taking over a codebase](codebase-takeover-cost.md)
- [What not to buy](what-not-to-buy.md)

---

## Source note (maintainers)

Derived from internal research on asset taxonomy and "worth buying" criteria. No listing prices or current market multiple bands included on this page.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are the three asset types when buying a micro-SaaS?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Type A (operating business), Type B (distribution without monetization), and Type C (source / finished product without proof of use)."
      }
    },
    {
      "@type": "Question",
      "name": "Why can't you use the same valuation for all three?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Type A is priced on durable profit and risk. Type B is priced on transferable attention plus your monetization plan. Type C is priced on rebuild and time-to-ship. Mixing them is how buyers overpay."
      }
    },
    {
      "@type": "Question",
      "name": "How do you classify a listing quickly?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "If verified recurring revenue and retention exist → A. Else if verified transferable distribution exists → B. Else → C."
      }
    },
    {
      "@type": "Question",
      "name": "Is a \"dev complete\" App with no users a business?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. That is Type C. Treat it as software and listing experience, not as SaaS priced on multiples."
      }
    }
  ],
  "url": "https://urbanu619.github.io/app-rescue-radar/asset-types/"
}
</script>
