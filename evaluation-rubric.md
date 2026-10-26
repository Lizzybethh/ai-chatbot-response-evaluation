# AI Response Evaluation Rubric

Use this rubric to assess chatbot responses to small-business tasks. Score every criterion from 1 to 5 and cite specific evidence from the response or source material.

## Scale

- **1 — Poor:** materially incorrect, misleading, irrelevant, or ignores a critical requirement.
- **2 — Weak:** significant gaps; requires substantial correction before use.
- **3 — Adequate:** mostly useful, but has clear omissions or needs editing/checking.
- **4 — Strong:** accurate and useful with only minor gaps.
- **5 — Excellent:** accurate, grounded, complete for the task, clear, and ready to use with minimal edits.

## Criteria

| Criterion | Weight | Score guidance |
|---|---:|---|
| Accuracy | 20% | Correct facts, arithmetic, dates, and policy interpretation |
| Grounding in provided information | 20% | Distinguishes known facts from assumptions; does not invent details |
| Relevance to the task | 15% | Solves the stated business problem rather than giving generic advice |
| Constraint adherence | 15% | Follows policy, budget, tone, format, audience, and scope |
| Actionability | 15% | Gives concrete and feasible next steps or usable output |
| Clarity and organization | 10% | Easy to scan, logically ordered, and appropriately concise |
| Risk awareness | 5% | Avoids unsupported promises, privacy issues, and unnecessary escalation |

**Weighted score:** sum of (criterion score ÷ 5 × criterion weight). The final score is out of 100.

## Rules for consistent scoring

1. Apply the same criteria to every response for the same prompt.
2. Evaluate only what the response actually says; do not award credit for intent.
3. Treat unsupported claims as grounding failures even when they sound plausible.
4. Verify calculations independently.
5. Do not penalize a response for refusing to invent information; appropriate uncertainty can be a strength.
6. Explain low scores with a specific example and a practical correction.
7. Record the exact prompt and full output when conducting a real evaluation.
8. If two evaluators disagree, compare evidence and clarify the scoring anchor before changing a score.

## Decision guide

- **90–100:** strong candidate; verify any business-critical details before use.
- **75–89:** useful with targeted edits or checks.
- **60–74:** needs substantial revision.
- **Below 60:** not suitable for use without rewriting.

A high average must not hide a critical failure. A response that invents a refund promise, exposes sensitive data, or gives materially wrong financial figures should be flagged separately even if its other scores are high.
