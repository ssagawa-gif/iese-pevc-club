# Venture math

Why a thesis has to clear a return bar, and how to check that it does.
Distilled from the club library (see `catalog.md` in the `pevc-library` skill for the source files).

## The fund structure that creates the bar

- LPs (pension funds, family offices, endowments) commit capital; GPs manage it. VC is typically a small slice (low single-digit %) of an LP's portfolio — the riskiest slice, expected to pay for its risk.
- "2 and 20": roughly 2% a year in management fee, 20% carry on profits above a hurdle (commonly stated around 7–8% IRR). GPs usually commit 1–2% of fund size themselves.
- Fees come out of the fund. A $100m fund paying 2% for 10 years has ~$80m actually to invest. Returning $100m of *capital* is not breaking even once the LP's opportunity cost is counted.
- Commitment (investing) period ~5 years; fund life ~10 years with extensions. Reserves for follow-ons are set aside at the start.

## Power law, stated plainly

Returns are not spread evenly. In a typical fund of 45–50 investments, only 1–2 companies return the whole fund, and only 6–8 produce a fund-level return. A worked example from the library: 10 investments at $8m each, 25% held at exit, against a target of roughly $310m — ten $50m exits return $125m, nowhere near. Five at $50m and five at $100m returns $187.5m, still short. The target is only cleared when one outcome is very large.

**What this means for a thesis:** a category where the best plausible outcome is a $300m exit can hold good businesses and still fail as a venture thesis. Say so when it is true instead of inflating the exit.

## The ownership arithmetic — do it out loud

The chain is: entry valuation → ownership → dilution → exit value → proceeds.

Worked example from the library: $2m invested at $8m pre-money = $10m post, so 20% ownership. A 5x return on $2m needs $10m of proceeds, which at 20% means a $50m exit. The same 5x on a $20m investment needs a $500m exit. **The bigger the check, the bigger the exit has to be** — this is why a thesis has to name the check size it is arguing for.

Two other numbers to keep honest:
- **Dilution / divergence.** Company value and the investor's per-share value do not grow at the same rate. The library puts typical divergence at 3–5x: a company whose valuation grows 15x may only grow an early investor's share value ~3x. An angel targeting 5–10x cash-on-cash over 4–8 years is roughly equivalent to targeting ~30x before divergence.
- **Time to cash.** For US fund vintages 2000–2015, upper-quartile funds took at least 8 years to reach 1.0x DPI (returning cost in cash); median funds at least 9.5 years, with extreme vintages far longer. Paper marks (TVPI, RVPI) are not distributions. A "Why now" argument that only pays off in year 12 is a different proposition from one that pays off in year 6 — name which one it is.

## The VC valuation method (Damodaran)

Forecast earnings or revenue in a future exit year → apply a multiple from comparable public companies → that is the exit value → discount back at a target return (historically 30%+, far above a normal cost of equity).

Its two known weaknesses, which a thesis should acknowledge rather than hide:
1. The exit multiple comes from how comparables are priced *today*. If today's market is wrong, the valuation inherits that error.
2. The target return is set by the investor, not by the market, and encodes undiversified risk.

## Fund-level metrics, in one line each

- **MOIC** — multiple on invested capital; raw picking skill.
- **TVPI** — total value (realized + paper) over paid-in capital. "TVPI" unqualified usually means net.
- **DPI** — cash actually distributed over paid-in. The one that matters at the end.
- **RVPI** — the paper half. Impressive early, meaningless unless it converts to DPI.
- **IRR** — time-weighted return; gross vs net differ a lot, so always say which.

## How to use this in a thesis

- **Block 13 (Return potential):** do the arithmetic in the open — entry price, ownership, dilution, exit value, proceeds. Name the comparable exits and cite them.
- **Block 12 (Timing):** connect the entry point to the time-to-liquidity above. Being three years early costs IRR even when the thesis is right.
- **Block 7 (Winner characteristics):** the winner has to be the kind of company that reaches the exit size the math demands.
