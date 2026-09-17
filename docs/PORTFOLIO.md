# PIGA Portfolio Registry

This document is the portfolio-level registry. Product-specific implementation belongs in each PIGA repository.

## Portfolio operating model

PIGA Strategies limits active work to **three PIGAs at a time**. The objective is not equal attention across the portfolio; it is to move a small number of assets to a commercial evidence gate while preserving the option value of everything else.

Working states:

- **BUILD** — active product work toward a monetizable test.
- **MVP REVENUE VALIDATION** — product is sufficiently live; primary work is generating real market/revenue evidence rather than adding product scope.
- **SELL** — validated product where acquisition/revenue is the primary operating constraint.
- **MAINTAIN** — live and substantially automated; only required upkeep.
- **SHELF** — preserved but receives effectively zero active development attention.

A new PIGA should not enter active work until capacity opens or another asset reaches its next gate.

## Current active portfolio

| Asset | Current state | Immediate gate |
|---|---|---|
| **Starterpak.ai** | MVP REVENUE VALIDATION | Generate the 3 qualifying Amazon affiliate sales required for Associates/API progression. No additional product build unless evidence requires it. |
| **Exam Sim** | BUILD | Reach revenue validation: production LLM generation + grading loop, site aligned to actual capabilities, pricing/entitlements implemented, Stripe live, then acquire real users. |
| **The AI HQ** | BUILD | Produce a genuinely useful legal AI workflow audit/report from attorney workflow input using a deliberately narrow intelligence corpus. Validate use/demand before generalizing the intelligence platform. |

### Starterpak

Starterpak is the first asset through the factory into commercial testing. Ten Pak pages are live with affiliate links and provisional Amazon Associates approval. Product expansion is paused while GTM focuses on generating the first three qualifying sales.

### Exam Sim

Exam Sim is the next asset being pushed to the same revenue-validation gate. The monetizable unit is not an AI prompt or practice question; it is a **generated, administered and graded law-school practice exam** with individualized feedback and iterative improvement.

Current pricing thesis:

- Cold Call — $0 — 1 practice test per week, resets Monday
- Top Half — $50 — 5 practice tests
- Top Third — $100 — 10 practice tests
- Top 10% — $300 / semester — unlimited usage for six months, subject to reasonable anti-abuse controls

### The AI HQ

The AI HQ is both a PIGA and the proving ground for a reusable intelligence architecture. The initial commercial wedge is a legal AI workflow auditor: an attorney describes a workflow; AI HQ uses a curated intelligence layer to recommend an operational process, tool stack and relevant vendor options in a useful report.

Do not build a generalized AI-news/intelligence platform before this narrow output proves useful.

The architectural pattern being tested is broadly:

**Sources → ingestion → enrichment → retrieval → synthesis → audience-specific output**

If proven, the pattern can inform The Hedge and Onchain Radar without forcing those products into active development now.

## Portfolio infrastructure

### Hustle Depot

Hustle Depot is currently classified as **portfolio/factory infrastructure rather than one of the three active PIGAs**.

It runs alongside the portfolio and should accumulate value as a byproduct of real PIGA construction. Its roles are:

1. Public portfolio/inventory layer showing digital businesses and concepts as they become real.
2. Codification layer for the repeatable knowledge, templates and architecture learned while building PIGAs.
3. Future factory interface for rapidly creating and packaging new digital businesses.
4. Potential marketplace for selling transferable digital business assets.
5. Potential commercial product for people who want to build or acquire businesses using a similar operating model.

Hustle Depot should not become a fourth active build. It should absorb proven factory knowledge from Starterpak, Exam Sim and AI HQ rather than inventing a generalized factory in advance.

## Shelved / option-value portfolio

| Asset | Thesis | Current treatment |
|---|---|---|
| **The Hedge** | Sophisticated retail-investor education/intelligence/tools | SHELF; potential reuse of AI HQ intelligence chassis |
| **Onchain Radar** | Crypto/onchain market intelligence | SHELF; potential reuse of AI HQ intelligence chassis |
| **DIGIT** | Digital-likeness licensing infrastructure | SHELF |
| **Loserville.tv** | Media brand/product | SHELF |
| **Godot / go-dot.ai** | Local/luxury concierge | SHELF |
| **Shorts Engine** | Automated short-form media operation | SHELF |

## Factory thesis

The long-term objective is to make PIGA creation increasingly standardized, fast and eventually agent-operable. The factory is **not** a large platform to design before the portfolio works.

Instead:

1. Build real PIGAs.
2. Solve the immediate commercial and technical problems.
3. When the same problem is solved repeatedly, extract the reusable solution into the common chassis.
4. Codify the solution in GitHub and, where useful, Hustle Depot.
5. Increase the percentage of each future PIGA that can be instantiated from configuration rather than built from scratch.

PIGAs create knowledge → knowledge strengthens the factory → the factory reduces the cost and time required to create future PIGAs.

## Portfolio review

A portfolio review should answer:

1. What is the single current evidence gate for each active asset?
2. What evidence changed since the last review?
3. Is product work still required, or should the asset be in market testing?
4. Should an asset advance, remain active, pivot, or return to SHELF?
5. What reusable architecture or operating knowledge did the active builds produce?

The governing objective is to move assets toward **real monetizable funnels and market evidence**, not maximize project count or feature completion.