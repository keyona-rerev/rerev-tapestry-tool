# Methodology

The thinking behind the Tapestry Tool. This doc exists so future-Keyona (or anyone else using the tool) understands why the three sections exist, what they're testing, and how to read the output honestly.

## The three layers

### 1. The week

The hours section enforces the non-negotiable truth: a week is 40 hours. Everything else is fiction. If the allocation sums to 43, something has to give. If it sums to 36, there are 4 unclaimed hours and they need a name.

The ventures shown by default are the six active streams: BTC, Prismm (anchor), Super Connector product dev, ReRev pipeline, ReRev content, and new client delivery. These change as the business evolves. Add or remove streams by editing the defaults in `index.html`.

The bar visualization matters more than the numbers. Numbers let you rationalize. A horizontal bar showing that Prismm plus BTC already eat 25 of 40 hours makes it impossible to pretend there's infinite capacity for new pipeline work.

### 2. The ICP fit grid

Fit is not the same as likelihood-to-buy. The grid answers: "if this audience engaged, would this service line be a credible offering for them?" It does not answer: "will this audience engage?" That's what the outreach blitz tests.

The grid has five states, not three, because nuance matters:

- **Not pitching** — deliberately off the table, either because fit is wrong or because you've decided to deprioritize the cell for strategic reasons. Distinct from Weak.
- **Weak** — real mismatch. Don't pitch.
- **Possible** — fit exists but isn't strong. Use only as a secondary offer, never as the lead.
- **Strong** — credible lead offer, will get considered.
- **Strongest** — primary lead offer, where signal and service align tightly.

The rule: every pitch leads with a Strongest cell. If no Strongest cell exists for an audience, rethink the audience.

### 3. The revenue mix

The $28K monthly target isn't arbitrary. It's 2.8x the post-raise anchor ($5,000) and represents the threshold where ReRev becomes a sustainable solo business rather than a side motion to BTC.

The four revenue lines encode the current strategic bet:

- **Anchor** is stable recurring. The base.
- **One-off projects** is the primary growth lever right now. Where the outreach blitz lands.
- **Tapestry sessions** is a new productized offering. Kept separate so you can see when it starts contributing.
- **Content / subscriptions** is a future line. Zero now. The question is when to start counting on it.

The goal gap metric forces honesty about where the revenue is actually coming from. You can't hit $28K with a $2,500 anchor and $5,000 in projects. The slider math makes that immediate.

## Signal-driven targeting

The ICP grid shows four audiences, but the real targeting philosophy is signal-based, not industry-based. Each audience column should be thought of as "an audience where I can detect operational moments that trigger outreach-worthy pain."

Operational moments currently tracked:
- Interim CEO or ED announcements
- New COO roles created
- Chief of Staff hired into founder-led companies
- Post-acquisition integration leads
- New CEO in first 100 days
- Bridge rounds raised (efficiency pressure)
- Key ops person departures without backfill
- Fractional CFO or COO engagements announced

The tool doesn't track these moments directly. That happens in the Super Connector and the outreach infrastructure. The grid is where you decide which moments, applied to which audience, earn which service-line pitch.

## How to use it strategically

**Weekly.** Open the tool Monday morning. Check last week's saved state against what actually happened. Adjust the hour allocation to match reality, not aspiration. Save the new state.

**When a new opportunity appears.** Before saying yes, add the hours it would consume to the correct bucket. Watch whether another bucket has to shrink. If nothing can shrink, the answer is no.

**Before a blitz.** Update the ICP grid with current scoring. Identify the Strongest cells. Those are the lead offerings. Everything else is noise.

**Monthly.** Update the revenue mix with actuals. Compare to the previous month's state. The gap metric tells you whether the trajectory is real.

## What it's not

This is not a CRM, not a project management tool, not a time tracker. Those systems exist elsewhere (Super Connector for relationships, Prismm sequence review for outreach, T018 for meeting follow-ups, Debbie for daily digests). The Tapestry Tool is a strategic pressure test that sits above those systems.

## Future iterations

Planned extensions:
- Per-ICP sub-views that show which cells of the grid are actively in a blitz
- Historical state tracking (compare April to March)
- A Martha-style productized version for other solo founders and consultants
- Export to PNG for client sessions
