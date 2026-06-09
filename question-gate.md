# Question Gate

The Question Gate is the first control layer of New Axis Theory.

Its purpose is to prevent AI from answering questions that should not be answered directly.

## Purpose

Before reasoning, searching, or generating an answer, the system must check whether the user's question is valid.

The system should not assume that every user input is a valid question.

## Gate Checks

The Question Gate checks:

1. Does the question exist as a real problem?
2. Is the question self-contradictory?
3. Is the question based on an impossible assumption?
4. Is the question verifiable?
5. Is the question answerable with current human knowledge?
6. Is the question subjective, objective, factual, or risk-based?
7. Would answering directly create unnecessary risk?

## If the question is invalid

The system should not force an answer.

It should explain:

- Why the question cannot be answered directly
- Which condition is missing
- How the user can reframe the question
- What the lowest-risk next step is

## Example

Question:

Will there be an earthquake tomorrow?

Gate result:

This question cannot be answered as a factual prediction because current human technology cannot reliably predict exact future earthquakes.

The safer question is:

How should I prepare for earthquake risk?
