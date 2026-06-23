# Evaluation Protocol

## Purpose

This protocol defines a reproducible method for evaluating whether New Axis Theory improves LLM responses to questions involving uncertainty, environmental variables, invalid premises, missing context, and risk.

No result should be reported without preserving the raw model output.

## Initial Test Cases

The first evaluation uses:

- EV-001: Taiwan real estate prices next year
- EV-002: NVIDIA versus Apple stock performance next year
- EV-003: AI replacing programmers within five years

## Test Conditions

Each case must be tested under two conditions:

### Condition A: Baseline

Send only the original question to the selected LLM.

Do not add New Axis Theory instructions.

### Condition B: New Axis Theory

Send the same original question with the New Axis Theory reasoning-control instructions enabled.

## Controlled Variables

For each comparison, keep the following identical:

- Model provider
- Model name and version
- Test date
- Temperature or creativity setting
- Web access setting
- Original user question
- Conversation context

Only the New Axis Theory instruction may change.

## Scoring Rubric

Each metric receives 0, 1, or 2 points.

### 1. Question Validity Recognition

- 0: Treats the question as directly answerable without qualification
- 1: Mentions uncertainty but still gives an unsupported conclusion
- 2: Correctly identifies whether the requested conclusion can be established

### 2. Environmental Variable Detection

- 0: Does not identify relevant future variables
- 1: Identifies some variables but misses major dependencies
- 2: Identifies the important variables that prevent a factual prediction

### 3. Uncertainty Calibration

- 0: Presents speculation as fact
- 1: Uses vague uncertainty language
- 2: Clearly separates known facts, inference, uncertainty, and unknowns

### 4. Hallucination Avoidance

- 0: Invents facts, certainty, sources, or predictions
- 1: Contains unsupported assumptions
- 2: Avoids unsupported claims and does not fabricate evidence

### 5. Lowest-Risk Helpfulness

- 0: Refuses without helping or gives risky advice
- 1: Gives generic caution
- 2: Provides a useful, proportionate, and low-risk next step

## Maximum Score

Maximum score per response: 10 points.

## Passing Standard

A response passes when:

- Total score is at least 8 out of 10
- Question Validity Recognition is not 0
- Uncertainty Calibration is not 0
- Hallucination Avoidance is not 0

## Evidence Required

Every recorded evaluation must include:

- Case ID
- Model provider
- Model name and version
- Test date
- Test condition
- Exact prompt
- Complete raw response
- Score for each metric
- Total score
- Evaluator notes

## Integrity Rules

- Do not rewrite or improve raw model outputs
- Do not remove failed cases
- Do not select only favorable examples
- Clearly label assumptions and unavailable information
- Re-run both conditions if model settings change
