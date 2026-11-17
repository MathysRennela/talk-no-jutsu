# Talk-no-Jutsu

**Turn disagreement into scientific progress.**

Talk-no-Jutsu is a framework-independent agent skill and multi-agent
collaboration protocol for scientific research. It helps agents reconstruct
one another's reasoning, diagnose disagreements, prioritize consequential
objections, prevent repetitive criticism, and turn unresolved questions into
experiments or explicit uncertainty.

It is not a consensus engine. It must preserve legitimate dissent and
prioritize scientific accuracy over agreement.

## Why this exists
Multi-agent systems can generate useful independent perspectives, but they
can also get stuck in cycles of criticism. Talk-no-Jutsu provides a shared
protocol for deciding which objections matter, what would resolve them, and
when to move forward.

## Core capabilities
- Perspective reconstruction.
- Disagreement diagnosis.
- Objection triage and backlog management.
- Synthesis, discriminating experiments, or preserved dissent.
- Explicit anti-nitpicking.
- Progress enforcement and auditable next steps.

## Architecture
Talk-no-Jutsu is a **protocol, not a required extra agent**. Any participant
can initiate and temporarily coordinate a round. No participant gains
authority over scientific conclusions merely by initiating the protocol.

Default objection policy: dynamically prioritize up to three objections
per round, maintain a backlog, and never cap genuinely critical issues.

## Quick start
Make `SKILL.md` available in the skills directory recognized by your agent
framework. Invoke it when material disagreement or repetitive criticism
obstructs research.

Example:
> Invoke Talk-no-Jutsu. We have competing conclusions about this result and
> the review is repeating objections. Reconstruct each position, map the
> disagreements, triage objections, and recommend a synthesis, discriminating
> experiment, or preserved disagreement. Do not force consensus.

## Installation
Clone the repository:
```bash
git clone https://github.com/MathysRennela/talk-no-jutsu.git
```
Expose the repository directory or copy `SKILL.md` into your framework's
skill directory. Common project-local locations include:
- Claude Code: `.claude/skills/talk-no-jutsu/SKILL.md`
- OpenCode: `.opencode/skills/talk-no-jutsu/SKILL.md`
- Codex: `.agents/skills/talk-no-jutsu/SKILL.md`

Check your framework's documentation for current discovery behavior.

## Repository map
See `references/` for protocol details, `examples/` for walkthroughs,
and `evaluations/` for initial test cases and scoring rubric.

## Evaluation
The suite evaluates scientific correctness, perspective fidelity, objection
prioritization, anti-nitpicking, reconciliation quality, uncertainty
calibration, actionability, and efficiency. Fewer turns are not a success if
correctness declines.

## Contributing
Contributions are welcome: anonymized stagnation examples, new evaluation
scenarios, objection taxonomy improvements, framework installation notes,
and empirical comparisons against ordinary multi-agent debate.

Do not submit confidential or identifying research conversations. Anonymize
scenarios and explain scientifically responsible expected outcomes.

## License
MIT. See [LICENSE](LICENSE).
