# Cap tables and early-stage instruments

Module 6 of the club library. Sources: *Cap Tables — from Formation to Exit* (Capdesk; UK-centred, with European references), *SAFEs vs. Convertible Notes vs. Priced Equity* (Dror Futter, Rimon PC, 2024, using Carta's *State of Pre-Seed Q1 2024* data).

> Explained as concepts for study. Structuring a real round needs a lawyer.

## What a cap table is, and why broken ones cost money

The cap table is the register of who owns what: share classes, rights, options and the arithmetic of ownership at each round. The Capdesk guide's blunt framing is that companies routinely discover errors in shareholder registers or employee share plans only at an acquisition, when it is too late and the cost runs to millions.

It tracks the company from **formation** (share capital, classes and rights, articles, the first issuance) through **seed**, **employee equity**, **convertible instruments**, **Series A** and later rounds, to **exit**.

## The two decisions at the early stage

**Decision 1 — priced equity or a convertible instrument?**
**Decision 2 — if convertible, SAFE or convertible note?**

### Priced equity
A real valuation is set and shares are issued now. Documents: stock purchase agreement, certificate of incorporation, investor rights agreement, voting agreement, co-sale / right of first refusal. Slower and more expensive, but it settles ownership and control.

### SAFE (Simple Agreement for Future Equity)
One document, no interest, no maturity date. Terms: **discount**, **conversion cap**, pre-money or post-money, pro-rata rights, most-favoured-nation. Standard forms from Y Combinator — the original forms were pre-money, the current ones post-money.

### Convertible note
A debt instrument that converts. Same discount and cap as a SAFE, plus an **interest rate**, a **maturity date**, and what happens at maturity (convert or repay). Usually a note purchase agreement alongside the note.

### How conversion actually works
A $10m round prices shares at $1. A $500k SAFE or note converts:

| Terms | Shares received | Effective price |
|---|---|---|
| No discount, no cap | 500,000 | $1.00 |
| 20% discount | 625,000 | $0.80 |
| $5m cap | 1,000,000 | $0.50 |

The cap does the heavy lifting. At a $5m cap against a $10m round, the early investor pays half price.

### Which is better?
Futter's answer: in theory SAFEs are more founder-friendly than notes; in practice, if a note does not stay outstanding long, it is a distinction without much difference. **The real gap is convertible instrument vs priced equity.**

- *Advantages of converting instruments:* fast, cheap.
- *Disadvantages for investors:* possibly inadequate reward for early risk, minimal representations and warranties, no control.
- *Disadvantage for founders:* full-ratchet anti-dilution above the cap.

### What the market actually does (Carta, Q1 2024)
SAFEs dominate pre-seed. SAFEs are overwhelmingly **post-money**; convertible notes are more likely **pre-money**. You will probably need a cap. The typical discount is **20%**. In convertible notes, cap-plus-discount is the common combination, and interest rates are material again.

## The two shuffles

**Option pool shuffle.** The new investor asks for an option pool to be created or enlarged. Where it sits in the arithmetic decides who pays for it:
- *Investor-friendly:* the pool comes out of the **pre-money**, so existing shareholders absorb all the dilution.
- *Founder-friendly:* the pool is created **post-money**, so the new investor shares it.
The headline valuation can look identical while the effective price differs — this is the single most common way a quoted pre-money overstates what founders keep.

**Convertible note shuffle.** The same question for converting notes at a priced round: whether the converting shares are counted inside the pre-money (investor-friendly) or outside it (founder-friendly).

## Employee equity

- **Stock options** — the right to buy shares at a set price, usually vesting over time with a cliff.
- **Warrants** — similar instrument, typically for non-employees.
- **Phantom shares** — a cash payout that tracks share value, no actual equity.

The practical decision is the equity/cash split: how much salary a company trades for how much ownership, and whether the employee can bear that trade.

## At the exit

- **M&A** — the common outcome; proceeds are distributed through the waterfall, which is where liquidation preferences decide who actually sees money.
- **IPO** — rarer, and preferences usually convert to common on listing.

The reason to build the cap table properly from day one is this moment: the waterfall is computed from it.

Go deeper: `6. Capital Structuring/` in the club library — the full Capdesk guide (chapter by chapter from formation to exit) and the Futter deck, which includes the Carta data charts.
