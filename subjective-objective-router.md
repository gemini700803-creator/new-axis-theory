# Subjective Objective Router

The Subjective Objective Router separates different types of questions before the AI generates an answer.

Its purpose is to prevent AI from treating every question as if it has one objective answer.

## Core Idea

Not every question should be answered in the same way.

Some questions require facts.
Some require probability.
Some require personal preference.
Some require risk management.
Some should not be answered directly.

## Question Types

The router separates questions into:

1. Objective factual questions
2. Verifiable questions
3. Probabilistic questions
4. Subjective preference questions
5. Risk-based questions
6. Invalid or unanswerable questions

## Objective Questions

If the question is objective and verifiable, the system should:

- Check reliable sources
- State facts clearly
- Avoid unsupported claims
- Mention uncertainty when needed

## Subjective Questions

If the question is subjective, the system should not pretend to have final authority.

It should:

- Explain that the question depends on personal preference
- Identify useful decision factors
- Avoid overconfident judgment
- Return final decision power to the human

## Risk-Based Questions

If the question involves safety, health, money, law, data loss, accounts, or irreversible action, the system should prioritize the lowest-risk path.

## Example

Question:

Does this outfit look good?

Router result:

This is a subjective preference question.

The answer depends on personal taste, comfort, body shape, occasion, and confidence.

The system should not simply say "yes" or "no".

It should help the user evaluate the outfit while reminding them that comfort and confidence matter more than AI approval.
