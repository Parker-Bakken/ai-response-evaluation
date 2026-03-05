# Example 09 — Missing information prompt

## Prompt
Summarize the following article in three sentences.

(No article provided)

## Candidate Response A
Please provide the article text or link so I can summarize it accurately.

## Candidate Response B
This article discusses several topics and provides useful insights.

## Scoring
| Category | A | B | Evidence |
|---|---:|---:|---|
| Intent & Instruction Following | 5 | 0 | B invents content |
| Helpfulness & Completeness | 4 | 1 | A asks for necessary input |
| Factuality & Grounding | 5 | 0 | B hallucination |
| Clarity & Structure | 5 | 3 | A direct request |
| Safety & Policy Awareness | 5 | 5 | No safety issue |
| Efficiency | 5 | 3 | A concise |
| **Total** | **29** | **12** | |

## Winner
A — Strong Accept

## Improvements for B
- Ask for missing information
- Avoid guessing content
