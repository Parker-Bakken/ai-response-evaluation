# AI Response Evaluation & Grading

Framework + worked examples for evaluating AI assistant responses for:
- instruction following / intent match
- helpfulness & completeness
- factuality / hallucination risk
- safety & refusal quality
- clarity and formatting

## Quick start
1) Read the rubric: `rubric/rubric.md`
2) Use the template: `templates/evaluation-template.md`
3) Review examples: `examples/`
4) See calibration & QA: `calibration.md` + `qa/qa_log.csv`
5) Use gold set for consistency checks: `gold/gold_set.csv`

## Repo structure
- `rubric/` — evaluation rubric + scoring guidance
- `templates/` — copy/paste templates for new evals
- `examples/` — worked comparisons + verdicts
- `qa/` — QA logs for double-pass consistency
- `gold/` — adjudicated “correct label” examples

## How I score (short)
- Score each dimension
- Write a short rationale
- If borderline: mark as “needs adjudication” and log it in QA
