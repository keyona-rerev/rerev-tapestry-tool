# Changelog

## v3.0 — 2026-04-18

Measure tab added. The feedback loop.

- New Measure tab with round-based tracking
- Each round has its own targets and actuals per ICP per metric (replies, calls, proposals, closed, revenue)
- Round pills let you switch between rounds, add new rounds, rename rounds
- New rounds default targets to the previous round's targets
- Round totals with color-coded percentage (green ≥80%, amber ≥40%, red below)
- Refactor signals checklist with 8 prebuilt diagnostic signals
- Auto-warning when 3 or more refactor signals are flagged
- Execution tab gets an Output defined checklist showing ICP row completion state
- "Execution complete" banner with handoff to Measure when all four ICP rows are populated

## v2.0 — 2026-04-18

Execution mode added.

- Two-tab layout: Offer Alignment (original) and Execution (new)
- Execution tab: per-ICP cells for Sub-landing page URL, Email template (subject + body), Contacts (name, title, org, signal), and Cowork brief
- Cells light up green when populated
- Click any cell to open an inline editor panel
- Copy buttons on email and brief panels for fast paste to external tools
- State now persists the execution data alongside alignment data
- Backward-compatible load from v1 saved state

## v1.0 — 2026-04-18

Initial release.

- Three-section layout: the week, the ICP fit grid, the revenue mix
- Six default venture streams: BTC, Prismm, Super Connector dev, ReRev pipeline, ReRev content, new client delivery
- Four default target audiences: marketing agencies, fractional execs, boutique advisory, interim leaders
- Seven service lines: Claude-native automation, Gmail outreach infra, GAS systems, content automation, workshop delivery, custom CRM builds, AI consulting / advisory
- Five-level scoring: Not pitching, Weak, Possible, Strong, Strongest
- Revenue mix with $28K monthly goal and four revenue lines
- localStorage persistence with Save, Load, Reset, Export
- Light and dark mode support
- Responsive layout for mobile
