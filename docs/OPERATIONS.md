# Portfolio Operations

## Objective

Build fast, validate early, and move every active PIGA toward a monetizable funnel without allowing portfolio breadth to become permanent partial completion.

## Attention allocation

PIGA Strategies uses a hard WIP constraint: **maximum three active PIGAs**.

The current pattern is intentionally asymmetric:

- one asset may be in **MVP REVENUE VALIDATION**
- one or two assets may be in **BUILD** approaching that gate
- everything else remains **SHELF**, **MAINTAIN**, or otherwise outside active development

SHELF is a legitimate state, not a failure state. Shelved assets retain brand, documentation, code and accumulated learning without consuming recurring execution attention.

Portfolio infrastructure such as Hustle Depot does not automatically consume an active PIGA slot. It should remain thin and primarily absorb outputs from real portfolio work rather than becoming an independent speculative build.

## The evidence gate

Every active PIGA must be moving toward one concrete external signal. Depending on the business, that signal may be:

- revenue
- a paid conversion
- an affiliate sale
- a qualified lead
- repeated product usage
- a high-intent submission
- another measurable behavior that materially informs the next commercial decision

The point is not to finish a product. The point is to build **enough product to expose the important commercial uncertainty to reality**.

Once the product can support that test, default to distribution and evidence collection rather than additional features.

## Active-asset requirement

Every active PIGA must have:

- one named lifecycle state
- one current monetizable/evidence milestone
- one measurable success condition
- an up-to-date product status record
- an executable Linear backlog
- attributable runtime costs
- commercially meaningful analytics when live

If the current milestone cannot be stated in one sentence, the asset is not sufficiently groomed for active development.

## Decision hierarchy

When deciding what to work on, prefer the fastest, cheapest and most reversible action that resolves the largest commercial uncertainty.

Priority order generally follows:

1. create the smallest complete value loop
2. connect it to a monetizable funnel
3. put real users through it
4. measure what they do
5. improve based on evidence
6. automate repeated proven work
7. scale infrastructure only when constrained

## Factory development

The PIGA factory should emerge from repeated real builds rather than be designed as a speculative platform.

When Exam Sim, AI HQ, Starterpak or another real PIGA solves a reusable problem, capture the solution. When a problem has been solved repeatedly, standardize it into the common chassis.

Likely reusable layers include:

- project/repository scaffolding
- Supabase setup and schema patterns
- authentication where required
- Stripe/payment patterns
- analytics event conventions
- email/lifecycle patterns
- AI model invocation and prompt/config management
- ingestion/retrieval patterns
- deployment/configuration conventions
- marketing attribution
- transfer documentation

The target state is that future PIGAs become increasingly **configuration on a proven chassis** and can eventually be instantiated and operated substantially by agents.

## Documentation discipline

GitHub is the canonical institutional record. Linear contains execution tasks and chat may contain exploration, but durable decisions should be reflected in the relevant repository.

Minimum product-repo documentation target:

- `docs/STATUS.md`
- `docs/PRODUCT.md`
- `docs/ARCHITECTURE.md`
- `docs/ROADMAP.md`
- `docs/OPERATIONS.md`

`STATUS.md` should remain short and current. Historical detail belongs in version control.

Hustle Depot may additionally codify reusable factory knowledge for public/commercial consumption, but it does not replace GitHub as the institutional source of truth.

## Commercial instrumentation

Instrumentation is a prerequisite for increasingly automated portfolio operation. The system needs to understand both **what users do inside a PIGA** and **which acquisition activity produced those users**.

Standard direction:

- **PostHog** — product/site analytics: acquisition attribution, meaningful events, funnels, conversion, retention, session replay, behavioral diagnosis and experimentation.
- **Metricool** — cross-channel marketing/social publishing analytics and campaign/post performance where supported.
- **Supabase** — product/runtime data and durable business records.
- **n8n** — automation/orchestration between systems where useful.

Do not add analytics products merely for dashboard redundancy. Standardize commercially meaningful events across PIGAs so future agents can reason over comparable signals.

Each live PIGA should eventually expose enough data to understand:

- qualified traffic/users
- acquisition source / campaign / content
- activation or core value event
- monetization trigger
- conversion rate
- revenue
- variable cost / contribution where applicable
- repeat behavior / retention where applicable
- meaningful abandonment or failure points

The eventual goal is a closed learning loop:

**Marketing activity → qualified traffic → product behavior → monetization → economics → next action**

## Build-to-transfer discipline

Avoid shared dependencies that make one PIGA difficult to sell independently. Each mature asset should have isolated ownership boundaries for code, database, domain, analytics, configuration and costs wherever practical.

Third-party credentials should be documented and re-keyable. Automations should be inspectable. Business logic should not exist only inside a founder's memory or a chat transcript.

## Review cadence

Portfolio reviews exist to make allocation decisions, not create status theater.

For each active asset ask:

1. What gate are we trying to cross?
2. What evidence do we have?
3. What is the smallest action that produces the next useful evidence?
4. Are we building something that could already be tested?
5. Did this build produce reusable factory knowledge worth codifying?

The governing question is: **what evidence justifies continuing to allocate attention to this asset?**