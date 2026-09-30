---
title: "Buy or Build: A Decision Framework for Micro Apps"
description: "Decide whether to buy, rescue, or build a micro App or micro-SaaS after classifying the asset as Type A, B, or C."
permalink: /buy-or-build/
---

# Buy or Build: A Decision Framework for Micro Apps

By **Joshua Chen** · [About / experience](about.md) · urbanu619@gmail.com


Most indie founders ask the wrong first question ("What should I build?"). The real decision is:

```text
Discover a real niche need
→ See if someone already validated it poorly
→ Choose: build from zero · buy and rescue · or steal the insight only
```

This hub page routes that choice. Use it once per opportunity — not once per career.

## Definition

**Buy or build (for micro Apps / micro-SaaS)** means choosing, for one concrete opportunity, whether to (1) acquire and rescue an existing product, (2) ship a new product yourself, or (3) take only the market insight and ignore the listing. It is not a career-wide ideology. Classify the asset first (Type A / B / C), then pick the path.

## FAQ

**What is the buy-or-build decision for a small App?**  
It is the choice between purchasing a transferable product, building from zero, or borrowing only the problem insight—made after you know whether a real need and a clean asset exist.

**When should an indie developer buy instead of build?**  
When a Type A or Type B asset can transfer (store, domain, payments, data), the price plus migration still beats rebuild cost, and you can fix the core flaw within about 90 days.

**When should you build instead of buy?**  
When inventory is Type C or gray, title cannot transfer, or no listing matches a need you have already validated.

**What does “insight only” mean?**  
You keep the job-to-be-done and the failure lesson from a weak listing or shutdown post, then ship your own product with clean ownership—no escrow, no zombie dependencies.

---

## The three outcomes (pick one)

| Path | You pay for | You still must do | Skip when |
| --- | --- | --- | --- |
| **Build** | Time, infra, store setup | Distribution and product risk | A transferable Type A/B asset already exists at a sane price |
| **Buy / rescue** | Purchase + migration + debt | Diligence and 90-day fix | Nothing transfers, or you cannot fix the core problem |
| **Insight only** | Research time | Your own build later | You confuse "I saw a listing" with "I own distribution" |

Buying is not cheaper by default. Building is not safer by default. **Classify the asset, then choose the path.**

---

## Step 1 — Is the need real?

Before marketplaces or wireframes:

1. Who hits this problem weekly?
2. What clumsy workaround do they use now?
3. Do they already pay for adjacent tools?
4. Can first value appear in ~60 seconds?
5. Is there a cheap channel (search, community, niche media)?
6. Does the core value survive without a foundation-model wrapper?
7. After a clone of the UI, do data, workflow, or distribution still moat you?
8. Are platform, copyright, privacy, and API risks bounded?

If you cannot answer these, you are not ready to buy *or* build. Methods for finding underpriced needs: [How to find undervalued demand](undervalued-demand.md).

---

## Step 2 — What kind of asset is on the table?

Marketplaces mix three types. Pricing them the same is how people overpay.

- **Type A** — operating small business (verified recurring revenue)
- **Type B** — real distribution, weak monetization
- **Type C** — source / "dev complete" with no proof of use

Full taxonomy: [Three asset types you must not mix](asset-types.md).

**Rule of thumb**

```text
Type A + you can operate it     → consider buy
Type B + you own the monetization fix → consider buy
Type C                          → usually build (or buy only at rebuild cost)
Gray / non-transferable         → walk ([exclusion list](what-not-to-buy.md))
```

---

## Step 3 — Buy path (only after classification)

1. Find listings on the right marketplace for that size ([platform comparison](where-to-buy.md)).
2. Run the [due diligence checklist](due-diligence-checklist.md) — ownership first, vanity metrics last.
3. Price migration and code debt with [codebase takeover costs](codebase-takeover-cost.md).
4. Treat "cheap multiples" as a risk signal until proven otherwise ([why multiples look low](valuation-multiples.md)).

Buy when: distribution or revenue is verified, title can transfer, and the broken piece is something **you** know how to fix in 90 days.

---

## Step 4 — Build path (when inventory fails you)

Build when:

- No Type A/B asset exists in your niche at a price that beats rebuild
- IP, store, or data transfer will never be clean
- You need ownership structure right from day one (entity, keys, store)

Worth-building filter: [What counts as a niche App worth shipping](worth-building.md). Idea pool: [30+ niche ideas](niche-idea-pool.md).

Building still benefits from failure databases and complaint mining — same evidence stack as buyers use.

---

## Step 5 — Insight-only (the underrated third path)

Sometimes the listing is worthless and the **complaint cluster** is gold. You take:

- The job-to-be-done
- The failed monetization lesson
- The channel that almost worked

…and you ship a clean product. No escrow, no zombie dependencies. This is not "giving up on acquisitions"; it is refusing to buy Type C at Type A prices.

---

## One-page decision card

```text
Need real? ──no──► research more (B3)
   │yes
Asset type? ──C / gray──► build or walk
   │A or B
Can title transfer? ──no──► walk
   │yes
Can you fix the core flaw in 90 days? ──no──► walk or hire rebuild
   │yes
Verified $ or distribution justifies price + migration? ──no──► walk
   │yes
BUY / RESCUE
```

---

## Where this site goes next

**Buy cluster:** [checklist](due-diligence-checklist.md) · [codebase cost](codebase-takeover-cost.md) · [exclusions](what-not-to-buy.md) · [asset types](asset-types.md) · [marketplaces](where-to-buy.md) · [multiples](valuation-multiples.md)

**Build cluster:** [worth building](worth-building.md) · [idea pool](niche-idea-pool.md) · [undervalued demand](undervalued-demand.md)

**Help executing:** [App Rescue Radar](app-rescue-radar.md) — screening, rescue engineering, managed ops. Email: urbanu619@gmail.com

---

## Source note (maintainers)

Hub framing from internal research on opportunity radar, marketplaces, worth-buying criteria, and product phases. No live listing financials on this page.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is the buy-or-build decision for a small App?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It is the choice between purchasing a transferable product, building from zero, or borrowing only the problem insight—made after you know whether a real need and a clean asset exist."
      }
    },
    {
      "@type": "Question",
      "name": "When should an indie developer buy instead of build?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "When a Type A or Type B asset can transfer (store, domain, payments, data), the price plus migration still beats rebuild cost, and you can fix the core flaw within about 90 days."
      }
    },
    {
      "@type": "Question",
      "name": "When should you build instead of buy?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "When inventory is Type C or gray, title cannot transfer, or no listing matches a need you have already validated."
      }
    },
    {
      "@type": "Question",
      "name": "What does \"insight only\" mean?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You keep the job-to-be-done and the failure lesson from a weak listing or shutdown post, then ship your own product with clean ownership—no escrow, no zombie dependencies."
      }
    }
  ],
  "url": "https://urbanu619.github.io/app-rescue-radar/buy-or-build/"
}
</script>
