# Third-Party Practice Quizzes

Source: 36 screenshots (uploaded 2026-07-28) of online practice-exam content for the WSET
Level 3 Award in Wines — a Brainscape flashcard deck and several unattributed "mock exam"
PDFs/quiz pages. Transcribed verbatim from the images; nothing in these files has been
invented or corrected. Where a screenshot showed no answer key, the file says so explicitly:
treat unanswered questions as review prompts, not verified content.

**These are not official WSET material.** Unlike `wset_l3wines_specification_en_highres_may2022_issue2.pdf`
and `wset_l3_sample_paper_oct2017.pdf` (the authoritative sources this repo is built around),
these are third-party study aids of unknown provenance and uneven quality.
**Cross-check anything you're unsure of against the official spec before trusting it.**

## Removed pending verification

Three questions were pulled out entirely rather than left in with a caveat, because the source
material was internally inconsistent or contradictory and neither version could be confirmed:

- `brainscape_50mcq.md`, Q12 (vine growth-cycle ordering) — question screen and answer screen in
  the source gave two different, incompatible item lists.
- `brainscape_50mcq.md`, Q46 (Chablis Grand Cru count) — source's answer key ("1") conflicts with
  the commonly taught figure (7 climats) and couldn't be confirmed either way.
- `quiz_10q_with_answers.md`, Q2 (Casablanca Valley) — source keyed one of two true statements as
  "the" correct answer with no way to tell if that was deliberate.

Each of these still has a numbered placeholder in its file explaining why it's gone, so the
numbering isn't silently broken. If you track down a reliable answer for any of them, add it back
in place rather than restoring the original unverified content.

## Files

| File | Content | Answers included? |
|---|---|---|
| `brainscape_50mcq.md` | 50 MCQs, full syllabus sweep (48 answered, 2 removed — see above) | Yes, full key minus 2 removed |
| `brainscape_short_answer.md` | 4 short-answer mini-essays (25 marks each) with full model answers: wine faults, Riesling (Alsace vs Mosel), Sauternes, traditional method sparkling production | Yes, model answers given |
| `quiz_10q_with_answers.md` | 10 MCQs, mixed topics (9 answered, 1 removed — see above) | Yes, full key minus 1 removed |
| `mock_exam_30q_no_answers.md` | 30 MCQs, single-column "WSET Level 3 Mock Exam" | **No — not captured** |
| `mock_exam_50q_two_col_no_answers.md` | MCQs 11–50 of a two-column mock exam (questions 1–10 were not in the uploaded screenshots) | **No — not captured** |
| `mock_exam_35q_no_answers.md` | 35 MCQs, two-column, plain lettering | **No — not captured** |

## Suggested use

1. Work the three answered sets (`brainscape_50mcq.md`, `brainscape_short_answer.md`,
   `quiz_10q_with_answers.md`) first — self-mark directly, log any recurring miss in
   `06_past_papers/log.md` per the usual format.
2. For the three unanswered sets, work through them and check your own answers against
   `01_foundations/`, `02_regions/`, or the official spec PDF — do not trust an answer you
   generate for these without checking. Mining a topic that keeps tripping you up into a
   proper `02_regions/` file (per `00_toolkit/region_template.md`) is more valuable than
   re-reading this raw dump.
3. If you find/recall the answer keys for the three unanswered sets later, add them in place
   rather than guessing.
