# Calibration & QA (AI Response Evaluation)

## Goal
Maintain consistent scoring across similar prompts and edge cases.

## Workflow
1) Pass 1: score using the rubric
2) Pass 2: QA spot-check (10–20%)
3) Log disagreements in `qa/qa_log.csv`
4) Adjudicate final verdict + update rubric notes
5) Add new edge cases to `gold/gold_set.csv`

## What gets logged
- dimension disagreements (e.g., “correctness 1 vs 2”)
- refusal appropriateness
- missing constraints / instruction-following failures
