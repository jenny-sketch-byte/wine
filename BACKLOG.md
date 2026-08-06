# Backlog

Tracked tasks not yet actioned, in priority order within each section.
Add new items at the top of their section.

## Priority order (across all sections)

1. Design brief re-skin — biggest visible change, but needs decisions
   first (dark mode, serif choice) and is the largest single effort

## Corrections

- ~~"Written Practice has no rubrics"~~ — **false alarm, removed
  2026-08-05.** Every `SCENARIOS` part already has a populated `model`
  field, and the app has a working "Reveal model answer" / "Reveal
  answers" UI (`web/index.html:3465-3467`, `3527-3533`). The original
  finding checked for a field called `rubric`, which never existed in
  this schema — the real field is `model`. No action needed here.

## App content — Response Builder gaps

Region notes cover 15 countries/regions (`02_regions/`). RESPONSE_BUILDERS
in `web/index.html` covers 13 as of 2026-08-05 (19 builders total: added
Burgundy × 2, Loire × 3, and New Zealand × 1 — Marlborough climate,
Wairau/Awatere sub-zone contrast, and winemaking reinforcement — this
session, on top of the earlier Chile/Argentina/fortified batches).

Regions with a written note and zero corresponding builder:

- **Northern Rhône** — has a region note, 0 builders.

No region note AND no builder yet:
- **Champagne**
- **Australia** (broader than the one Hunter Valley written-practice scenario)
- **Portugal**

## Design

- **Implement the design brief** (parchment/spine/serif re-skin). Currently
  0% implemented — none of the brief's 12 color tokens are in the app's CSS,
  and `--font-display`/`--font-body`/`--font-mono` are all the same system
  sans stack. Needs two decisions from Jenny before starting:
  - Dark mode: keep as a warm-dark variant, drop it, or leave the existing
    cool palette untouched for dark mode only.
  - Serif choice for headings: classic-bookish vs. warm-modern (brief
    defaults to a Fraunces/Newsreader register with Georgia as the safe,
    self-contained fallback — a web font would break the app's current
    zero-external-request, double-click-to-open portability).
  - Map pipeline (GeoJSON → styled SVG) is part of the same brief but is
    its own multi-step effort; can be sequenced separately once the shell
    and tokens are in place.

## Housekeeping

- **Repo is still public.** Decision to go private was made a few sessions
  ago but never executed. Note: GitHub Pages from a private repo needs a
  paid plan (Pro+) or the site goes offline.
- **`GATE_PASSWORD = "wset3"` is hardcoded and decorative** in
  `web/index.html` — fine for a private repo, but offers no real protection
  on a public one.
- **Brand-voice content in `web/index.html`** — the "Wine With Jenny" marks
  and the 5 "Jenny's notes" callouts. User chose "report only, change
  nothing yet" when this was audited; still open, still their call.
