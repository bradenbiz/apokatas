# Apokatas project history

This is a summary of the project conversation and material actions, not a verbatim transcript. User intentions, suggestions, and completed work are identified separately.

## 2026-09-12 — Repository and skill installation

- The user requested a public repository named `apokatas` in their personal GitHub account.
- `bradenbiz/apokatas` was created as public. The local project was initialized on `main` and connected to `origin`.
- Initial commit `765bdd2` added the README and a `.gitignore` excluding local environment files and `.DS_Store`.
- The user wanted Matt Pocock's Wayfinder skill to explore the project idea. Wayfinder, setup-matt-pocock-skills, grilling, and domain-modeling were installed in the local Codex environment.
- In a follow-up, the user asked how GitHub would store issues and what participation was expected. The assistant explained the parent map, child decision questions, recorded resolutions, and the user's role in product choices. It also clarified that repository-specific tracker setup still remained at that point and that published issues would be public.

## 2026-09-12 — Initial idea and opening discussion

- The user invoked Wayfinder and described an open-source monetary system intended to make gold and silver usable as money, potentially adding other metals.
- The user supplied ten candidate features and preferred exploring service providers over initial vertical integration. The complete idea inventory is in the [project brief](project-brief.md).
- Preliminary primary-source research examined e-gold, PAXG, XAUT, KVT, and the SchiffGold/TGold reference. The [research notes](research/predecessors.md) preserve the findings and their limits.
- The assistant asked five questions about the destination, meaning of open, first customers, monetary guarantees, and predecessor failures. It offered recommendations but received no answers or acceptance. The questions remain in [open questions](planning/open-questions.md).
- No Wayfinder map, child decision issues, final product decisions, or application code were created.

## 2026-09-27 — Provider leads captured in conversation

- The user said they would answer the opening questions later.
- The user pasted a Google-generated summary naming Rush Institutional APIs, BullionVault XML API, Kitco Digital Metals, and nFusion Developer Hub.
- The user explicitly said they did not know whether the offerings would fit and requested acknowledgment only. The assistant acknowledged them as unverified leads; no verification or provider selection was performed.
- The supplied claims are preserved in [provider leads](research/provider-leads.md).

## 2026-10-02 — Repository documentation archive

- The user requested that the conversation's project context, memory/history, and any actual code changes be put on GitHub, and asked what input was still needed.
- The repository and remote were checked: only the initial README and `.gitignore` existed, with no GitHub issues or application code.
- Added the current memory, brief, unanswered questions, dated research, provider leads, and this history, linked from the README.
- Added instructions for future sessions and documented GitHub as the issue tracker. This configuration does not create or approve a Wayfinder map.
- The remaining user input is the opening set of five questions. No proposed monetary guarantees, pilot design, or provider choice has been promoted to an accepted decision.

## 2026-10-02 — Wayfinder handoff for another machine

- The user requested a discoverable checkpoint so Wayfinder could resume the unanswered questions later on another machine.
- Added an explicit resume instruction near the top of `AGENTS.md`, pointing directly to [the saved handoff and questions](planning/open-questions.md).
- The handoff identifies the exact planning stage, links the context required without the original chat, includes a suggested resume message, and explains that local skill installations must also be available on the new machine.
- All five questions remain unanswered; no planning decisions or GitHub map were created as part of this handoff.

## 2026-10-02 — Project rationale and predecessor research incorporated

- The user asked to add this conversation's findings to the project's “why,” and clarified an ethos of open source, multiple contributors, independent hosting and different people operating components.
- The user prefers external custody/tokenization APIs and replaceable providers; Apokatas need not own vaults. Broad compatibility is an ambition, while end-user provider selection is still optional and unresolved.
- The user identified an existing platform's delivery delays and breadth of work as concerns, and proposed scope complexity as a possible cause. The rationale preserves this hypothesis without declaring that platform or every predecessor failed.
- Imported a September 14 historical delivery study and summarized it. Its selected-sample limits were preserved, and a misleading interpretation of current availability was withdrawn.
- Recorded the user's earlier views on a usable MVP, white-label cooperation, marketing after delivery and evaluation dimensions. These are viewpoints, not verified product scores.
- Rechecked Goldmoney's public offering and another platform's named external vaulting/audit partners. This narrow check qualifies blanket claims about failure and vertical integration; it does not select providers.
- Updated opening questions 2 and 5 to partially answered. No Wayfinder destination, map, pilot feature set, custody contract, licensing/governance choice or application implementation was selected.

## 2026-10-02 — Incentive discussion added to the rationale

- The user asked to preserve an analysis of an existing platform's yield and reward changes as another reason for Apokatas. They view the unresolved economic purpose of retail-spending incentives and perceived lack of execution as major warning signs, and prefer a focused core offering with tangible benefits.
- Recorded the user's three-part argument:
  - whether retail spending should earn income for a shared fee pool
  - whether lower fees or explicit rewards would work better than a pooled velocity reward
  - what measurable value elsewhere justifies a spending subsidy
- Checked public staff explanations of fee exemptions, two-sided trading fees and the funding of rewards from operating profits. Historical statements were kept separate from current terms and audited evidence.
- Preserved the discussion of yields, productive pledging, referral progression, fee-sharing token allocation, explicit rewards budgets and fee rebates as viewpoints or proposals, not approved Apokatas features.
- Corrected the assumption that growth necessarily reduces a pooled payout, and recorded that gross pool inflows differ from profit, and company contributions from customer fees.

## 2026-10-04 — Operational lessons from a platform disruption

- The user asked for an explanation of an operator's statement about a deposit/withdrawal disruption at an existing metal-backed platform, then asked to record lessons and things to avoid without publicly naming that platform's failures.
- Added [operational lessons](research/operational-lessons.md): general failure modes (hidden upstream bank holds, fallback channels that couldn't handle volume, sold metal becoming a claim on the operator, downstream token theft, slow and uneven communication, scope expanding ahead of core reliability) and candidate considerations for Apokatas. These are proposals; none was adopted as a requirement.
- The underlying specifics include information shared in confidence in a restricted forum section. They are kept in a gitignored local `private/` folder, which is now excluded in `.gitignore`. Nothing from that material was published.

## 2026-10-04 — Public records anonymized

- The user asked whether other repository content should be turned into anonymized lessons like the operational lessons, and chose to anonymize it and also rewrite git history.
- Added [roadmap and delivery lessons](research/roadmap-delivery-lessons.md) and [incentive design lessons](research/incentive-design-lessons.md). Rewrote the rationale, brief, opening questions, predecessor notes, memory and this history so they don't name other platforms' failures. Neutral, sourced competitor facts remain.
- Moved the platform-specific delivery study and dataset, the user's forum-post notes and the pre-anonymization records to the local `private/` folder.
- Replaced the three most recent commits with a single anonymized commit and force-pushed, so the user's forum identity, token holdings and the named research no longer appear in the public history. A backup bundle of the earlier history is kept privately.

## 2026-10-08 — Who the service ends up serving

- The user agreed with a community member's remark that a platform's leadership seemed disengaged from ordinary customers, as if they weren't the intended customer base. They identified a broader principle: as a platform grows more complicated, its incentive structures (fee-sharing tokens, trading income, pooled rewards) give it other parties to serve besides the retail users it set out to serve. The user tied this to their earlier public question of whether a pooled spending reward is a user benefit or a source of income, and for whom.
- Added a [rationale section](rationale.md#who-the-service-ends-up-serving) and a related check. Added a matching failure mode, an avoid item and an extension of the economic-purpose test to the [incentive design lessons](research/incentive-design-lessons.md). Added communicating legal constraints publicly to the incident-communication consideration in the [operational lessons](research/operational-lessons.md). All of these are user arguments or proposals, not decisions.
- The thread came from a restricted forum section that includes information shared in confidence, so its specifics are kept only in the private folder.

