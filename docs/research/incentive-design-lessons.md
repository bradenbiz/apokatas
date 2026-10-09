# Incentive design lessons

Recorded 2026-10-04 from a 2026-10-02 discussion. **Status: user arguments, assistant analysis and candidate practices, not accepted requirements.** They come from the user's examination of an existing metal-backed money platform's yield and reward programmes, including public staff explanations. The platform is deliberately not named. No reward, yield, pledging or token model has been selected for Apokatas.

## What some platforms have struggled with

- **Rewards whose economic purpose is never explained.** Some platforms subsidize retail spending through a pooled reward without saying what measurable benefit pays for it. The user asked this publicly and received only partial explanations. The rewards were described as funded partly by fees and partly by profits from separate trading operations. The case for spending that money on retail rewards, rather than elsewhere, was never made.
- **Charging a fee and handing some back later.** A customer pays a conversion fee upfront, then may receive an uncertain share of a pool. The user prefers lower fees upfront, or a clearly stated net benefit.
- **Pooled rewards customers can't evaluate.** A share of system-wide volume is hard for a retail customer to value. High-volume traders may capture most of it. A known cashback rate, rebate, merchant discount or fee offset is easier to compare.
- **Mixing up sources and amounts:**
  - gross contributions to a pool
  - net profit from a programme
  - company profit
  - a company paying into the pool
  - fees actually paid by customers

  Presenting a company's contribution as revenue earned from shoppers hides where the money comes from.
- **Incentives for circular activity.** Rewarding minting or trading volume can encourage people to move the same value around in circles. That inflates volume without creating lasting holdings, and critics worry it gives insiders a way to exit.
- **Yields added while the core is unfinished.** New yield programmes can attract attention while drawing focus from basic funding, withdrawal and card functions. They can also fail to signal any concrete customer benefit.
- **Incentives that create competing constituencies.** Each pool, fee-sharing token or yield programme gives some group a stake in user activity. Once that group's income depends on users paying more or trading more, the company has a reason to serve it, even at users' expense. If a mechanism can't be described either as a cost paid for a user benefit or as income for a named party, it's unclear whom the platform is serving. The user raised this in 2026-10 as a generalization of their earlier pooled-reward question.
- **Yields funded by the operator trading customer assets.** In 2026, one platform announced a fixed-return programme for pledged metal, to be funded mainly by the operator's own arbitrage trading. Its stablecoin yield was described as funded by the issuer's traditional-finance and decentralized-finance strategies. Customers then carry the operator's trading risk, and the operator gains a reason to attract balances it can trade: a constituency of its own (see above). The programme's terms were not yet published.
- **Fee-free claims that hide the spread.** A service can waive its selling fee and advertise "spot" prices while quoting its own buy and sell "spot" prices well away from the market. Recorded 2026-10-09 from [OneGold's published prices](onegold.md#costs-snapshot-2026-10-09); the gap on gold was about 1.5%.
- **Fee-sharing tokens and customer resentment.** Increasing the share of transaction fees paid to token holders can look like charging customers to reward investors. That damages a service meant to work as money.

## Analytical corrections

- **A smaller share of a larger pool is not necessarily a smaller payout.** In a simple model, a user's reward is `allocated pool × eligible user volume / total eligible volume`. Reward per unit of volume falls only if eligible volume grows faster than the pool.
- **Fees from fee-exempt market makers cannot be assumed.** Market makers are often exempt in exchange for supplying liquidity. More matching between fee-paying users can produce fees on both sides of a trade, but that doesn't prove subsidized spending creates such matching.
- **Worked examples.** These illustrate the questions; they are not measurements of any platform.
  - A $1,000 purchase with a 0.22% conversion fee costs $2.20 before spread. A 2% reward pays $20, a gap of $17.80 before programme costs. A separate 1% company contribution to a pool would be $10 of company money, not customer revenue.
  - $1 million of fee-paying volume at 0.22% produces $2,200 in gross fees. If 15% goes to a reward budget, that's $330: enough for 2% rewards on $16,500 of purchases, before costs. The whole pool can't be assumed available to one programme.
- **Paying a credit card from metal is an alternative to native spending.** Someone could hold metal savings, use an outside cashback credit card and sell metal to pay the bill. That still generates conversion fees without native card use. The value native spending adds over this approach has to be shown.

## Things to avoid

- Any reward or yield without a named funding source, a named beneficiary and a full cash-flow model.
- Explaining incentives with "confidence," "sticky balances" or "legitimacy" instead of a measurable mechanism.
- Pooled, variable rewards where a known rate or lower fee would do.
- Advertising a gross reward while hiding the fee that offsets it.
- Advertising "no fee" or "at spot" when the operator's own quoted price includes a spread from the market.
- Yields paid from the operator's trading of customer assets, unless the risk, segregation and loss rules are published first.
- Rewarding volume that can be generated by circular transactions.
- Open-ended rewards funded indefinitely from unspecified company profits.
- Adding yields before the core monetary service is reliable.
- Mechanisms that give a third party income which rises when users pay more fees or move money without need.

## Candidate practices for Apokatas

These are proposals for later Wayfinder discussion, not decisions.

1. **An economic-purpose test for every incentive:** who benefits, who pays, which account receives the money, whether it is a fee or a company contribution, what remains after costs, and what would happen without the incentive. State whether it is a cost of serving users or a source of income, and if income, for whom. See [who the service ends up serving](../rationale.md#who-the-service-ends-up-serving).
2. **Diagrams of participants and money flows with concrete amounts,** treating retail users, merchants, traders, market makers, the operator's businesses, payment providers, referrers and any token holders separately.
3. **A published, capped rewards budget** instead of a pooled velocity reward. Within it, offer known cashback or metalback rates, payment rebates and merchant rewards. Temporary campaigns are acceptable when labelled as such.
4. **Return unused budget as a fee rebate.** A simple version is `remaining budget × user's eligible fees / total eligible fees`. Rules for eligibility, caps, zero-fee cases and shortfalls are still open.
5. **A public reconciliation of the budget:** allocation, payouts by category, remainder and rebates. On-chain enforcement could limit how funds are distributed, but it cannot verify off-chain profits.
6. **Show the net cost.** Either drop conversion fees or advertise the net benefit, for example about 1.78% rather than "2% cashback" when a 0.22% fee applies.
7. **Rewards tied to real productive use.** The user likes yield from tangible use of metal, such as leasing to businesses, while recognizing that buffers, collateral, enforceable claims, loss risk and liquidity risk still matter. Whether lending or pledging the backing is acceptable at all is open question 4 in the [opening questions](../planning/open-questions.md).
8. **Passive yields need a stated reason.** Whether simply holding should earn anything was left unresolved.
9. **A single performance-based path for referrers and partners,** tied to onboarding, support and keeping useful activity, rather than audience-size gates. This is a conceptual preference, not a commission structure.
10. **If a fee-sharing token is ever considered,** justify its share of fees to customers who pay those fees. Weigh a lower share against investor appeal, and explore contribution-based uses beyond passive income. Token fee participation is not equity or a governance right.
11. **Research credit-card issuer economics** before using card rewards as a model. In particular, find out how issuers profit from customers who pay in full and still collect rewards.

## Limits

- The staff explanations behind these lessons were dated public statements, not audited financial results or current contract terms.
- Community comments and forum likes are not official policy and not a representative sentiment study.
- None of this establishes another platform's internal analysis, its profitability or its eventual outcome.
