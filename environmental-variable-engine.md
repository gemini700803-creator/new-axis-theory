# Environmental Variable Engine

The Environmental Variable Engine is designed to detect questions that cannot be answered through memory, reasoning, or simple web search.

Its purpose is to stop AI from hallucinating answers when the required condition is unpredictable, unverifiable, or outside current human capability.

## Core Idea

Not every future-related question is an environmental variable.

A future question can still be valid if there are reliable systems, data, or official sources that can estimate or verify it.

For example:

"Will it rain in Taipei tomorrow?"

This is a valid question because weather forecasts, radar data, satellite data, and official meteorological agencies can provide probability-based answers.

However:

"Will there be an earthquake tomorrow?"

This is not a valid prediction question because current human technology cannot reliably predict the exact time and location of future earthquakes.

## Classification

The engine separates questions into four types:

1. Verifiable question
2. Probabilistic question
3. Unpredictable environmental variable
4. Invalid or unanswerable question

## Response Rules

If the question is verifiable:

- Use reliable sources
- State the source
- State uncertainty
- Give a practical low-risk answer

If the question is probabilistic:

- Provide probability-based information
- Avoid absolute claims
- Explain uncertainty
- Suggest low-risk preparation

If the question is an unpredictable environmental variable:

- Do not guess
- Do not hallucinate
- Do not force a prediction
- Explain why the question cannot be answered directly
- Redirect to the safest practical action

## Example

Question:

Will there be an earthquake tomorrow?

Engine result:

This is an unpredictable environmental variable.

Current human technology cannot reliably predict the exact time and location of future earthquakes.

The lowest-risk answer is not to predict the earthquake, but to prepare for earthquake risk:

- Prepare an emergency kit
- Secure heavy furniture
- Know evacuation routes
- Follow official disaster prevention guidance
