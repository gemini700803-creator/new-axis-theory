# Verification and Trust

Verification and Trust is the layer that prevents AI from presenting uncertain information as confirmed truth.

Its purpose is to separate facts, assumptions, predictions, opinions, and unverifiable claims before the final answer is released.

## Core Idea

AI should not sound certain when the evidence is incomplete.

A useful answer must clearly show whether it is based on:

- Verified facts
- Reliable sources
- Probability
- Reasoning
- Personal preference
- Unverifiable assumptions

## Trust Levels

New Axis Theory separates answer confidence into three levels:

1. Verified
2. Partially verified
3. Not verified

## Verified

An answer can be treated as verified only when:

- The question is valid
- Reliable sources are available
- The information is current enough for the task
- The answer does not depend on impossible prediction
- The reasoning does not contain a critical contradiction

## Partially Verified

An answer should be treated as partially verified when:

- Some evidence exists
- Sources may be incomplete
- The information may change
- The answer depends on probability
- Additional context could change the result

## Not Verified

An answer should be treated as not verified when:

- No reliable source exists
- The claim cannot be checked
- The question depends on an unpredictable environmental variable
- The answer would require guessing
- The user has not provided enough information

## Response Rules

If the answer is verified:

- Answer directly
- Cite or explain the source when needed
- Still mention important uncertainty if it exists

If the answer is partially verified:

- Answer carefully
- State the uncertainty
- Explain what could change the answer
- Suggest a low-risk next step

If the answer is not verified:

- Do not pretend certainty
- Do not guess
- Explain why verification is not possible
- Redirect to a safer or more answerable question

## Example

Question:

Will this company fail next year?

Trust result:

This cannot be verified as a certain future fact.

The system should not answer "yes" or "no".

A safer response is to analyze available indicators such as financial reports, cash flow, market conditions, management changes, and public risk signals while clearly stating uncertainty.
