# WSET Level 3: 2-Week Prep Repo

Personal study repo. Built topic-by-topic in conversation with Claude, then saved here.
Goal: pass efficiently as a non-native English speaker, with strong written-answer technique.

## How this repo is organized

```
00_toolkit/          Command words, sentence templates, vocab, question patterns,
                      the reverse-engineering framework: use these EVERY session
01_foundations/       Climate, viticulture, winemaking, oak: the reusable building blocks
02_regions/           One file per region, consistent template
03_sparkling/         Method comparison, dosage, Champagne
04_fortified/         Port, Sherry, Madeira, VDN
05_business/          Supply chain, pricing, distribution
06_past_papers/       Real WSET sample paper + practice answers/self-marking notes
                      (06_past_papers/third_party_quizzes/: unofficial practice MCQs/mini-essays,
                      quality varies — see that folder's README before trusting an answer)
07_training_video/    Script for a "how to answer" technique training video
web/                  Wine With Jenny: interactive study + practice site (written
                      practice, multiple-choice drills, matching games), open web/index.html
```

## The master lens: reverse-engineering

Before studying any new region, read `00_toolkit/reverse_engineering_framework.md`. The
core idea: climate/altitude sets the ceiling, soil modifies within it, everything else
(grape choice, viticulture, style) follows logically. Master this chain and you can
construct a plausible answer for a region you've never specifically studied: which is
what the exam is actually testing. `00_toolkit/question_patterns.md` catalogs the real
question archetypes and mark logic, built directly from the sample paper in
`06_past_papers/`.

## The rule for every new topic
1. Cover content with Claude using the region/topic template (see `00_toolkit/region_template.md`)
2. Save the file in the right folder
3. Write a 4–5 sentence practice answer using a sentence template
4. Log it in `06_past_papers/log.md`

## 2-Week Plan (tracker)

| Days | Focus | Status |
|---|---|---|
| 1–3 | Foundations: climate, viticulture, winemaking, oak | ⬜ |
| 4–10 | Regions, priority order: France → Italy → Spain → Germany → USA → Australia/NZ → other | ⬜ |
| 11–12 | Sparkling + Fortified | ⬜ |
| 13–14 | Past papers, timed, weakest region review | ⬜ |

## Region priority order (marks-weighted)
1. France: Bordeaux, Burgundy, Rhône, Loire, Alsace, Champagne
2. Italy: Piedmont, Tuscany, Veneto
3. Spain: Rioja, Sherry
4. Germany
5. USA: California, Washington/Oregon
6. Australia / New Zealand
7. Other: Portugal, South America, South Africa

## Topics covered so far
- [x] Sediment/deposits vocab (`00_toolkit/vocab.md`)
- [x] Argentina: irrigation (`02_regions/other/argentina.md`)
- [x] Alsace: climate + sweetness range (`02_regions/france/alsace.md`)
- [x] Foundations: climate (`01_foundations/climate.md`)
- [x] Foundations: viticulture (`01_foundations/viticulture.md`)
- [x] Foundations: winemaking (`01_foundations/winemaking.md`)
- [x] Foundations: oak (`01_foundations/oak.md`)
- [x] Bordeaux: Left/Right Bank soils & grapes (`02_regions/france/bordeaux.md`)
- [x] Burgundy: appellation hierarchy & terroir fragmentation (`02_regions/france/burgundy.md`)
- [x] Southern Rhône: blending rationale, GSM (`02_regions/france/southern_rhone.md`)
- [x] Germany: Prädikatswein ladder, Eiswein (`02_regions/other/germany.md`)
- [x] Hungary (Tokaj): Aszú, noble rot, Eszencia (`02_regions/other/hungary.md`)
- [x] Practical/service knowledge: storage, decanting (`web/index.html`, Service & Storage topic)
- [x] Sparkling wine: traditional method, autolysis, sweetening methods (`web/index.html`, Sparkling Wine topic)
- [x] Fortified wine: fortification timing, Sherry, Port, Muscat contrast (`web/index.html`, Fortified Wine topic)
- [ ] Loire, Champagne: remaining France priority regions
- [ ] Italy, Spain (Rioja, Sherry detail), USA, Australia/NZ, other remaining regions
- [ ] Business (05): supply chain, pricing, distribution

## Real exam material on file
- [x] Official WSET Level 3 Award in Wines Specification, Issue 2, May 2022 (`06_past_papers/wset_l3wines_specification_en_highres_may2022_issue2.pdf`): the actual syllabus, ranges, exam structure, mark weighting, and grading thresholds. The authoritative source; everything else here is cross-checked against it.
- [x] WSET Level 3 Sample Short Written Answer Paper, Oct 2017 (`06_past_papers/wset_l3_sample_paper_oct2017.pdf`)
- [x] Full mock theory exam: 50 MCQs + 4 written questions with model answers (`06_past_papers/mock_exam_full_theory_qa.pdf`): source for the Tokaji, German Prädikatswein/Eiswein, Chardonnay MLF, sparkling, fortified, and Vintage Port content now in `web/index.html`
- [x] Reverse-engineering framework, built from that paper (`00_toolkit/reverse_engineering_framework.md`)
- [x] Question-pattern taxonomy + mark logic, built from that paper (`00_toolkit/question_patterns.md`)
- [x] Video training script: command words, marks logic, Golden Thread technique (`07_training_video/script.md`)
- [x] Third-party practice quizzes, consolidated from 36 screenshots, 2026-07-28 (`06_past_papers/third_party_quizzes/`):
  165 MCQs total across 5 sources + 4 short-answer mini-essays with model answers. Only 2 of the
  5 MCQ sets came with an answer key (57 verified-as-transcribed questions); 3 sets (105 questions)
  are unanswered and flagged as such — work them, then verify your own answers, don't trust a
  guess. 3 questions with internally inconsistent or unconfirmable source answers were removed
  outright rather than kept with a caveat (see that folder's README).

## Core exam facts to keep in view
- Verified against the official WSET Level 3 Award in Wines Specification, Issue 2, May 2022 (`06_past_papers/`)
- Grading: Pass 55–64% | Merit 65–79% | Distinction 80%+ *and* no individual paper below 65%
- Theory: 2 hours total. Part 1 = 50 MCQ (1 mark each, 55% pass mark on this part alone).
  Part 2 = 4 written questions × 25 marks (55% pass mark on this part alone, separate from Part 1)
- MCQ weighting by Learning Outcome: LO1 (vineyard/winery factors) 8 · LO2 (still wine regions) 28 ·
  LO3 (sparkling) 5 · LO4 (fortified) 5 · LO5 (service/recommendations) 4 — LO2 dominates
- Written weighting: LO2 70 marks · LO3+LO4 20 marks · LO5 10 marks (LO1 runs through all four questions)
- Tasting: 2 wines blind, 30 minutes, SAT structure, 55% pass mark
- Written section is where most marks are lost: practice writing, not just reading
