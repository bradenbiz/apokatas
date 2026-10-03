# Opening Wayfinder questions

Status on 2026-10-02: all five questions remain unanswered. Recommendations below were supplied by the assistant and are not user decisions.

## Wayfinder handoff

This is the canonical checkpoint for resuming the opening interview on another machine. The original chat is not required.

**Resume point:** Wayfinder's **Chart the map → Name the destination** step. The initial idea has already been supplied; the first round of questions is awaiting the user's answers. No map or child decision issues have been created.

Before continuing, read the [current memory](../../MEMORY.md), [project brief](../project-brief.md), and [GitHub tracker conventions](../agents/issue-tracker.md). The brief preserves all ten feature ideas; the memory links to predecessor research and unverified provider leads. Use those records as context instead of asking the user to repeat the initial idea.

Load the Wayfinder skill and its grilling and domain-modeling support skills in the new environment. They were installed on the original machine, but are not bundled with the repository. If missing, obtain them from [Matt Pocock's official skills repository](https://github.com/mattpocock/skills) before continuing the skill workflow.

Suggested resume message after cloning or pulling this repository:

> Use Wayfinder to continue from docs/planning/open-questions.md. Read the saved context and resume the unanswered opening questions.

As the user answers, replace each pending answer with their actual response, distinguish remaining uncertainty, and update the memory and history. Once the destination is agreed, continue Wayfinder's discussion across the major open areas before creating the GitHub map and its child issues. The recommendations below are starting points for discussion, not approved requirements.

## 1. Planning destination

**Question:** Should this effort produce a concrete design for an Apokatas pilot the user intends to launch, or an open monetary-system specification that others could implement?

**Proposed answer:** A decision-complete design for a first viable pilot, supported by evidence about providers, operating requirements, and economics, sufficient to decide whether to proceed and write an implementation specification.

**User answer:** Pending.

## 2. Meaning of open

**Question:** Does open mean inspectable and reusable source code, multiple independent operators using a shared system, permissionless participation, or something else?

**Proposed answer:** Start with open-source software, documented interfaces, and explicit ways to replace providers. Leave the number of operators, participation rules, and blockchain choice open until the intended guarantees are understood.

**User answer:** Pending.

## 3. First users and primary activity

**Question:** Who are the first customers, in which countries, and what is their main activity: saving in metal, paying other people, merchant purchases, cross-border transfers, or another use?

**Proposed answer:** Begin with one community and one primary activity. A starting hypothesis is people who already want to hold gold or silver and want to transfer those balances to others.

**User answer:** Pending.

## 4. Monetary guarantees

**Question:** When someone holds a balance representing one gram of gold, what must be true about its backing, their ownership, redemption, and their position if Apokatas stops operating? Are lending or pledging the backing categorically unacceptable?

**Proposed answer:** Consider full backing by unencumbered metal, no lending of that backing, and clearly defined ownership and redemption rights as requirements to investigate. Research must establish which structures could actually deliver them, including during operator failure.

This is a proposed product requirement, not a finding that any legal or operational structure already provides it.

**User answer:** Pending.

## 5. Priority predecessor failures

**Question:** Which two or three predecessor deficiencies motivated the project? Which would make Apokatas unacceptable even if its other features were excellent? Concrete experiences or examples would help.

**Proposed answer:** Prioritize the failures before ranking features. Initial candidates are usable physical redemption, credible verification of backing and customer claims, and continuity when a provider fails.

**User answer:** Pending.

## Resuming the discussion

The user can answer by number in rough notes; uncertainty is useful input. Continue with the newly answerable questions after this round. Budget, team, timing, jurisdictional feasibility, provider fit, economics, and feature sequencing have not yet been resolved.

Wayfinder's destination must be settled before the map is created. No recommendations above should be silently converted into accepted scope or closed decision tickets.
