# ReRev Tapestry Tool

A strategic planning tool for solo founders. Three interactive layers: time allocation across ventures, ICP fit grid for service lines, and revenue mix tracking toward monthly goals.

Built for ReRev Labs by Keyona Meeks.

## What this is

The Tapestry Tool is a single-page HTML app that lives on GitHub Pages and runs entirely in the browser. No backend, no auth, no setup. It stores state in localStorage so your configuration persists across sessions.

Three sections:

**The week.** Drag sliders to allocate 40 hours across your active ventures. A horizontal bar renders the allocation as a visual tapestry, colored by venture. Over-allocation and under-allocation are flagged in real time.

**The ICP fit grid.** Four target audiences across the top (marketing agencies, fractional execs, boutique advisory, interim leaders). Seven service lines down the side. Click any cell to cycle through fit scores: Not pitching, Weak, Possible, Strong, Strongest. Use this to pressure-test outreach strategy before committing lead budget.

**The revenue mix.** Drag sliders to model the path to the monthly $28K goal. Anchor client, one-off projects, Tapestry sessions, content subscriptions. Shows monthly total, gap to goal, and percentage achieved.

## Using it

Open `https://keyona-rerev.github.io/rerev-tapestry-tool` (once deployed to GitHub Pages).

- **Save** writes the current state to localStorage
- **Load** restores the most recently saved state
- **Reset** restores the default configuration
- **Export** downloads the current state as a JSON file for archival or sharing

## Deploying

This is a static single-file app. Deploy to GitHub Pages:

1. Push this repo to `keyona-rerev/rerev-tapestry-tool`
2. In repo settings, enable GitHub Pages from the main branch root
3. Wait a minute, then visit `https://keyona-rerev.github.io/rerev-tapestry-tool`

## Updating it

Edit `index.html` directly. All state defaults, service lines, audiences, and colors are declared at the top of the embedded script. Change them and push.

If you add new service lines or audiences, remember to update the DEFAULT_GRID array to match the new dimensions.

## File layout

```
rerev-tapestry-tool/
  index.html          Single-file app
  README.md           This file
  methodology.md      The thinking behind the tool
  data/
    default-state.json  Starting configuration
  CHANGELOG.md        Version history
```

## Versioning

Current version: v1.0. See CHANGELOG.md for history.

## Tool Registry

Registered in the ReRev Tool Registry under:
- Name: Tapestry Tool
- Owner: ReRev Labs
- Type: Strategic planning tool
- Status: Active
