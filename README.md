# PIGA Strategies

**Passive Income Generating Assets — built to operate or sell.**

PIGA Strategies is a faceless holding company and digital-asset factory. It creates lean, well-designed, automated businesses with measurable economics and transferable value.

This repository is the canonical source of truth for the portfolio-level mandate, principles, operating system, architecture standards, and portfolio registry. Product-specific implementation belongs in each PIGA's own repository.

## Mandate

A **PIGA** is a product developed under PIGA Strategies that is designed to become a low-touch, measurable, profitable and transferable economic asset.

Every PIGA must have:

- **Funnel:** a distribution/acquisition path that brings users into contact with monetization.
- **Trigger:** a monetizable action or mechanism capable of generating revenue without marginal human fulfillment at steady state.

“Passive” does not mean zero work. It means declining or negligible marginal labor per income-generating transaction.

The smallest acceptable commercial unit is:

**User → valuable action → conversion → revenue**

Commercial validation outranks technical sophistication. Manual validation and fulfillment are acceptable before demand is demonstrated. Automation follows proven workflows rather than hypothetical scale.

Every PIGA is designed for two possible outcomes: **operate it for cash flow or sell it as a transferable asset.**

## Operating doctrine

The portfolio is not managed as ten simultaneous side projects. It is managed as a pipeline of assets moving through a factory.

Not every PIGA may be active at once. Active development is capped at **three BUILD assets**. A new PIGA does not enter BUILD until another exits.

Portfolio operating states:

| State | Meaning |
|---|---|
| **BUILD** | Active product work toward a defined monetizable milestone |
| **SELL** | Product works; primary effort is acquisition and revenue |
| **MAINTAIN** | Live and substantially automated; only required upkeep |
| **SHELF** | Preserved but receives effectively zero active attention |

Attention is milestone-driven, not evenly distributed. The objective is to push assets through monetizable milestones, move proven businesses toward SELL/MAINTAIN, and shelf or kill weak hypotheses.

## Portfolio

The current portfolio includes:

| PIGA | Thesis |
|---|---|
| **Starterpak.ai** | Curated commerce sets answering: “What is the smallest sensible collection of things I should buy to reliably create outcome X?” |
| **Exam Sim** | Law-school exam simulation: generated practice exams, realistic administration, individualized grading, diagnosis and iterative improvement |
| **Hustle Depot** | Marketplace/factory for acquiring ready-to-run digital business assets |
| **The AI HQ** | B2B AI implementation diagnosis → Automation Brief → implementation demand |
| **The Hedge** | Sophisticated retail-investor education, intelligence and tools |
| **Onchain Radar** | Crypto/onchain market intelligence |
| **DIGIT** | Digital-likeness licensing infrastructure for creators and people with marketable likenesses |
| **Loserville.tv** | Media brand/product; thesis still being developed |
| **Godot / go-dot.ai** | Local/luxury concierge for date nights, social itineraries and related booking/referral demand |
| **Shorts Engine** | Automated short-form media operation |

Current operating state should be updated as portfolio priorities change; do not infer activity from the existence of a brand or repository.

## Principles

1. **PIGA Definition** — Build low-touch, measurable, profitable, transferable economic assets.
2. **Commercial Objective** — Optimize after-tax cumulative cash flow plus transferable asset value.
3. **Monetizable Wedge** — Every PIGA needs a clear funnel and trigger; build the smallest complete monetizable solution.
4. **Commercial Validation** — Behavior and revenue outrank enthusiasm.
5. **Evidence Discipline** — Distinguish FACT, ASSUMPTION, HYPOTHESIS and RESULT.
6. **Stage Discipline** — Do not solve later-stage problems prematurely.
7. **Decision-Making** — Prefer the fastest, cheapest, reversible action that resolves the largest commercial uncertainty.
8. **Kill/Pivot Discipline** — Weak evidence should reduce investment, not generate rationalization.
9. **Product** — Deliver first-user value without requiring network effects.
10. **Platform Timing** — A platform is earned through repeated demand, not assumed in the starting specification.
11. **Buyer Selection** — Favor narrow, identifiable buyers with budgets, mandates or meaningful economic pain.
12. **Market Selection** — Evaluate demand × intent × monetization × fit ÷ competition.
13. **Distribution** — Intercept existing demand; favor outputs that are shareable, indexable or referable.
14. **Monetization** — Every product should naturally lead to a paid action; optimize contribution per qualified user.
15. **Capital & Cost Discipline** — Keep fixed costs low until economics justify expansion.
16. **Manual Before Automated** — Manually prove uncertain workflows where practical.
17. **Automation** — Replace proven repeated work, not imagined future work.
18. **Technical Restraint** — Build only the infrastructure required by the current commercial stage.
19. **Build vs Buy** — Buy commodity capability; build differentiated value.
20. **Architecture** — Use a common template, not a common monolith.
21. **Source & Data Architecture** — Prefer replaceable, normalized inputs and the lowest-risk viable access method.
22. **Proprietary Data** — Create value through normalization, classification, relationships, interpretation, ranking, synthesis, history and workflow.
23. **Instrumentation & Learning** — Measure commercially meaningful behavior and feed results back into decisions.
24. **Transferability & Institutional Memory** — Design the business so another owner can understand, operate and acquire it.

## Standard technical architecture

Default stack, modified only when the product requires otherwise:

- **Lovable** — frontend/product creation
- **GitHub** — source control and institutional memory from day one
- **Supabase** — database, backend, auth and storage
- **Stripe** — payments
- **Resend** — transactional/lifecycle email
- **PostHog** — product and commercial analytics
- **Sentry** — error monitoring
- **n8n** — automation/orchestration
- **OpenAI / Claude-class models** — AI capabilities where economically justified

Each PIGA should have its own repository, Supabase project, analytics property, environment variables, domain configuration, and attributable revenue/expenses. No PIGA should depend on another PIGA's private database, infrastructure or undocumented credentials.

No auth unless needed. No complex payments before there is something to sell. No infrastructure for hypothetical constraints.

## Transferability standard

A mature PIGA should be capable of being transferred as a functioning business asset, not merely a code repository. Where applicable the transfer package should include:

- domain and brand assets
- source code and deployment configuration
- database schema, migrations and appropriate seed/sample data
- analytics and revenue history
- distribution and monetization infrastructure
- automations and AI workflows/prompts
- environment-variable inventory and credential re-key checklist
- architecture and operating documentation
- SOPs and known issues
- product roadmap
- GTM starter assets

Where a third-party account cannot cleanly transfer, the architecture should allow a buyer to replace credentials or reconnect their own account without rebuilding the product.

## Repository standard

Each PIGA repository should maintain a lightweight `/docs` spine:

- `STATUS.md` — what it is, lifecycle state, what is live, current milestone
- `PRODUCT.md` — customer, wedge, value proposition, business model, product principles
- `ARCHITECTURE.md` — stack, services, integrations and data model
- `ROADMAP.md` — milestones and outstanding work
- `OPERATIONS.md` — operation, automation and transfer instructions

This portfolio repository governs shared doctrine. Product repositories govern product-specific truth.

## Operating systems

- **GitHub** = canonical institutional memory and source of truth
- **Linear** = work queue and execution state
- **Lovable** = product-building environment
- **Supabase** = runtime data/backend
- **Drive** = working files and source assets

Decisions that materially change a PIGA's product, architecture, monetization or operating state should ultimately be reflected in GitHub rather than living only in chat or Linear.

## Portfolio lifecycle

Concept → Wedge → Validation → MVP → First Revenue → Repeatable Revenue → Automation → Scale or Sale

Advancement is evidence-based. The purpose of the factory is not to maximize the number of projects created; it is to maximize the number of economically useful assets that reach operation or sale.