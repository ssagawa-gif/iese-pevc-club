# Market sizing and operating benchmarks

For Blocks 4 (market consequence), 5 (behavior change), 6 (business model) and 11 (investable companies).
Distilled from the club library; benchmark figures carry their source and vintage so they can be re-checked.

## TAM, SAM, SOM — and why bottom-up wins

- **TAM** — the sector's entire revenue opportunity.
- **SAM** — the share of TAM the product can actually serve (geography, segment, channel).
- **SOM** — the share of SAM this company can realistically capture.

Sequoia's own deck template asks for TAM top-down **and** SAM bottom-up. A thesis that only states a top-down TAM ("the market is $50bn") has not done the work. Rebuild it:

```
number of buyers in the segment
  × share that have the problem acutely
  × what they already spend on the alternative (or would plausibly pay)
  = annual revenue opportunity
```

Every input gets a source and a date. Where no source exists, mark `[LACUNA]` and keep the chain visible so a reader can substitute their own number.

Three questions that break a weak sizing:
1. **Whose budget does this come out of?** A new category still gets paid from an existing line item. Name it.
2. **Is this a new market or a margin transfer?** Taking 20 points of margin from an incumbent is a real opportunity, but it is a different thesis with different winners.
3. **Does the category have an edge?** What is in, what is out, who the adjacent incumbent is.

## Operating benchmarks worth citing

Use these as reference points, and always restate the source and vintage when you put one in a document.

**Growth (SaaS ARR growth, Bessemer data as reported in the library's *Fundamental Startup Metrics*):** top quartile 80%+; middle 50% between 35% and 80%; bottom quartile under 35%; average around 60%.

**Burn efficiency (Burn Multiple = net burn ÷ net new ARR, David Sacks' scale):** under 1x amazing, 1–1.5x great, 1.5–2x good, 2–3x suspect, over 3x bad.

**Churn (median customer churn by industry, 2022, customergauge.com):** IT services ~12%, software ~14%, financial services ~19%, telco ~31%, consumer goods ~40%. Churn is the denominator of LTV, so a category with structurally high churn caps the business model argument in Block 6.

**Unit economics identities:**
- `LTV = (ARPU × gross margin) ÷ churn rate`
- `Burn multiple = net burn ÷ net new ARR`
- CAC must include *everything* — referral fees, credits, discounts — or it is not CAC.

**CAC by industry (FirstPageSage, organic vs inorganic):** B2B SaaS ~$205 / ~$341; cybersecurity ~$345 / ~$512; e-commerce ~$87 / ~$81; financial services ~$644 / ~$1,202. Useful as an order-of-magnitude check on a claimed go-to-market, not as a target.

**Other metrics the library treats as standard:** GMV (and the reminder that GMV ≠ revenue — revenue is the take), ARPU, NPS (0–30 good, 30–70 great, 70+ excellent), customer concentration (largest customer ÷ total revenue; low is preferred), and a clearly stated definition of "active user".

## Defensibility, checked against the metrics

Network effects are the moat the library treats as most durable for software: the product gets more valuable as more people use it, which lifts engagement and margin. The test is mechanism, not assertion — *why* does it compound, and *when* does it start working? Most moats are absent at seed.

For AI companies specifically, the library's framework argues models are commoditising and the durable asset is the **dataset**. Judge it on five dimensions — veracity, variety, volume, velocity, value — and on one question that decides defensibility: *how long would it take and how much would it cost a competitor to collect the same data?* "We have proprietary data" with no answer to that is a claim, not a moat.

## Stage reference (US patterns, Flybridge/HBS, 2021 — check against current market before citing)

| Stage | Raise | Post-money | Instrument |
|---|---|---|---|
| Pre-seed | $250–500k | $5–7m cap | SAFE / convertible note |
| Seed | $1–3m | $8–15m | Note, SAFE or priced |
| Series A | $5–10m | $20–50m | Priced, board seat |
| Series B | $20–40m | $80–200m | Priced, control terms |

These numbers move with the cycle. Treat them as the shape of the ladder, not as today's prices — search for current figures before putting any of them in a thesis.
