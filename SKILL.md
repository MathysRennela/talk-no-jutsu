---
name: talk-no-jutsu
description: >
  A multi-agent scientific collaboration protocol for resolving disagreements,
  preventing adversarial stagnation, synthesizing competing hypotheses, and
  converting criticism into measurable research progress. Invoke when agents
  disagree, repeatedly criticize one another, revisit resolved objections,
  or stop making progress.
---

# Talk-no-Jutsu

## Mission
Turn disagreement into scientific progress. This protocol is for multi-agent
investigations with conflicting conclusions, repetitive criticism, unresolved
objections, or diminishing returns. The goal is productive understanding,
not consensus. Scientific accuracy takes precedence over conversational harmony.

## When to invoke
Invoke when agents materially disagree, criticism cycles without new evidence,
resolved objections are repeatedly reopened, assumptions or methods conflict,
or discussion consumes resources without producing a useful next step.

## Architecture

### Protocol-based facilitation
There is no mandatory facilitator agent. Any participant may initiate and
temporarily coordinate a round. Initiating a round confers no authority over
scientific conclusions. Participants share responsibility for the protocol.
Where possible, complete independent investigations before sharing conclusions
and preserve evidence provenance.

### Hybrid objection management
Dynamically prioritize objections with configurable limits.
- Default: up to **3 priority objections per round**.
- Keep lower-priority issues in a visible backlog.
- Promote an objection when new evidence establishes its importance.
- Never cap or suppress genuinely critical objections.
- Adapt the budget to stakes and available resources.

### Explicit anti-nitpicking
Participants may flag repetitive criticism. Identify its prior disposition,
ask what new evidence, changed assumption, or reasoning justifies reopening it,
and assess whether that changes the conclusion or risk. Without material
novelty, retain the previous disposition and move forward.
Do not mistake persistent criticism about a genuine flaw for nitpicking.

## Protocol

### Phase 1 — Establish independent positions
Record each agent's main hypothesis or conclusion, supporting evidence and
provenance, assumptions, confidence, limitations, and what would change its mind.
Do not confuse confidence with evidence quality.

### Phase 2 — Reconstruct perspectives
Each agent states the strongest reasonable version of another participant's
position. Identify the exact claim, its evidence, relevant assumptions and
constraints, and the strongest reason it could be right. Correct
misunderstandings before debating conclusions.

### Phase 3 — Diagnose disagreement
Classify disagreements as factual, methodological, assumptive, objective-based,
interpretative, or epistemic (insufficient evidence). Separate conflicts that
affect the main conclusion from those that do not.

### Phase 4 — Triage objections
- **Critical:** invalidates a central claim, result, or essential condition.
- **Major:** materially weakens the conclusion or scope.
- **Moderate:** warrants investigation but need not block current work.
- **Minor:** limited impact; record and defer.
- **Cosmetic:** stylistic or preferential.

A useful objection identifies the precise claim, why it matters, evidence or a
counterexample, potential impact, and a proposed check where possible.
Prioritize by impact, plausibility, and checking cost—not rhetorical force or
repetition. Select up to three priority objections by default; retain others
in a backlog. Critical objections are never suppressed by a quota.

### Phase 5 — Reconcile or design a test
Consider three outcomes:
1. **Synthesis:** combine compatible insights, stating what survives and which
   assumptions the synthesis requires.
2. **Discriminating test:** specify competing predictions, inputs and controls,
   success/failure criteria, cost, responsible agent, and implications.
3. **Preserved disagreement:** document competing positions, assumptions,
   evidence, confidence, and what would change each agent's mind.

Never manufacture consensus.

### Phase 6 — Resolve objections
Each material objection must be resolved, accepted risk, deferred, or blocking.
The challenged agent must have an opportunity to respond. The proposer cannot
unilaterally declare the objection resolved; assess the response against
evidence and actual impact. Reopen resolved objections only with new evidence,
changed assumptions, failure of the prior resolution, or a materially
different argument.

### Phase 7 — Intervene in stagnation
Name the recurring objection, point to its prior disposition, request what
new information warrants reopening, and mark repetition as non-progressing
when no material novelty exists. Preserve the record and proceed according
to the prior status unless a critical flaw remains unresolved.

Suggested wording:
> This appears to repeat the concern addressed in round 2. What new evidence
> or changed assumption makes that resolution insufficient? Without such a
> change, let's retain its status and move to the next unresolved issue.

Do not penalize an agent for finding a real flaw, correcting a previous
mistake, or identifying a distinct implication.

### Phase 8 — Commit to progress
End with what was learned, what remains uncertain, objection statuses, the
most valuable next action, its owner, and what result could change the
conclusion. If discussion has diminishing value, stop debating and execute
the test or document the uncertainty.

## Output format
1. Research question.
2. Agent positions: claims, assumptions, evidence, confidence.
3. Disagreement map.
4. Objection register: severity, evidence, owner, status, disposition.
5. Reconciliation: synthesis, test, or preserved dissent.
6. Scientific confidence: established, supported, uncertain, unsupported.
7. Progress assessment.
8. Next actions: task, owner, expected result, decision informed.

## Termination
Stop when material objections have explicit dispositions, remaining
disagreement is documented, a discriminating test is ready, discussion has
diminishing value, or the interaction budget is exhausted. Termination does
not imply consensus or correctness.

**Understand. Reconcile. Investigate. Move forward.**
