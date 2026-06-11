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
