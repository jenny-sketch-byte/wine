# Backlog

Tracked tasks not yet actioned, in priority order within each section.
Add new items at the top of their section.

## Priority order (across all sections)

1. Written Practice rubrics — repairs a feature that's currently broken
   (see "Broken functionality" below)
2. Burgundy + Loire Response Builder exercises — biggest content gaps
   (5 and 3 topics in the app with zero practice)
3. New Zealand Response Builder exercise — already scoped
4. Design brief re-skin — biggest visible change, but needs decisions
   first (dark mode, serif choice) and is the largest single effort

## Broken functionality

- **Written Practice has no rubrics.** All 9 parts across the 4 SCENARIOS
  entries (Bordeaux Right Bank; Southern Rhône; Hunter Valley, Australia;
  Pinot Noir: two climates — Los Carneros/Central Otago) are missing
  `rubric`. The app's own code comment says answers are "scored by
  self-marking," but there's currently nothing to self-mark against — the
  user writes an answer and gets no model answer or mark scheme. Fix: add a
  rubric (or model answer + mark breakdown, matching the Response Builder's
  step-by-step style) to each part.

## App content — Response Builder gaps

Region notes now cover 15 countries/regions (`02_regions/`), but
RESPONSE_BUILDERS in `web/index.html` only covers 8. Regions with a written
note and zero corresponding builder:

- **Burgundy** — 5 topics in the app's TOPICS list, 0 builders. Biggest gap.
- **Loire** — 3 topics, 0 builders.
- **Northern Rhône** — has a region note, 0 builders.
- **New Zealand** — note added 2026-08-04. Candidate angle: Marlborough
  climate + winemaking → Sauvignon Blanc style (mirrors the Mosel/California
  pattern already in the app: natural factor, then winery/technique
  reinforcement).

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
