# Opening Wayfinder questions

Status on 2026-10-02: questions 2 and 5 have partial user answers from the project-rationale discussion. Questions 1, 3 and 4 remain unanswered. Recommendations below remain assistant proposals unless explicitly identified as user statements.

## Wayfinder handoff

This is the canonical checkpoint for resuming the opening interview on another machine. The original chat is not required.

**Resume point:** Wayfinder's **Chart the map → Name the destination** step. The initial idea has already been supplied; the first round has partial answers on openness and predecessor problems, while the destination, initial users and monetary guarantees remain pending. No map or child decision issues have been created.

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

**User answer (partial, 2026-10-02):** As open source and distributed as practical, with many people able to code, host and operate different parts. Favor replaceable external services; Apokatas need not own vaults. Explore custody/tokenization APIs and broad provider compatibility. User-facing provider choice remains a possibility, not a requirement.

**Still open:** license, governance and contribution authority; who can operate which components; participation rules; and whether replacing providers is an operator capability, an end-user capability or both. See [rationale](../rationale.md).

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

**User answer (partial, 2026-10-02):** Repeated delivery delays at an existing platform, the difficulty of keeping track of a broad offering, and dependence on one company attempting to coordinate many pieces motivate a focus on the core offering and distributed, replaceable services. The user suspects excessive scope contributes to failure risk.

**Additional user answer (2026-10-02):** The user regards the still-unresolved economic purpose of retail-spending subsidies as another warning sign. They suspect that adding yields without tangible customer benefits distracts from the core monetary service, and they report dissatisfaction with how an existing platform carried out its expansion. They want to know who pays, who benefits, and what measurable value funds an incentive. Their public question about this received only partial answers; that platform's internal analysis, rollout status and profitability remain unestablished. The [incentive design lessons](../research/incentive-design-lessons.md) preserve the arguments, proposals and limits. No yield/reward model for Apokatas was approved.

**Additional context (2026-10-04):** a deposit/withdrawal disruption at an existing platform added concerns about banking redundancy, protection of customer cash and crisis communication. See [operational lessons](../research/operational-lessons.md).

**Evidence boundary:** the delivery study does not establish causation or predict business failure, and the platform studied itself uses outside partners. The user's earlier views also recognized regulatory and negotiating constraints. See [roadmap and delivery lessons](../research/roadmap-delivery-lessons.md).

**Still open:** which two or three shortcomings are unacceptable for Apokatas and the measurable acceptance criteria for the first user journey. The user's earlier benchmark for an existing platform's MVP does not automatically become an Apokatas commitment.

## Resuming the discussion

The user can answer by number in rough notes; uncertainty is useful input. Continue with the newly answerable questions after this round. Budget, team, timing, jurisdictional feasibility, provider fit, economics, and feature sequencing have not yet been resolved.

Wayfinder's destination must be settled before the map is created. No recommendations above should be silently converted into accepted scope or closed decision tickets.
