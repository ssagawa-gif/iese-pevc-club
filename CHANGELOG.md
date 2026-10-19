# Changelog

Format: `## <version> — <date>`, one line per change. Bump the version in
`plugins/pevc-club-toolkit/.claude-plugin/plugin.json` on every release.

## 0.2.0 — 2026-10-19

- **New skill: PE/VC Library.** A reference desk over the club's teaching material — VC fundamentals, sourcing and diligence, valuation, term sheets and memos, cap tables and SAFEs, portfolio and exits, private equity, and VC career prep. Nine reference files, including a catalogue of the club's original PDFs so students can be pointed to the source.
- **Investment Thesis Coach now writes in plain language.** New "Write so it can be read" section: one idea per sentence, short paragraphs, concrete over abstract, VC terms kept but glossed once, a plain-word substitution list, and a worked before/after. The published page now opens with a jargon-free summary. Applies to the conversation as well as the document.
- **Club library bundled into the coach** as three reference files: `venture-math.md` (fund economics, power law, ownership-to-exit arithmetic, dilution and divergence, time to DPI), `market-sizing.md` (bottom-up TAM, operating benchmarks with sources, defensibility and the AI data-moat test), `memo-and-evidence.md` (what a real memo does, the YC skeleton, how investors actually decide, risk taxonomy).
- The old empty "Course library" placeholder is gone, replaced by the real material.

## 0.1.1 — 2026-09-13

- All plugin-facing text switched to English (plugin description, marketplace entry, READMEs).

## 0.1.0 — 2026-09-13

- First release of the **Investment Thesis Coach**.
- 14 blocks, each with its question, a description of what a 5 looks like, and stress tests.
- Zero-invention rule: source + URL + data vintage, or a visible `[LACUNA]`.
- Ten VC lenses mapped onto specific blocks (USV, Sequoia, Accel, Bessemer, a16z,
  Founders Fund, Index, First Round, Lightspeed, General Catalyst).
- Score gate: a block below 3 does not pass.
- Final deliverable as a published page with six required visuals and a 400-word memo.
