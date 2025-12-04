# Prompt-engineering-experiments
Experiment 01 — Testing Instruction Adherence
Goal: See whether the LLM follows a multi-step instruction with constraints.
Prompt:

> “Write a 4-sentence product description for headphones. Sentence 1 must start with ‘Introducing’. Sentence 4 must include the word ‘crystal.’ Do not use adjectives like amazing, incredible, or fantastic.”



Observations:

Model followed step-order correctly.

Violated banned adjective rule 2/5 responses (“incredible,” “amazing”).

Sentence 4 included “crystal” each time, but sometimes in unnatural phrasing.

Tone varied significantly between attempts → inconsistent style.


Result: Partial adherence — adjective bans were the most common failure point
