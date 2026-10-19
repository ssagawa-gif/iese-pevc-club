# Term sheets and investment memos

Module 5 of the club library. Sources: *Preparing a Venture Capital Term Sheet* (Morgan, Lewis & Bockius), *Investment Memo Template* (Y Combinator), Bessemer's 2009 Twilio seed memo, the Shopify and YouTube memos, *Sequoia Pitch Deck Template*, *Questions VCs Ask Founders Before Investing*, *VC's Framework for Evaluating an AI Startup's Tech Stack*.

> Term sheet mechanics below are explained as concepts for study. A live negotiation needs a lawyer.

## The term sheet

Its purpose is to agree the shape of the deal before anyone spends money on documentation. It is normally **non-binding** except for specific clauses (confidentiality, exclusivity, expenses) — and the Morgan Lewis guide spends its first section on making sure that non-binding status is unambiguous, because ambiguity here has cost people deals.

Terms group into three families.

**1. Economics — who gets what**
- Type of security (almost always preferred stock)
- Amount of investment and capitalisation
- Price per share
- Dividends
- **Liquidation preference** — who gets paid first on an exit, and how much before common shares see anything
- Redemption / repurchase rights
- Reimbursement of investor expenses
- **Founder share vesting**
- Employee stock options and **option pool increase** (see the option pool shuffle in `cap-structure.md` — this one moves real value)

**2. Control — who decides what**
- Voting rights
- **Protective provisions** — the list of corporate acts that need investor consent
- **Board composition**
- Matters requiring investor-director approval
- Non-compete and non-solicit

**3. Investor protections**
- **Anti-dilution** — what happens if a later round prices lower
- Mandatory conversion
- Representations, warranties, closing conditions
- Use of proceeds
- Registration rights, management rights, information rights
- Pre-emptive (pro rata) rights
- **Pay-to-play** — follow on or lose your preference
- Confidentiality and invention assignment
- D&O and key-man insurance
- Right of first refusal and co-sale
- **Drag-along**

The NVCA groups the same ground as general investor protections, venture general protections, investor control, return enhancements and downside protection. Model documents: NVCA for priced rounds, Y Combinator for SAFEs.

## What a real investment memo does

The Twilio seed memo (Bessemer, November 2009, $125k into an $800k seed extension) is the best teaching artefact in the library. Four habits to copy:

1. **The recommendation comes first** — amount, structure and co-investors in the opening paragraph, before any argument.
2. **Weak numbers are stated plainly** — "growth has not been explosive… about $20k of MRR 9 months after launch". No hiding.
3. **Evidence is separated from hope** — three marquee logos are named as *leading indicators*, followed immediately by an admission that the firm has not yet verified whether these are real commitments or trials.
4. **Gaps are named** — "we haven't dug deep enough into the market dynamics to get comfort around what percentage of the pie will be addressable".

It also uses concrete unit economics rather than adjectives: 0.6 cents cost per minute against ~3 cents charged, 56% blended gross margin. And it is explicit about what the next cheque is buying — in this case, time to observe whether three named accounts convert.

## The YC memo skeleton

**Introduction** (a paragraph each): what do you do · what problem · how the world works now · how you solve it · how solving it changes behaviour and makes money · scale of the opportunity.
**Traction / metrics**: traction with a chart, churn, ACV, rake, revenue drivers, go-to-market.
**Challenges to growth**: what has stopped you growing faster, and how the money fixes it.
**Market**: who the customers are, how they think, how big they are.
**Future states**: what happens to the market as you win, and where that leads the company.
**Competitive landscape**: who you are up against and how you beat them.
**Team**: who you are and what makes you special.
**FAQ**: surface the main objections and knock them down with data — YC's own note is that this is where a memo beats a deck.
**Use of funds**: raised before, raising now, what for.

## Sequoia's deck order

Company purpose (one declarative sentence) · problem · solution · **why now** · market size (TAM top-down, SAM bottom-up, SOM) · competition · product · business model (revenue model, pricing, account size / LTV, sales and distribution, pipeline) · team · financials (P&L, balance sheet, cash flow, cap table, the deal).

"Why now" sits fourth — before market size — because size only matters if the timing holds.

## The 15 questions founders get asked

Great management team · big market opportunity · early traction and how it accelerates · passionate, determined founders · founders who understand their own financials and metrics · warm referral · professional pitch deck · risks and mitigations · why the product is great · how the capital gets used and what it buys · realistic valuation expectations · differentiated technology · intellectual property · realistic projections with defensible assumptions · clean legal formation.

## Diligencing an AI company

The library's framework argues that models are commoditising and the durable asset is the **dataset**. Judge data on four qualities — relevance, accuracy, coverage, bias — then the **five V's**: veracity, variety, volume, velocity, value.

The question that decides defensibility: **how long would it take, and how much would it cost, a competitor to collect the same data?** Supporting questions: is capture automated so it scales; are pipelines automated with quality controls; are data and model versions tracked; is there a real data governance strategy; is there evidence predictions improve as data accumulates?

Go deeper: `5. Term Sheets & Investment Memos/` in the club library — the full Morgan Lewis guide with a sample term sheet in its appendix, the HSBC and SVB term sheet guides, and the three real memos.
