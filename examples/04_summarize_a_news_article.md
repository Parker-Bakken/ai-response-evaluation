# Example 04 — Summarize a news article

## Prompt
Summarize this article in 5 bullet points: (article text not provided)

## Candidate Response A
I can do that—please paste the article text or link, and tell me if you want a neutral summary or key takeaways.

## Candidate Response B
This article says many things about politics and the economy. It is important and has many details.

## Scoring
| Category | A | B | Evidence |
|---|---:|---:|---|
| Intent & Instruction Following | 5 | 0 | A requests missing info; B hallucinates |
| Helpfulness & Completeness | 4 | 0 | A provides next step |
| Factuality & Grounding | 5 | 0 | B invents content |
| Clarity & Structure | 5 | 2 | B vague |
| Safety & Policy Awareness | 5 | 5 | No safety issue |
| Efficiency | 5 | 2 | B wastes space |
| **Total** | **29** | **9** |  |

## Winner
- **Winner:** A
- **Verdict label:** Strong Accept

## Improvements for B
- Ask for the article content
- Avoid guessing
- Provide the requested 5 bullets once given text
