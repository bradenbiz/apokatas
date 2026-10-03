# Issue tracker: GitHub

Use GitHub Issues in [bradenbiz/apokatas](https://github.com/bradenbiz/apokatas/issues) for the project's issues, Wayfinder map, and decision questions. Use the `gh` CLI from the repository, or specify `--repo bradenbiz/apokatas` explicitly.

For multiline issue descriptions and comments, prepare the exact text in a file and use `--body-file`. Check existing issues before creating new ones to avoid duplicates. Refer to issues by their descriptive titles with links, not by bare numbers.

## Wayfinding operations

- **Before charting:** Settle the destination with the user, then discuss the major open areas. The current opening questions are in `docs/planning/open-questions.md`; none is answered yet.
- **Map:** Create one issue labelled `wayfinder:map`, with Destination, Notes, Decisions so far, Not yet specified, and Out of scope sections. Keep it an index; detailed decisions belong in their issues.
- **Child questions:** Create sub-issues of the map and label them `wayfinder:research`, `wayfinder:prototype`, `wayfinder:grilling`, or `wayfinder:task`. Create the labels when needed. If sub-issues are unavailable, use explicit parent links and a map task list.
- **Dependencies:** Use GitHub's native issue dependency relationships. Create issues before wiring their dependency edges. If the capability is unavailable, document blockers explicitly in the issue bodies.
- **Next available question:** Select an open child issue with no open blockers and no assignee. Fetch current tracker state rather than trusting an older local summary.
- **Claim:** Assign the selected issue to the developer driving the session before working it.
- **Resolution:** Record the outcome in a comment, close the issue, and append a short linked summary to Decisions so far. User-dependent questions require the user's actual participation.
- **New questions:** Create issues only when their questions can be stated precisely. Keep less-defined areas in Not yet specified. Record excluded work in Out of scope.

Consult the installed Wayfinder skill for its full workflow, including its per-session limit on resolving non-research questions. Check current GitHub API documentation if a relationship operation is unfamiliar or unavailable.

## Relationship to repository files

Markdown files retain the brief, history, dated research, and current context. Once a decision issue exists, its resolution is the detailed source of truth; the map and local memory should point to it rather than independently restating the decision.

Pull requests as a triage request surface: off. No triage workflow or triage label vocabulary has been configured.
