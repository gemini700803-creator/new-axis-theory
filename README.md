# New Axis Theory

New Axis Theory is a risk-first AI reasoning framework.

It is designed to help AI systems avoid answering invalid, unverifiable, high-risk, or misleading questions too quickly.

The core idea is simple:

AI should not answer every question immediately.

It should first check whether the question is valid, verifiable, answerable, and safe to answer.

## Core Principles

1. Check whether the question exists as a valid problem.
2. Check whether the question can be verified.
3. Detect environmental variables that cannot be predicted.
4. Separate subjective, objective, factual, and risk-based questions.
5. Route each question into the correct reasoning path.
6. Prevent AI from hallucinating answers to invalid questions.
7. Return the lowest-risk answer when the question is valid.
8. Return decision power back to the human when the question is subjective.

## Example

Question:

Will there be an earthquake tomorrow?

New Axis Theory response:

This question cannot be answered as a factual prediction because current human technology cannot reliably predict the exact time and location of future earthquakes.

The safer answer is to prepare for earthquake risk:
- Prepare an emergency kit.
- Secure heavy furniture.
- Know evacuation routes.
- Follow official disaster prevention information.

## Goal

The goal of this project is not to build a bigger AI model.

The goal is to build a reasoning control layer that helps AI decide:

- Should this question be answered?
- Can this question be verified?
- What risks exist if the answer is wrong?
- What is the lowest-risk response?

- ## Benchmark Files

- [Environmental Variable Seed Dataset](datasets/environmental-variable-seed.md)
- [Golden 100 Benchmark Plan](datasets/golden-100-plan.md)

- ## Evaluation Evidence

The project includes a preliminary paired evaluation of New Axis Theory against baseline LLM responses.

### Evaluation Method

* [Evaluation Protocol](EVALUATION-PROTOCOL.md)
* [Environmental Variable Benchmark](datasets/environmental-variable-benchmark.md)

### Pilot Results

* [Pilot Evaluation Summary](PILOT-SUMMARY.md)
* [EV-001: Taiwan Real Estate](FIRST-EVALUATION.md)
* [EV-002: NVIDIA versus Apple](EV-002-EVALUATION.md)
* [EV-003: AI and Programmers](EV-003-EVALUATION.md)

### Current Pilot Scores

| Case      |  Baseline | New Axis Theory |
| --------- | --------: | --------------: |
| EV-001    |      7/10 |           10/10 |
| EV-002    |      7/10 |           10/10 |
| EV-003    |      8/10 |           10/10 |
| **Total** | **22/30** |       **30/30** |

These results are preliminary and descriptive. They do not prove universal effectiveness. The next phase requires a larger benchmark, complete raw-output preservation, multiple models, independent evaluators, and blind scoring.


## Examples

See practical examples here:

[Examples](./examples.md)
