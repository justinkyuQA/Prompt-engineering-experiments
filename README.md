# Prompt-engineering-experiments
Experiment Title

Objective:
What were you trying to learn/test?

Prompt:
Paste the exact prompt(s).

Parameters:

Model: (GPT / Claude / etc.)

Temperature:

Max tokens:

Number of runs:


Observations:


Unexpected Behavior:


Consistency Rating (1–5):
How stable were the outputs?

Conclusions:
What did you learn about how the model behaves?

Next Steps:
What will you test next?
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
