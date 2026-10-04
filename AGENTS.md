# Working on apokatas

## Start here

Read `MEMORY.md` before continuing the project. Follow its links to the brief, unanswered questions, research, and history as relevant. These files preserve context from the initial planning conversation.

## Resume Wayfinder here

When the user invokes Wayfinder or asks to resume planning, open [the saved Wayfinder handoff and unanswered questions](docs/planning/open-questions.md) first. That file is the canonical checkpoint for the unfinished opening interview, including when continuing on another machine without the original chat.

The resume point is **Chart the map → Name the destination**. Read the handoff, `MEMORY.md`, and `docs/project-brief.md`, then continue the pending questions with the user. Do not restart intake, assume the proposed answers were accepted, or create a map with an invented destination.

Check that the Wayfinder, grilling, and domain-modeling skills are available in the current environment; the prior machine's installations do not travel with this repository. Use `docs/agents/issue-tracker.md` for the established GitHub tracker configuration.

## Preserve the status of information

- Distinguish user-stated intentions, candidate features, assistant recommendations, sourced findings, and unverified leads.
- The opening Wayfinder questions have partial user answers recorded in `docs/planning/open-questions.md`; unresolved parts remain open. Do not treat suggested answers as accepted requirements.
- Record product decisions only after the user makes them. Do not invent answers to advance planning.
- Keep the original broad ambition separate from the eventual pilot scope; a candidate feature is not an MVP commitment.
- Recheck dated provider and competitor claims before using them to make a decision. A marketing claim does not establish integration availability, eligibility, pricing, or operational reliability.

## Persistent records

Update `MEMORY.md` when the current state or next step changes. Add material developments to `docs/history.md`, with dates. Keep detailed content in its relevant document rather than copying it into every record.

The user requested that project memory/history and actual code changes be committed and pushed to this public GitHub repository. Inspect changes before publishing; include intended project work and exclude credentials, local environment files, and unrelated changes.

The user does not want specific platforms' operational failures named in public lessons; describe them generically ("some platforms have struggled with…"). Keep specifics, and anything shared in confidence, in the gitignored `private/` folder of the main checkout (`~/repos/apokatas/private/`). It exists on one machine only, so never copy its contents into tracked files, issues or PRs.

## Agent skills

### Issue tracker

Use GitHub Issues in `bradenbiz/apokatas`. See `docs/agents/issue-tracker.md`. Do not create a Wayfinder map until the user has settled its destination and the opening discussion has exposed the initial questions.

### Domain docs

Use a single project context. See `docs/agents/domain.md`. Create a glossary or architecture decision record only when there is an agreed term or qualifying decision to record.
