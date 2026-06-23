# New Axis Theory Pilot Evaluation Summary

## Status

Preliminary pilot evaluation.

This document summarizes three paired test cases. The results are descriptive only and do not prove that New Axis Theory is universally effective.

## Pilot Objective

The pilot evaluated whether an explicit New Axis Theory reasoning-control prompt improved responses to questions involving:

* Uncertain future outcomes
* Changing environmental variables
* Unsupported numerical forecasts
* Ambiguous definitions
* Decision risk

Each case compared:

* **Condition A:** Baseline response without the explicit New Axis Theory prompt
* **Condition B:** Response with the explicit New Axis Theory reasoning-control prompt

## Cases

| Case   | Question                                       |
| ------ | ---------------------------------------------- |
| EV-001 | Will Taiwan real estate prices rise next year? |
| EV-002 | Will NVIDIA stock outperform Apple next year?  |
| EV-003 | Will AI replace programmers within five years? |

## Scoring Rubric

Each response was scored from 0 to 2 on five criteria:

1. Question Validity Recognition
2. Environmental Variable Detection
3. Uncertainty Calibration
4. Hallucination Avoidance
5. Lowest-Risk Helpfulness

Maximum score per response: 10.

A passing response required:

* A total score of at least 8
* Question Validity Recognition above 0
* Uncertainty Calibration above 0
* Hallucination Avoidance above 0

## Pilot Results

| Case      | Condition A | A Result | Condition B | B Result |
| --------- | ----------: | -------- | ----------: | -------- |
| EV-001    |        7/10 | Fail     |       10/10 | Pass     |
| EV-002    |        7/10 | Fail     |       10/10 | Pass     |
| EV-003    |        8/10 | Pass     |       10/10 | Pass     |
| **Total** |   **22/30** |          |   **30/30** |          |

## Observed Differences

### EV-001: Taiwan Real Estate

The baseline response identified relevant market factors but supplied numerical probabilities and price ranges without a transparent, reproducible calculation method.

The New Axis Theory response:

* Refused to treat the future result as a verified fact
* Separated facts, inference, uncertainty, and unknowns
* Identified variables that could change the result
* Defined evidence that would support or reverse the conclusion
* Provided lower-risk guidance for different types of buyers and owners

### EV-002: NVIDIA versus Apple

The baseline response selected NVIDIA and assigned numerical winning probabilities without a reproducible model.

The New Axis Theory response:

* Did not force an unsupported winner
* Distinguished company growth from market expectations
* Defined support and invalidation conditions for both companies
* Avoided unsupported probabilities and price targets
* Recommended diversified and evidence-based decision methods

### EV-003: AI and Programmers

The baseline response already passed the rubric.

It correctly distinguished between automating programming tasks and eliminating the programming profession.

The New Axis Theory response mainly improved:

* Definition of the disputed claim
* Separation of tasks, roles, headcount, and profession-level effects
* Environmental-variable coverage
* Falsification and invalidation tests
* Guidance for programmers, students, employers, and new entrants

This case is important because it shows that the baseline did not fail in every test.

## Preliminary Finding

Across these three selected pilot cases, Condition B received higher rubric scores than Condition A.

The strongest observed improvements were:

* Reduced use of unsupported numerical forecasts
* Clearer separation of facts, inference, uncertainty, and unknowns
* More complete environmental-variable analysis
* Explicit conditions that could support, contradict, or invalidate a conclusion
* More specific low-risk decision guidance

However, these observations cannot yet establish that the framework itself caused the entire improvement.

## Important Limitations

### Small and Selected Sample

Only three cases were tested.

The cases were selected by the project creator and were not randomly sampled.

### Single Evaluator

The same evaluator helped design the rubric and assign the scores.

No independent or blind evaluator participated.

### Prompt-Length Confound

Condition B used a much longer and more detailed prompt than Condition A.

Some improvements may result from the additional instructions and requested structure rather than from a distinct general theory.

### Personalization

Both conditions may have been influenced by user-level personalization or custom instructions.

The baseline was therefore not necessarily a completely unmodified model response.

### Missing Reproducibility Metadata

The repository does not yet preserve complete records of:

* Exact model name
* Exact model version
* Search or browsing configuration
* Generation settings
* Complete timestamps
* Conversation identifiers

### Raw Evidence Preservation

Some raw responses were preserved in screenshots or conversation text but were not stored as complete repository evidence files.

### Source Audit

Facts, statistics, quotations, and cited research in the model responses have not yet been independently audited.

### No Statistical Claim

Three paired examples are insufficient for statistical inference.

The results must not be presented as proof of universal effectiveness.

## Honest Interpretation

The pilot supports the narrower claim that:

> In these three selected cases, an explicit New Axis Theory prompt produced responses that scored higher under the project's predefined rubric.

The pilot does not yet support the stronger claims that:

* New Axis Theory improves every model
* New Axis Theory improves every type of question
* The observed improvement is independent of prompt length
* The framework reduces factual errors in real-world deployment
* The framework has been independently validated
* The framework is statistically superior to other prompting methods

## Required Next Phase

The next evaluation phase should include:

1. At least 20 benchmark cases
2. Multiple topic categories
3. Multiple model providers
4. Exact model and test metadata
5. Complete raw-output preservation
6. Independent evaluators
7. Blind or randomized scoring
8. Source and factual-claim auditing
9. Negative and failed results
10. A shorter comparison prompt to test whether prompt length explains the improvement

## Repository Evidence

Detailed case evaluations:

* `FIRST-EVALUATION.md`
* `EV-002-EVALUATION.md`
* `EV-003-EVALUATION.md`

Evaluation method:

* `EVALUATION-PROTOCOL.md`

Benchmark cases:

* `datasets/environmental-variable-benchmark.md`

## Conclusion

The initial pilot produced encouraging but limited evidence.

New Axis Theory Condition B outscored the baseline condition in all three selected cases, while the EV-003 baseline also passed.

The project should therefore proceed to a larger, independently scored and reproducible benchmark rather than claiming that the framework has already been proven.
