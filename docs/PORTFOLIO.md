# PIGA Portfolio Registry

This document is the portfolio-level registry. Product-specific status belongs in each PIGA repository's `docs/STATUS.md`.

## Portfolio attention rule

At most **three PIGAs may be in BUILD simultaneously**.

States:
- **BUILD** — active product work toward a defined monetizable milestone
- **SELL** — working product; acquisition/revenue is the primary constraint
- **MAINTAIN** — live and substantially automated
- **SHELF** — preserved with effectively zero active attention

A new asset cannot enter BUILD until another exits. This prevents portfolio breadth from becoming permanent partial completion.

## Registry

| Asset | Core thesis | Repository / source of truth | State |
|---|---|---|---|
| Starterpak.ai | Curated commerce sets optimized for completeness without excess | `pigastrategies-ctrl/starter-pak-studio` | Update from product repo |
| Exam Sim | Generated, administered and graded law-school exam simulation | `pigastrategies-ctrl/exam-sim` | Update from product repo |
| Hustle Depot | Marketplace/factory for ready-to-run digital business assets | `pigastrategies-ctrl/hustle-depot-launchpad` | Update from product repo |
| The AI HQ | AI implementation diagnosis and Automation Briefs | `pigastrategies-ctrl/the-ai-hq-85fb451a` | Update from product repo |
| The Hedge | Retail-investor education/intelligence/tools | Repository TBD | SHELF unless activated |
| Onchain Radar | Crypto/onchain market intelligence | Repository TBD | SHELF unless activated |
| DIGIT | Digital-likeness licensing infrastructure | Repository TBD | SHELF unless activated |
| Loserville.tv | Media brand/product | Repository TBD | SHELF unless activated |
| Godot / go-dot.ai | Local/luxury concierge | Repository TBD | SHELF unless activated |
| Shorts Engine | Automated short-form media operation | Repository TBD | SHELF unless activated |

## Portfolio review

Portfolio review should answer only a few questions:

1. Which assets are consuming active attention?
2. What is the single current monetizable milestone for each active asset?
3. What evidence changed since the last review?
4. Should any asset move BUILD → SELL, MAINTAIN or SHELF?
5. Is a SHELF asset now more valuable to activate than one of the current BUILD assets?

The portfolio should not optimize for equal attention. It should allocate attention to the assets with the highest-value unresolved commercial milestone.