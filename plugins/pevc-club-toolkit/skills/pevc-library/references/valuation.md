# Valuation and metrics

Module 4 of the club library. Sources: *Venture Capital Valuation* (Aswath Damodaran), *Valuing Pre-revenue Companies* (eVenturing / Luis Villalobos, Tech Coast Angels), *Fundamental Startup Metrics* (Linas Beliūnas), *Pre-money vs Post-money Valuation Guide*, *Valuation Guidelines*, *How to Talk About Valuation Numbers*.

## Pre-money and post-money

`post-money = pre-money + new investment`, and the new investor's ownership is `investment ÷ post-money`.

$2m invested at an $8m pre-money gives a $10m post-money and 20% ownership. The post-money is what determines what you own — that is why the GCV checklist tells investors to make sure they understand it before anything else.

## The venture capital method (Damodaran)

The standard early-stage approach, because DCF struggles with negative earnings and no history:

1. Forecast earnings (or revenue) in the year the company could plausibly exit.
2. Apply a multiple drawn from comparable public companies to get the **exit / terminal value**.
3. Discount back to today at a **target rate of return** — historically 30%+, far above a normal cost of equity.

Worked example from the source: a software firm expected to earn $4m net income in three years, at a 25x P/E for public comparables, gives a $100m exit value. At a 30% target return, that discounts to $45.5m today.

**Two weaknesses to state out loud rather than hide:**
- The exit multiple is borrowed from *today's* pricing of comparables. If the market is mispricing them, the valuation inherits that error — Damodaran's example is internet firms valued in 2000 at 80x revenue.
- The target return is chosen by the investor and reflects an undiversified portfolio, not a market-clearing cost of capital. More diversified private equity investors can accept lower returns and will therefore pay more for the same company.

## Divergence — the number students miss

Company valuation and the investor's per-share value do **not** grow at the same rate, because later rounds dilute. The library puts typical divergence at **3x to 5x**.

Example: an investor enters at a $4m post-money with shares at $2. The company sells five years later for $60m — a 15x increase in company value. After dilution the investor's shares might be worth $6, a 3x. 15 ÷ 3 = **5x divergence**.

This is why angel return targets look inconsistent until you account for it: targeting 5–10x cash-on-cash over 4–8 years (an IRR roughly between 25% and 75%) is effectively the same as targeting ~30x before divergence. 4x divergence × 7.5x return ≈ 30x.

## Pre-revenue valuation

With no revenue there is no multiple to apply, so the approaches in the library are structural rather than arithmetic: work backwards from the return the investor needs, compare against recent rounds for similar companies at the same stage and geography, and adjust for the qualitative factors (team, product progress, market size, competitive position). The eVenturing collection includes a valuation worksheet and estimator for exactly this.

The honest framing: at pre-revenue, valuation is a negotiation about ownership and future dilution, dressed as arithmetic.

## Talking about valuation (founder side)

The library's practical advice, from a VC with a decade of experience: the founder is negotiating against someone with **asymmetric information** — the VC sees price signals across thousands of deals, the founder sees one. When asked about price expectations, in most cases do not name a number; anchor a general range instead, since the VC is in price-discovery mode and is testing whether you are in their band at all.

## Market sizing

- **TAM** — the sector's entire revenue opportunity.
- **SAM** — the portion of TAM being served / that you can serve.
- **SOM** — the portion of SAM you can realistically capture.

Sequoia's template asks for TAM top-down and SAM bottom-up. Build the bottom-up chain explicitly — buyers × incidence of the problem × what they pay today — with a source on every input.

## Metric definitions and benchmarks

Each benchmark below carries its source. Repeat the source and vintage whenever you use one; these move.

- **ARR** — recurring revenue annualised, excluding one-time fees, services and variable usage. *Growth benchmark (Bessemer, via Fundamental Startup Metrics):* top quartile 80%+, middle 50% 35–80%, bottom quartile under 35%, average ~60%.
- **GMV** — total transaction volume through a marketplace. **GMV is not revenue**; revenue is the take rate on it.
- **ARPU** — revenue ÷ users for a period. Reference points in the source: Amazon ~$752, Apple ~$194, Google ~$137, Spotify ~$64.
- **Churn** — customers lost in a month ÷ prior-month total. *Median by industry, 2022 (customergauge.com):* IT services 12%, software 14%, financial services 19%, telco 31%, consumer goods 40%, wholesale 56%.
- **LTV** = `(ARPU × gross margin) ÷ churn rate`.
- **CAC** — the full cost of acquiring a customer, per customer. The common error is omitting referral fees, credits and discounts. *By industry (FirstPageSage), organic / inorganic:* B2B SaaS $205 / $341, cybersecurity $345 / $512, e-commerce $87 / $81, financial services $644 / $1,202.
- **Burn multiple** = `net burn ÷ net new ARR`. *Scale (David Sacks):* under 1x amazing, 1–1.5x great, 1.5–2x good, 2–3x suspect, over 3x bad.
- **NPS** — "would you recommend us?" scored −100 to 100. 0–30 good, 30–70 great, 70+ excellent. *Industry averages (Satmetrix NICE):* hotels 49, brokerage 49, software and apps 41, banking 34.
- **Customer concentration** — largest customer(s) ÷ total revenue. Lower is preferred.
- **Active users** — define it explicitly, make sure it reflects real activity, and apply the definition consistently.
- **Deferred revenue** — advance payments for undelivered service; a liability, not revenue.

Go deeper: `4. Valuations/` in the club library — Damodaran's note, the pre-revenue collection with its worksheet, the valuation guidelines, and the VC Valuation Method model (.xlsx).
