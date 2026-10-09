# Apokatas current memory

Last updated: 2026-10-09.

## Established context

- The public personal repository is [bradenbiz/apokatas](https://github.com/bradenbiz/apokatas); the working branch is `main`.
- The user wants an open-source monetary system that brings gold and silver back into everyday use as money. Other metals may be considered.
- The user reinforced a preference for external banking, vaulting, card and audit providers on 2026-10-02. Apokatas need not own vaults; explore gold/silver custody and tokenization via APIs. Favor replaceable providers and broad compatibility over time. No provider has been selected.
- Openness should enable multiple contributors, independent hosting and different operators running components. User-facing provider choice is still a candidate option. License, governance and operator permissions are unresolved.
- Delivery delays, breadth/complexity and dependence on one organization motivate the project. The hypothesis that scope causes delays or predicts failure is not established by the research.
- The user also sees unclear incentive economics and the unresolved purpose of subsidizing retail spending as reasons for Apokatas. They want tangible, comparable benefits and an explicit explanation of funding and value creation before adding yields. No Apokatas reward or yield model has been selected.
- On 2026-10-08 the user generalized the incentive concern: as platforms grow more complex, incentive structures (fee-sharing tokens, trading income, pooled rewards) give them parties to serve other than ordinary users. Is each mechanism a user benefit or income, and for whom? Recorded in the [rationale](docs/rationale.md#who-the-service-ends-up-serving) as an argument and proposals, not a decision.
- On 2026-10-09 the user asked for a scored OneGold comparison using the same 21 criteria as their earlier TGold comparison. The criteria and OneGold's scores are in [OneGold](docs/research/onegold.md); the named comparison is private. The criteria are a candidate checklist, not adopted requirements.
- Public docs describe other platforms' failures generically ("some platforms have struggled with…") and do not name them. Neutral, sourced facts about competitors may stay named. Specifics live only in the local `private/` folder.
- The user chose Wayfinder to explore the idea and expects the resulting map and decision issues to live on GitHub.
- The user wants project memory, history, and code changes preserved in the repository and pushed to GitHub.

## Current state

The project remains in the opening Wayfinder discussion. The user has partially answered questions 2 (meaning of open) and 5 (predecessor problems). Questions 1, 3 and 4 remain unanswered. There is no agreed planning destination, final MVP scope, legal structure, launch market, monetary contract, technology choice, or economic model.

As checked on 2026-10-02, the repository has no GitHub issues and no application code. The documentation records the conversation, GitHub tracker conventions, the user's rationale and three anonymized lessons documents: roadmap/delivery, incentive design and operations. On 2026-10-04 the platform-specific research, the user's forum identity and their token holdings were moved to private storage, and git history was rewritten so they no longer appear in the public history. On 2026-10-09 OneGold was researched as a narrow, no-yield comparison point, and the operational and incentive lessons were updated from a public re-check. A Wayfinder map has not yet been created.

Wayfinder, setup-matt-pocock-skills, grilling, and domain-modeling were installed in the user's local Codex environment on 2026-09-12. Those installed skills are not vendored into this repository; availability should be checked when working from another environment.

## Next step

Resume with the [Wayfinder handoff and partial answers](docs/planning/open-questions.md). Settle the destination, first users/use case and monetary guarantees; clarify the remaining operator versus end-user provider choices and measurable core-service priorities. When defining the core offering, include the unresolved incentive-economics question and the lessons documents: [roadmap/delivery](docs/research/roadmap-delivery-lessons.md), [incentives](docs/research/incentive-design-lessons.md) and [operations](docs/research/operational-lessons.md). `AGENTS.md` directs future sessions to this checkpoint, including on another machine. Do not restart intake. The user's forum identity and posts are recorded in the private notes. Assistant recommendations remain proposals.

After those answers, continue the discussion across the major open areas, then create the Wayfinder map and child issues. Research should answer factual questions; the user makes product decisions.

## Where details live

- [Rationale](docs/rationale.md): user motivation, intended openness/provider direction, a summary of incentive concerns, evidence limits and proposed follow-up checks.
- [Roadmap and delivery lessons](docs/research/roadmap-delivery-lessons.md): anonymized findings from a 2018–2026 delivery study, things to avoid, candidate practices and the user's earlier MVP/evaluation views.
- [Incentive design lessons](docs/research/incentive-design-lessons.md): anonymized reward/yield analysis, corrections, worked examples and the user's alternative proposals.
- [Project brief](docs/project-brief.md): original intention and all ten feature ideas.
- [Open questions](docs/planning/open-questions.md): the opening round, partial user answers and remaining questions.
- [Predecessor research](docs/research/predecessors.md): preliminary findings checked on 2026-09-12, with sources and limits.
- [Operational lessons](docs/research/operational-lessons.md): anonymized failure modes from a platform's 2026 deposit/withdrawal disruption, things to avoid and candidate resilience considerations (proposals, not requirements).
- Private notes: the gitignored `private/` folder in the main checkout (`~/repos/apokatas/private/`, this machine only) holds non-public specifics behind the anonymized docs. That includes `private/platform-research/` (the named study and dataset, the user's forum posts, pre-anonymization records, and the 2026-10-09 named OneGold vs. Kinesis scoring with raw evidence) and a backup bundle of the pre-rewrite history. Never copy them into tracked files.
- [OneGold](docs/research/onegold.md): a vaulted-metal account with a spending card, researched 2026-10-09. Costs, ownership terms, custody evidence, a published-terms comparison, considerations for Apokatas and the user's 21 evaluation criteria.
- [Provider leads](docs/research/provider-leads.md): Google-generated suggestions supplied by the user on 2026-09-27 (unverified), plus suppliers observed behind OneGold's card on 2026-10-09.
- [History](docs/history.md): milestones and changes in the conversation.
