# vidIQ Validation

## Scope and limitation

The authenticated vidIQ connection was used for keyword clusters and faceless-channel discovery. Its numbers are **point-in-time directional metrics**, not guaranteed monthly traffic or a substitute for YouTube Analytics. The connection did not provide a public query-result URL, so the exact figures are preserved as connector evidence and labeled `[Vxx]` in the [source log](SOURCE_LOG.md).

## Keyword-cluster result

The winning thesis is not “rank for one keyword.” It is a channel built around a buyer’s sequence of questions.

| Buyer job | Connected query example | Est. monthly search | Competition | Overall |
|---|---|---:|---:|---:|
| Decide whether to buy an EV | ev buying guide | 5,061 | 17.5 | 66.18 |
| Decide whether to buy used | buying used ev | 4,779 | 22.2 | 64.07 |
| Evaluate a popular used model | used tesla buying guide | 3,408 | 21.5 | 63.04 |
| Verify the highest-cost component | tesla battery health check | 4,305 | 13.0 | 67.35 |
| Understand age-related risk | tesla battery degradation | 4,801 | 23.1 | 63.73 |
| Understand cross-brand risk | ev battery degradation | 3,718 | 24.0 | 62.38 |
| Browse category inventory | used ev | 6,742 | 39.1 | 58.65 |

**Interpretation:** The cluster contains enough mid-volume, moderate-to-low-competition questions to support model-specific episodes, while broader “used EV” and vehicle-model demand can expand reach. [V01]

## Channel-pattern result

vidIQ’s channel search was filtered for English, active and faceless channels. It surfaced two useful patterns.

### Pattern A — broad automotive ownership files work without a host

- **Japanese Motors** — connected snapshot: 24.4K subscribers, 2.76M views, 32 videos, roughly 86K average views.
- **Everything Lexus** — 9.82K subscribers, 1.08M views, 48 videos, roughly 22.4K average views.
- **Everything Hyundai** — 4.53K subscribers, 659K views, 68 videos; connected snapshot showed 20.8% subscriber growth over 30 days.
- **Everything Subaru** — 26.7K subscribers, 2.37M views, 67 videos, roughly 35.4K average views.
- **Everything Toyota** — 33.4K subscribers, 3.77M views, 99 videos.

These channels demonstrate an asset-based “what to buy / what to avoid / how to own” format. They do **not** prove that every such channel will succeed. Their strongest lesson is packaging: a narrow ownership promise can create a coherent subscriber audience.

### Pattern B — EV channels exist, but most are news, enthusiast or repair-led

- **Auto Gear Shift** — 30.2K subscribers, 3.43M views, 479 videos; EV news/battery technology.
- **Gary C EV Repairs** — 10.1K subscribers, 1.1M views, 176 videos; specialist diagnostics and repair.
- **CarLandTV** — 64.1K subscribers, 9.29M views, 948 videos; broad SUV/EV reviews and rankings.
- **DIY500AMP** — 3.21K subscribers, 336K views; batteries and DIY power.

**Inference:** The space is validated but fragmented. A used-EV-only buyer channel with a fixed evidence scorecard is more focused than broad car rankings and safer/more scalable than hands-on high-voltage repair.

## Format opportunity

The connected examples suggest that faceless automotive channels can succeed when each episode has a different substantive subject. That aligns with YouTube’s policy: a consistent format is acceptable when the substance materially varies, while mass-produced or minimally varied templates are not. [S05]

The proposed format deliberately changes the underlying research in every episode:

- VIN/model-year recall set
- battery chemistry and thermal-management design
- vehicle-specific warranty language
- compatible charging standards and curve
- listing-price and mileage sample
- insurance quote inputs supplied by the viewer
- common owner complaints, verified through primary documents where available
- final risk score and conditional verdict

## Competitive gap statement

The gap is **not** “no one makes used-EV videos.” The API evidence disproves that. The gap is:

> No dominant faceless channel in the connected sample owns the repeatable promise of turning public records, battery evidence, warranty language, charging fit and ownership math into an auditable used-EV buying verdict.

That is an inference, not a claim of exhaustive platform coverage.

## Recommended search architecture

Use four layers rather than keyword stuffing:

1. **Problem-first:** “How to check a used EV battery,” “Can I own an EV without home charging?”
2. **Model-first:** “Used Tesla Model 3 buyer guide,” followed by year/trim updates.
3. **Risk-first:** “Battery warranty fine print,” “The dashboard range myth,” “VIN recall audit.”
4. **Decision-first:** “Buy, wait or walk,” “Best fit for apartment charging,” “The total-cost test.”

Every title should promise a decision or avoided mistake. Keywords support the promise; they do not replace it.

## Metrics to refresh after launch

vidIQ metrics should be refreshed monthly and compared with actual channel data:

- impressions by topic family
- search terms reported in YouTube Analytics
- click-through rate by thumbnail archetype
- average percentage viewed
- subscribers per 1,000 views
- returning viewers
- comments containing a purchase deadline or specific model request

Actual channel behavior outranks third-party estimates after the first videos publish.