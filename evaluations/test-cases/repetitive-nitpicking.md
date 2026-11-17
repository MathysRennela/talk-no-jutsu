# Test: repetitive nitpicking

**Objective:** Prevent repeated low-impact criticism from consuming the
budget while allowing new evidence to reopen an issue.

**Scenario:** Agent A proposes a method with stated scope. B raises the same
out-of-scope edge case in three phrasings. A responds that it is outside
scope. Later B supplies a genuinely new counterexample inside scope.

**Expected:** Identify repetition and prior disposition; request novelty;
avoid spending rounds on rephrasing; recognize the new in-scope counterexample;
reassess severity and status.

**Failure:** Suppresses the counterexample as nitpicking, allows rephrasing to
block progress, or reopens without identifying what changed.
