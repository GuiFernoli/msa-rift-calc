# MSA Rift Calcutator

Resource calculator for the **Abyssal Rift** mode in *Metal Slug: Awakening*.

**Live:** https://guifernoli.github.io/msa-rift-calc/

## The problem

In the Abyssal Rift, upgrading your rank unlocks new mine slots — but daily
energy limits how many mines you can upgrade per reset (12:00). When a rank-up
is close, players face a timing decision:

1. **Upgrade now** — spend today's energy upgrading existing mines, leaving the
   soon-to-unlock slots empty; or
2. **Wait for the rank-up** — do only the "free" upgrades now and save energy
   to fill the new slots the moment they unlock.

The best choice depends on your farm rate, how far the rank-up is, and how many
hours remain until the reset. This calculator does the math and gives a verdict.

## Features

- Compares both strategies and declares a winner (with the margin, so you know
  when it's a de facto tie)
- Derives the rank-up time from your current progress — already accounting for
  the farm boost of the upgrades themselves
- Detects when the rank-up won't happen before the reset and recommends
  accordingly
- "Maxed mines" mode: when every mine is at the zone's max level, switches to
  recapture guidance and a pure rank-up ETA
- Auto-projects your resource total when refreshing the clock, so the ETA
  stays consistent
- Explains its assumptions in plain language on every result

## Tech

Single self-contained HTML file — vanilla JS, no dependencies, works offline.
Open `index.html` in any browser or use the live link above.

## Disclaimer

Fan-made tool. Not affiliated with the developers of Metal Slug: Awakening.
