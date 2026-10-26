# Case Study: Responding to a Delayed-Order Complaint

**Scenario type:** Customer interaction  
**Business:** Fictional small online shop, Cedar & Coast  
**Purpose:** Demonstrate how to evaluate whether an AI-generated customer reply follows policy and uses only confirmed facts.

## 1. Business context supplied to the chatbot

- A customer says their order is four days later than the estimated delivery date.
- The tracking page has not updated for two days.
- The store's policy allows the support team to investigate delayed shipments.
- Refunds or replacements may be considered only after the carrier investigation, according to the store's policy.
- The business has not confirmed the parcel is lost.
- The reply should be empathetic, concise, and avoid promising a delivery date.

## 2. Evaluation prompt

> You are helping Cedar & Coast draft a reply to a customer whose order is four days late and whose tracking has not updated for two days. Acknowledge the inconvenience, explain that the support team will investigate with the carrier, and tell the customer what information or next step to expect. Do not claim the parcel is lost, promise a delivery date, or guarantee a refund or replacement. Keep the message under 120 words and use a warm, professional tone.

## 3. Response patterns to look for

These are **illustrative examples**, not transcripts from a live chatbot comparison.

### Response A — Policy-aligned

> Hi there,  
> I'm sorry your order hasn't arrived when expected, and I understand how frustrating it is to see no recent tracking updates. We'll contact the carrier to investigate the delay and will update you as soon as we have more information. You don't need to place another order while we look into this. Thank you for your patience, and please reply here if your delivery details have changed.

### Response B — Unsupported promise

> We're sorry! Your parcel will arrive tomorrow. If it doesn't, we'll automatically issue a full refund and send a replacement.

### Response C — Too vague

> Sorry about that. Shipping delays happen sometimes. Please keep checking your tracking page.

## 4. Illustrative evaluation

| Criterion | Response A | Response B | Response C |
|---|---:|---:|---:|
| Accuracy | 5 | 1 | 3 |
| Grounding | 5 | 1 | 3 |
| Relevance | 5 | 3 | 2 |
| Constraint adherence | 5 | 1 | 3 |
| Actionability | 4 | 2 | 1 |
| Clarity | 5 | 4 | 4 |
| Risk awareness | 5 | 1 | 3 |
| **Weighted score / 100** | **97** | **32** | **54** |

Scores are illustrative and use the rubric in this repository. The weighted score uses the criterion weights; rounding may affect totals slightly.

## 5. Findings

- **Response A** acknowledges the issue, states a realistic next step, and avoids claiming facts that have not been confirmed. Before use, the business should confirm it can commit to the stated update process and that the line about not placing another order is appropriate.
- **Response B** invents a delivery date and guarantees a refund and replacement that the supplied policy does not authorize. These are critical failures even though the tone is friendly.
- **Response C** avoids making a false promise but offers no meaningful investigation or expectation-setting. It places the burden on the customer and does not satisfy the requested next step.

## 6. Recommended evaluation notes format

For each response, record:
- **Evidence:** exact phrase or claim being evaluated.
- **Issue:** factual error, unsupported assumption, omission, or constraint violation.
- **Business impact:** confusion, lost trust, cost, policy inconsistency, or avoidable follow-up.
- **Correction:** a specific revision that resolves the issue.

## 7. Limitations

This is a controlled teaching example using fictional business information and constructed response patterns. It is not evidence of performance by any particular chatbot or a real customer-service deployment. A live evaluation should capture actual outputs and independently verify every score.
