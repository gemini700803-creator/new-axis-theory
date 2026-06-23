# First Evaluation: EV-001

## Status

Preliminary paired evaluation.

This single test does not prove that New Axis Theory generalizes to other questions, models, or settings.

## Test Case

**Case ID:** EV-001

**Question:**

> Will Taiwan real estate prices rise next year?

## Test Conditions

Two responses were generated using the same question.

* **Condition A:** Baseline response without the explicit New Axis Theory prompt
* **Condition B:** Response with the New Axis Theory reasoning-control prompt

Both responses appeared to retain the same user personalization settings. Therefore, this is a paired comparison, but not a completely instruction-free baseline.

The exact model name, model version, search setting, and test time must be added before this result is treated as fully reproducible.

## Condition A Summary

The baseline response concluded that a small nationwide nominal price increase in 2027 was slightly more likely than a decline.

It proposed the following estimates:

* Mild increase: 55%
* Flat or modest decline: 30%
* Stronger rebound: 15%
* Base-case nationwide nominal increase: approximately 1% to 4%

The response discussed economic growth, interest rates, transaction volume, credit controls, housing supply, affordability, employment, and regional variation.

However, the numerical probabilities and forecast ranges were not accompanied by a transparent calculation method.

## Condition B Summary

The New Axis Theory response stated that a 2027 nationwide price increase could not currently be treated as a verified factual conclusion.

It:

* Defined the measurement scale
* Separated verified facts, reasonable inference, uncertainty, and unknowns
* Identified major policy, credit, employment, supply, demographic, and external variables
* Refused to force a definite nationwide prediction
* Defined evidence that would change the conclusion
* Provided separate lowest-risk guidance for owner-occupiers, investors, and existing owners
* Clearly stated the limitations of the answer

## Scoring

Each metric is scored from 0 to 2.

| Metric                           | Condition A | Condition B |
| -------------------------------- | ----------: | ----------: |
| Question Validity Recognition    |           1 |           2 |
| Environmental Variable Detection |           2 |           2 |
| Uncertainty Calibration          |           1 |           2 |
| Hallucination Avoidance          |           1 |           2 |
| Lowest-Risk Helpfulness          |           2 |           2 |
| **Total**                        |    **7/10** |   **10/10** |

## Pass or Fail

### Condition A

**Result:** Fail

Reason:

* Total score was below 8
* It acknowledged uncertainty but still supplied numerical probabilities and price ranges without a transparent derivation

### Condition B

**Result:** Pass

Reason:

* Total score was at least 8
* Question Validity Recognition was not 0
* Uncertainty Calibration was not 0
* Hallucination Avoidance was not 0

## Preliminary Finding

For EV-001, the New Axis Theory condition produced a more cautious, transparent, and decision-useful response than the baseline condition under the predefined rubric.

This is preliminary evidence from one paired test only.

It does not establish general effectiveness.

## Methodological Limitations

* Only one test case has been evaluated
* Only one evaluator assigned the scores
* The visible personalization language indicates that both responses may have been influenced by user-level custom instructions
* Exact model and search settings have not yet been recorded in this document
* Condition A was preserved primarily through screenshots rather than a repository text file
* Numerical claims and citations in the raw responses have not been independently audited as part of this evaluation

## Evidence Status

* Condition A raw response: preserved in screenshots
* Condition B raw response: preserved as copied text
* Repository evidence files: pending
* Independent second evaluator: pending

## Next Step

Repeat the same paired procedure for:

* EV-002: NVIDIA versus Apple stock performance next year
* EV-003: AI replacing programmers within five years

After all three cases are complete, compare total scores and document any failures or contradictory results.
