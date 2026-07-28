# WSET Level 3 Award in Wines: Study & Practice Repo

Structured revision notes and an interactive practice site for the WSET Level 3 Award in
Wines theory exam, built around the official Specification.

## How this repo is organized

```
00_toolkit/          Command words, sentence templates, vocab, question patterns,
                      exam scope, the reverse-engineering framework
01_foundations/       Climate, viticulture, winemaking, oak: the reusable building blocks
02_regions/           One file per region, consistent template
03_sparkling/         Method comparison, dosage, Champagne
04_fortified/         Port, Sherry, Madeira, VDN
05_business/          Supply chain, pricing, distribution
06_past_papers/       Official WSET Specification + sample paper, plus practice material
                      (06_past_papers/third_party_quizzes/: unofficial practice MCQs/mini-essays,
                      quality varies — see that folder's README before trusting an answer)
07_training_video/    Script for a "how to answer" technique training video
web/                  Interactive study + practice site (written practice, mock exam,
                      multiple-choice drills, matching games), open web/index.html
```

## The master lens: reverse-engineering

Before studying any new region, read `00_toolkit/reverse_engineering_framework.md`. The
core idea: climate/altitude sets the ceiling, soil modifies within it, everything else
(grape choice, viticulture, style) follows logically. Master this chain and you can
construct a plausible answer for a region you have never specifically studied, which is
what the exam is actually testing. `00_toolkit/question_patterns.md` catalogs the real
question archetypes and mark logic, built directly from the sample paper in
`06_past_papers/`.

## Method for each new topic
1. Cover the content using the region/topic template (`00_toolkit/region_template.md`)
2. Save the file in the right folder
3. Write a 4–5 sentence practice answer using a sentence template
4. Log it in `06_past_papers/log.md`

## Region priority order (marks-weighted)
1. France: Bordeaux, Burgundy, Rhône, Loire, Alsace, Champagne
2. Italy: Piedmont, Tuscany, Veneto
3. Spain: Rioja, Sherry
4. Germany
5. USA: California, Washington/Oregon
6. Australia / New Zealand
7. Other: Portugal, South America, South Africa

## Exam material on file
- Official WSET Level 3 Award in Wines Specification, Issue 2, May 2022
  (`06_past_papers/wset_l3wines_specification_en_highres_may2022_issue2.pdf`): the syllabus,
  ranges, exam structure, mark weighting and grading thresholds. The authoritative source;
  everything else here is cross-checked against it. Scope and weighting are summarised in
  `00_toolkit/exam_scope.md`.
- WSET Level 3 Sample Short Written Answer Paper, Oct 2017 (`06_past_papers/wset_l3_sample_paper_oct2017.pdf`)
- Full mock theory exam: 50 MCQs + 4 written questions with model answers
  (`06_past_papers/mock_exam_full_theory_qa.pdf`)
- Reverse-engineering framework and question-pattern taxonomy, built from those papers
  (`00_toolkit/`)
- Video training script: command words, marks logic (`07_training_video/script.md`)
- Third-party practice quizzes, consolidated from screenshots
  (`06_past_papers/third_party_quizzes/`): 165 MCQs across 5 sources plus 4 short-answer
  mini-essays. Only 2 of the 5 MCQ sets came with an answer key (57 questions); the other
  3 sets (105 questions) are unanswered and flagged as such. 3 questions with internally
  inconsistent or unconfirmable source answers were removed rather than kept with a caveat
  (see that folder's README). This material is unofficial and is not cross-checked to the
  same standard as the Specification.

## Core exam facts
- Grading: Pass 55–64% | Merit 65–79% | Distinction 80%+ *and* no individual paper below 65%
- Theory: 2 hours total. Part 1 = 50 MCQ (1 mark each). Part 2 = 4 written questions ×
  25 marks. **55% is required in each part separately**, not on the combined average.
- MCQ weighting by Learning Outcome: LO1 (vineyard/winery factors) 8 · LO2 (still wine regions) 28 ·
  LO3 (sparkling) 5 · LO4 (fortified) 5 · LO5 (service/recommendations) 4 — LO2 dominates
- Written weighting: LO2 70 marks · LO3+LO4 20 marks · LO5 10 marks (LO1 runs through all four questions)
- Tasting (Unit 2): 2 wines blind, 30 minutes, SAT structure, 55% pass mark, assessed separately
- The written section is where most marks are lost: practice writing, not just reading
