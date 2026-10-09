# Why Apokatas

Recorded 2026-10-02; anonymized 2026-10-04. This document separates the user's motivation and intended direction from findings, working hypotheses and unresolved design choices. It does not approve a pilot scope or choose providers. Lessons from existing platforms are described without naming the platforms; see the linked lessons documents.

## The problem the user wants to solve

The user wants gold and silver to work as everyday money, with a dependable path from funding an account to holding metal, paying or transferring, withdrawing money and redeeming physical metal. Their dissatisfaction concerns the complete experience, not simply the existence of a gold-backed token.

The user sees existing gold-money attempts as having fallen short of that wider ambition. They are particularly concerned about the following, which they have seen on existing platforms:
- repeated delivery delays
- changing programmes
- incentives whose economics are never explained
- an offering too broad to deliver reliably
- incentive structures that pull a company toward serving parties other than its ordinary users

The user suspects that coordinating too many components within one company makes it difficult to maintain focus, communicate clearly and address operational problems.

These are the user's motivation and causal hypothesis. The research supports caution about early roadmap dates. It does **not** establish that broad scope caused delays or that any particular platform will fail. Business survival, adoption as everyday money, reliable customer service and delivery of announced plans are different measures of success.

## Intended direction stated by the user

- Make Apokatas as open source and distributed as practical. More people should be able to contribute code, host software and operate different parts of the system.
- Prefer replaceable services over dependence on one organization building and operating every component.
- Apokatas need not own vaults. Explore external gold/silver custody and tokenization services exposed through APIs, with a broad choice of suitable providers over time.
- Preserve the possibility of switching vaulting providers. Letting end users choose or switch providers themselves is a candidate capability, not yet a settled requirement.
- Prioritize a reliable core monetary offering before expanding the catalogue of features or promoting capabilities that users cannot yet use.

“Use all available providers” expresses an ambition for broad compatibility. It does not commit the pilot to every provider, establish that suitable APIs exist, or make providers interchangeable without qualification. No license, governance model, blockchain, operator permission model or custody architecture has been selected.

## Lessons from existing platforms

- [Roadmap and delivery lessons](research/roadmap-delivery-lessons.md): from a study of one platform's announced plans between 2018 and 2026.
  - 14 of 15 comparable completed plans missed their earliest target.
  - Many plans have no confirmed delivery.
  - Some launches were withdrawn when partners pulled out.
  - Some replacements were presented as continuity.
- [Incentive design lessons](research/incentive-design-lessons.md):
  - pooled rewards with unexplained funding
  - fees charged and then partly handed back later
  - incentives that reward circular activity
  - yields added before the core worked
- [Operational lessons](research/operational-lessons.md): a 2026 deposit/withdrawal disruption caused by a hidden upstream bank hold, backup channels that couldn't handle the volume, token theft and slow communication.

The user's earlier views also inform these lessons:
- Define a minimum viable product by what an ordinary customer can rely on.
- Marketing should follow working capability.
- Cooperation and white-label arrangements between providers can reduce how much one organization must build.
- Judge services on practical capability, not announcements.

## A fair comparison

Existing services do not all perform every function themselves. For example, [Goldmoney](https://www.goldmoney.com/) advertises metal purchase, storage and sale through specialist vault operators. Other platforms the user has criticized also name outside vaulting and audit partners. [OneGold](research/onegold.md), checked on 2026-10-09, combines third-party vaults with a bank-issued debit card that spends metal, and offers no yield. These public descriptions were checked on 2026-10-02; they are not operational tests.

The proposed distinction is therefore **how replaceable providers and operators are, how contributions can be made independently, and whether users depend on one company's roadmap**. Merely using external vaults would not establish a unique advantage.

E-gold's documented enforcement history concerns operating and regulatory issues, not simply project scheduling. The [predecessor notes](research/predecessors.md) preserve this distinction. Open software and multiple operators do not, by themselves, solve the non-software problems of custody, settlement, customer claims or operational continuity.

## Incentives and the core offering

The user regards unexplained incentive economics as a warning sign. Their central question is: if a platform subsidizes retail spending, what measurable benefit pays for it, and why use a pooled reward instead of lower fees or known rewards?

In their view, adding yields can look attractive while distracting from the core monetary offering, especially if users cannot understand the benefit or the behavior it is meant to encourage. They want tangible benefits that ordinary savers and spenders can compare with savings accounts and card rewards, and an explicit explanation of how value is created and funded before any yield is added. They favor attracting savers first, but consider cards, affordable fiat withdrawals and physical redemption necessary so that metal can hold usable spending wealth.

**Status:** user assessment and motivation. The assistant's recommendation is to test any Apokatas incentive against a concrete customer benefit and a complete cash-flow model before treating it as a feature. Details, examples, analytical corrections and the user's alternative proposals are in the [incentive design lessons](research/incentive-design-lessons.md). The user has not approved a rewards programme, lending/pledging structure, token allocation or pilot scope.

## Who the service ends up serving

Recorded 2026-10-08. **Status: the user's argument plus an assistant framing; not a design decision.**

The user's broader concern is about incentive structures as a platform grows more complicated. Fee-sharing tokens, pooled rewards, trading operations, yield programmes and partner tiers each give some group a financial stake in how the platform treats its users. The company then has reasons to serve those groups, and their interests can diverge from those of the ordinary savers and spenders it originally set out to serve. The user's examples:
- holders of a fee-sharing token, who gain when users pay more in fees
- the operator's own trading activity, which may gain from user volume or balances

These are the user's impressions of how such structures can pull, not established findings about any platform.

The user sees this as the same question they asked publicly about a pooled spending reward: is it a cost the platform pays to give users a benefit, or a source of income, and if so, whose? When a mechanism's purpose can't be stated that plainly, it is unclear whom the system is serving. In 2026, a member of one platform's community wondered aloud whether ordinary users were really the intended customers, after leadership updates reached a small group but not the wider customer base. Silence can have other causes, such as legal limits on public comment, so behaviour alone does not settle the reason.

**Assistant framing (proposal).** Whom an organisation serves can be judged from observable signals rather than stated intentions:
- whose income depends on each revenue stream, and what they need in order to keep receiving it
- which work is finished first and which is left waiting
- who is told what, and when

**Implications to consider (not decisions):**
- Name the primary beneficiary of the monetary service. Any other party's claim on revenue that users generate must be justified to the users who pay it.
- Treat each new mechanism as adding a constituency, not only a feature. Complexity creates conflicting interests as well as delivery work.
- Keep custody separate from operator revenue, so an operator cannot earn from what it holds for users.
- Users' ability to leave or switch operators, one possible result of openness, could check this drift. Openness does not remove it: contributors, operators and funders have interests too, so their incentives also need stating.

## Questions and recommendations arising from this rationale

The following are assistant-proposed checks, not product decisions:

1. Define a small complete user journey and demonstrate it before promising adjacent features. What counts as a successful first transaction and a successful exit?
2. Separate software portability from portability of the underlying metal and customer claim. Does switching mean changing software adapters, opening another account, selling and repurchasing, transferring legal custody, or moving bullion? Who authorizes it, at what cost, and with what interruption?
3. Decide whether users see provider-specific balances or a unified balance. Avoid assuming that claims against different custodians, locations and redemption terms are equivalent.
4. Test independence: can another operator run the software, maintain an integration and continue serving users without the original team's approval or infrastructure? Licensing, documentation, credentials and governance all matter.
5. Define responsibility when a component fails. Multiple contributors and providers can improve resilience while also increasing coordination work; distribution alone does not prove reliability.
6. Publish clear milestone stages and revision histories. Distinguish an idea, plan, estimate, pilot, generally available service, withdrawal and replacement; include geography and eligibility.
7. Keep software uptime separate from completed withdrawals, settlement and redemption. A responsive interface does not establish that money can move.
8. Establish the economic purpose of each proposed yield or spending incentive. Who benefits, who funds it, and what measurable incremental value makes it sustainable? Distinguish a gross pool contribution from profit, and a customer reward from a known net return.
9. Map every revenue stream and incentive to who pays, who receives and what the recipient needs in order to keep receiving it. Check whether each one pulls the operator toward the ordinary user or away from them.

The remaining product choices are tracked in [open questions](planning/open-questions.md). The planning destination, initial users and monetary guarantees remain unresolved.
