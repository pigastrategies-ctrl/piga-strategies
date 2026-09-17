# Portfolio Operations

## Objective

Prevent a broad portfolio from becoming a collection of neglected half-built projects while preserving the option value of good ideas.

## Attention allocation

PIGA Strategies uses a hard WIP constraint: **maximum three BUILD assets**.

SHELF is a legitimate state, not a failure state. Shelved assets retain brand, documentation, code and accumulated learning without consuming recurring execution attention.

## Active-asset requirement

Every BUILD or SELL PIGA must have:

- one named lifecycle state
- one current monetizable milestone
- one measurable success condition
- an up-to-date `docs/STATUS.md`
- an executable Linear backlog
- attributable runtime costs
- commercially meaningful analytics when live

If the team cannot state the current milestone in one sentence, the asset is not sufficiently groomed for active development.

## Decision hierarchy

When deciding what to work on, prefer the fastest, cheapest and most reversible action that resolves the largest commercial uncertainty.

Priority order generally follows:

1. prove someone will take the monetizable action
2. prove the product delivers the promised value
3. prove acquisition can repeat economically
4. automate repeated manual work
5. scale infrastructure only when constrained

## Documentation discipline

GitHub is the canonical institutional record. Linear may contain implementation tasks and chat may contain exploration, but durable decisions should be reflected in the relevant repository.

Minimum product-repo documentation:

- `docs/STATUS.md`
- `docs/PRODUCT.md`
- `docs/ARCHITECTURE.md`
- `docs/ROADMAP.md`
- `docs/OPERATIONS.md`

`STATUS.md` should be deliberately short and current. Historical detail belongs in version control rather than accumulating into an unreadable status document.

## Commercial instrumentation

Do not optimize generic engagement when a monetizable event exists. Instrument the funnel from qualified arrival through the revenue trigger.

Each PIGA should eventually expose enough data to understand:

- qualified traffic/users
- activation/value event
- monetization trigger
- conversion rate
- revenue
- variable cost / contribution where applicable
- acquisition source
- repeat behavior or retention where applicable

## Build-to-transfer discipline

Avoid shared dependencies that make one PIGA difficult to sell independently. Each mature asset should have isolated ownership boundaries for code, database, domain, analytics, configuration and costs wherever practical.

Third-party credentials should be documented and re-keyable. Automations should be inspectable. Business logic should not exist only inside a founder's memory or a chat transcript.

## Review cadence

Use portfolio reviews to make allocation decisions, not to create status theater. Review active assets frequently enough to catch stalled milestones; review SHELF assets only when new evidence or capacity creates a reason to reconsider them.

The governing question is always: **what evidence justifies continuing to allocate attention to this asset?**