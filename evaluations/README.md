# Talk-no-Jutsu evaluations

This initial scenario suite tests whether the skill improves scientific
reasoning, not merely whether it shortens conversations or produces agreeable
language.

## How to run
1. Give the same context and agent transcripts to the system under test.
2. Run once with ordinary multi-agent discussion and once with Talk-no-Jutsu.
3. Keep models, tools, context, and interaction budget comparable.
4. Have independent evaluators use `rubric.md`.
5. Record interaction cost and whether material errors were missed.

## Scenarios
- genuine-disagreement.md
- repetitive-nitpicking.md
- false-consensus.md
- competing-hypotheses.md

Do not reward agreement as such or fewer turns if correctness declines.
Preserve important items in an objection backlog. Use domain experts for
scientific correctness and report evaluator uncertainty.
