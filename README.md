# Cost Projections — Office Tools prototype

Interactive HTML prototype of the unified **Cost Projections** experience for Vista Web (Office Tools), built to walk the dev team through the designs and to demo at Dimensions 2026.

## Open it

- **No setup:** download `index.html` and double‑click it. Everything (styles, scripts, sample data) is in the one file.
- **Live link:** if GitHub Pages is enabled on this repo, the prototype is served from the Pages URL shown under *Settings → Pages*.

## What's in it

- Landing page — projections list with status, notifications and over‑budget jobs
- Draft screen — Projection Code grid and Phase/Cost Type grid in a split layout, shared Filter / Customize columns panel, unassigned phase/cost type banner with "Assign now" panel
- Projection Details page — Information, Future Change Orders, Costs, Notes
- Actions menu on the Projection Code grid — Adjust projections, Reset projection, Export to Excel

Sample data is illustrative only.

## Source of truth

The **Figma file is the source of truth**, not this prototype. If the two disagree, Figma wins.

- Designs: [Projections (Figma)](https://www.figma.com/design/cpbHaGehztJE9l4BPwOKaK/Projections)
- Design system: Modus 2.0 — colours in the prototype use Modus‑named tokens

## Scope (Phase 1)

Excludes revenue projections, projection overrides and projection layouts.

## Feedback

Open an **Issue** in this repo, or comment directly in the Figma file.

## Multiple drafts & saved views (Nov 2026) — matched to Figma
- Landing: job 101 expands (chevron) into its drafts — one light-gray group with top/bottom borders, Primary pill on the primary draft, "You" as modifier, an Open button per draft. The job row shows the Primary draft's numbers and "Open Primary".
- Projection page header: draft switcher (name ▾) → menu with each draft + "Edited X ago" + Primary badge, divider, "Duplicate this draft", "New blank draft". Primary badge or "Set as Primary" button next to the switcher, then a ⋮ menu with Rename draft / Delete draft.
- Dialogs (per Figma): Duplicate draft (name prefilled "Copy of …", Set as Primary checkbox, Cancel / Duplicate and Open), New Draft (Create and Open), Rename draft (Save Change), Delete Draft (Cancel / Delete).
- "Save as new draft" removed. "Submit for review" enabled only on the Primary draft with everything assigned; disabled otherwise with a dark tooltip: "Set this draft as Primary to submit it for review".
- View dropdown lists the four saved views (Thulsi's / Kellie's / Angeline's project views, Adam's view); switching swaps the column set on both grids.
- Demo data for returning visitors migrates automatically (drafts added on load).
