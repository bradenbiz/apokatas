# OneGold: a vaulted-metal account with a spending card

Researched 2026-10-09. **Status: sourced findings plus assistant interpretation, clearly labelled.** Neutral, published facts are named. Prices and holdings are snapshots from that day and will change. Recheck before using any of this for a design or provider decision. Nothing here selects OneGold, or any company named, as a provider.

## Why it matters to Apokatas

OneGold is a working example of what the [rationale](../rationale.md) describes:

- metal bought, stored, spent and redeemed through outside providers: a bank issues the card, a card network carries it, and third-party vaults hold the metal;
- no yield, token or exchange.

It shows what a deliberately narrow service looks like in practice. It is not evidence that the narrow model wins with users; no adoption figures comparable across platforms were found.

## What it is

- **Ownership:** launched in 2018 by APMEX and Sprott. APMEX took full ownership in 2021. Since 2025 APMEX has been part of Bullion International Group, which is majority-owned by MKS PAMP. ([APMEX/Sprott launch](https://www.onegold.com/pressreleases/apmex-and-sprott-launch-onegold); later ownership is from press releases summarized in research notes)
- **Contracting party:** OneGold, LLC, a Delaware company based in Oklahoma City. Custody letters, wire instructions and the iOS app still name "OneGold, Inc." ([User agreement](https://www.onegold.com/useragreement))
- **Metals:** gold, silver and platinum (platinum in US vaults only). Holdings are fractional interests in kilo, 400 oz and 1,000 oz bars. ([Products](https://www.onegold.com/products))
- **Vault countries:** the US, Switzerland, Canada (Royal Canadian Mint) and the UK. ([Storage](https://www.onegold.com/storage-fees))

## The OneGold Card

Launched around mid-2026. The card page was first archived on 2026-06-09, and its help articles are dated July–September 2026. No launch press release was found. ([Card page](https://www.onegold.com/onegold-card))

- **Issuer and network:** Mastercard, issued by Cross River Bank.
- **Formats:** a virtual card immediately and a free physical card. Apple Pay and Google Pay. Works at ATMs.
- **How spending works:** each authorization sells just enough metal or cash to cover the purchase. You set the order in which gold, silver, platinum and cash are used. If you don't have enough, the payment is declined; there is no overdraft or credit line.
- **Selling fee:** none when spending US Gold. None for US Silver until 2026-12-31. Other fees exist (out-of-network ATMs, international transactions), but the cardholder agreement and fee schedule are not public.
- **Eligibility:** US residents with an SSN, individual accounts only.
- **Price used:** marketing says "Always at Spot". The disclosure says each purchase settles at an "indicative price" derived from the products page, which lists OneGold's buy and sell prices.
- **If the program ends:** at least 60 days' notice; metal is not liquidated and stays in the account.
- **Rewards:** none on this card. The separate Bullion Card is a Visa credit card from UMB Bank that pays points (4 per dollar at OneGold/APMEX, 1 elsewhere) usable for metal, at 17.74–27.74% APR. ([Bullion Card](https://www.onegold.com/thebullioncard))

## Costs (snapshot 2026-10-09)

| Item | Amount |
|---|---|
| Buy premium, gold | 0.80% (US, Switzerland); 1.50% (Canada, UK) |
| Buy premium, silver | 2.00–3.50% by vault |
| Buy premium, platinum | 5.00% (products page); a help article says 3.70% |
| Sell fee | 0.30% (waived for card spending of US Gold) |
| Storage | 0.12% a year for gold; 0.30% for silver and platinum; minimum $5 a quarter |
| Funding | ACH free; card or PayPal 3.99%; crypto via BitPay 1.99% |
| Withdrawal | ACH free; wire $25 |
| Minimums | No minimum trade or account balance |

**The undisclosed cost is OneGold's own spread.** OneGold quotes one "spot" for buying (ask) and another for selling (bid) ([explanation](https://support.onegold.com/hc/en-us/articles/360016737711)). At about 17:20 UTC on 2026-10-09:

- OneGold's gold ask was $4,214.80 and its bid $4,153.80. An external market reference was about $4,195. That is about 0.5% above the reference and 1% below it.
- Adding the 0.80% premium, buying US Gold and then selling it costs about 2.3–2.5%.
- An earlier capture the same day showed ask/bid gaps of about 5% on silver and 3% on platinum.

None of this spread is presented as a fee.

## Ownership terms: contract vs. marketing

The [user agreement](https://www.onegold.com/useragreement) (effective 2024-01-10) is the contract:

- A customer "owns, and has title to, an interest in actual and tangible physical metal", held "in an allocated and pooled position".
- Holdings are a "financial asset" under Article 8 of the Uniform Commercial Code as adopted in Delaware, the body of law used for investment custody.
- "The sole relationship between ONEGOLD and you is that of buyer-seller." No agency relationship exists, and the agreement contains no bailment, trust or insolvency language.
- Customers have no relationship with APMEX, which acts for OneGold.
- OneGold "is not obligated to purchase your Digital Metal" and may cancel any order.
- Customer cash sits in a pooled account kept separate from OneGold's operating funds. It is not FDIC- or SIPC-insured, and OneGold may keep the interest.

Other OneGold statements differ:

- **Card page:** metal is "stored as allocated bullion under your name".
- **Help centre:**
  - a pooled holding "doesn't translate to a specific bar of metal" ([pooled](https://support.onegold.com/hc/en-us/articles/360017552852));
  - if OneGold went out of business, "you would receive the equivalent cash value of your metal holdings" ([article](https://support.onegold.com/hc/en-us/articles/360055771252)).
- **Help centre on cash:** one article says cash is held at Wells Fargo in an FDIC-insured account, which conflicts with the agreement's "not… eligible for deposit insurance".

**Assistant interpretation, not legal advice:** the UCC Article 8 wording likely keeps customer holdings away from OneGold's creditors. If there were a shortfall, customers would share it pro rata, and the help centre suggests a payout in cash rather than metal.

## Custody and audits

- **Vault operators:** APMEX and Manfra, Tordella & Brookes (MTB, part of the MKS PAMP group) in the US; MKS PAMP in Switzerland; the Royal Canadian Mint; Loomis in the UK. Brinks is also named. Much of this custody is with companies in the same corporate group as OneGold. ([Where products are stored](https://support.onegold.com/hc/en-us/articles/4402410781197))
- **Monthly statements:** OneGold [publishes custodian statements](https://www.onegold.com/inventory-audit) monthly. The October 2026 set includes:
  - US letters from APMEX and MTB, holding inventory "on behalf of OneGold, Inc. and its customers";
  - a Swiss gold "Gold Deposit Account Confirmation" from MKS PAMP addressed to APMEX LLC;
  - a Swiss silver bar report;
  - Royal Canadian Mint balance statements;
  - a UK bar list.
- **Total holdings:** these add up to roughly 2.2M oz across the three metals, about $300M. Marketing says "4M+ ounces under management".
- **Annual audit:** an unnamed "top 10" accounting firm performs a yearly count. No report was found. Nothing was found on audits of customer cash.
- **Insurance:** described as Lloyd's of London; limits and syndicates are not disclosed.

## Other capabilities

- **Trading:** buy or sell 24/7, including when markets are closed. Limit orders by target spot price and recurring AutoInvest. No order book.
- **Funding holds:** ACH funds can't be sold or withdrawn for up to 5 business days. Card, PayPal or ACH funds can't be used for physical redemption for 60 days.
- **Physical redemption:** sells your holding and buys any of 30,000+ APMEX retail products at a price OneGold sets. Ships in 1–2 business days, free in the US over $100. International shipping has a $250 minimum. This is a sell-and-rebuy, not delivery of your stored metal.
- **Transfers:** no transfers between users, no token and no transfer of metal elsewhere. IRAs are available only through outside custodians.
- **Tax:** "OneGold does not prepare or send year-end tax form 1099-B." Holdings show only an average cost. ([Article](https://support.onegold.com/hc/en-us/articles/360016270431))
- **Accounts:** individual accounts, with IRAs via outside custodians. A beneficiary form exists but is not a transfer-on-death designation. No joint, business or trust accounts found.
- **Geography:** most countries can open accounts, apart from an exclusion list. ACH and the card are US-only.
- **Disputes:** mandatory arbitration in Delaware, with class-action and jury waivers. The agreement names both Oklahoma and Delaware law.

## Compared with a token-based platform's published terms

The terms below are as published; this table says nothing about operational reliability.

| | OneGold | Kinesis |
|---|---|---|
| What you hold | An interest in pooled, allocated metal; a UCC Article 8 financial asset | KAU/KAG tokens, with Kinesis holding the metal as bailee ([terms](https://kinesis.money/about-us/documents/terms-of-use/)) |
| Storage | 0.12–0.30% a year | Free |
| Yield | None | Variable yields funded by fees |
| Trading fee | Premium plus the bid/ask "spot" gap, plus 0.30% to sell | 0.22% ([fees](https://kinesis.money/about-us/fees/)) |
| Physical redemption | Any APMEX product, no meaningful minimum | 0.45% + $100 + delivery; minimum 100 g gold or 200 oz silver |
| Card | Live; no rewards | In beta (support page, September 2026); 2% gold cashback on up to $2,000 a month is announced |
| Transfers | None | Native and on-chain transfers |

**Worked example: spending $2,000, buying the gold first** (prices at about 17:20 UTC on 2026-10-09):

- OneGold costs about $46–51, almost all of it spread and premium.
- The Kinesis card's announced terms would net about +$30: 0.22% to buy, 0.22% to convert and roughly 0.08% half-spread, minus 2% cashback.
- The comparison depends on a promotional cashback at its monthly cap, from a card not yet generally available. For someone already holding gold, only the selling side matters, and the gap narrows to about $50.

## Considerations for Apokatas

These are assistant proposals for later discussion, not decisions.

1. **Show the spread as a cost.** Show the price customers get against a named external reference, as well as any fee. A fee-free sale at a quoted "spot" well away from the market is a fee customers can't see.
2. **Make marketing match the contract.** Ownership, segregation and insurance language should be identical in marketing, help pages and terms. Explain plainly what happens to metal and cash if the operator fails.
3. **Publish every agreement before sign-up,** including card terms and fee schedules.
4. **Deliver the customer's metal, not a retail swap,** where that is practical. If redemption is a sell-and-rebuy, state the total cost.
5. **Use independent custody evidence.** Statements from companies in the same group as the operator are weaker evidence than independent audits or bar lists matched to customer holdings.
6. **Tax records are basic,** especially for money that is spent: each sale on a card can be a taxable event. Per-lot cost basis and exportable records belong in the core offering.
7. **A narrow service has fewer parties to serve** (see [who the service ends up serving](../rationale.md#who-the-service-ends-up-serving)). OneGold's income comes from premiums, spreads, storage and interest on customers' cash: costs the holder pays rather than shares paid to third parties. The trade-off is higher visible costs and no transfers, so it doesn't serve as everyday money between people.

## Evaluation criteria used

The user has previously compared metal-money services on these criteria, scoring each 0–10 by practical maturity:

- **0:** absent
- **1:** broadly discussed
- **2:** announced but not usable
- **3–5:** pilot, restricted, unreliable or incomplete
- **6–7:** workable minimum product
- **8–9:** strong
- **10:** unusually complete

| # | Criterion | OneGold score (2026-10-09) |
|---|---|---|
| 1 | Spot markets with simple trade execution | 7 |
| 2 | Quick and easy fiat deposits and withdrawals | 7 |
| 3 | Simple, timely and affordable physical redemption | 7 |
| 4 | Regular, frequent and trustworthy metal and fiat audits | 5 |
| 5 | Free storage plus a reliable yield system | 1 |
| 6 | Physical and digital debit cards | 7 |
| 7 | Clean and intuitive interfaces | 7 |
| 8 | Quality customer support | 6 |
| 9 | Automated tax reporting | 1 |
| 10 | Personalized/named bank accounts | 0 |
| 11 | Legal ownership and bankruptcy remoteness | 5 |
| 12 | Fees, spreads and minimums | 5 |
| 13 | Insurance, custody, vaults and security | 7 |
| 14 | Geographic availability and eligibility | 6 |
| 15 | Transferability and interoperability | 1 |
| 16 | Supported metals and backing model | 7 |
| 17 | Liquidity, execution quality and price transparency | 5 |
| 18 | Regulatory status and user protections | 6 |
| 19 | Lending and borrowing | 1 |
| 20 | Platform maturity, outages and unresolved limitations | 7 |
| 21 | Account types and ownership options | 4 |

The scores are the assistant's, made with LLM help from public evidence. Criteria 5 and 19 reflect features OneGold deliberately does not offer. A low score there is not a defect for a service that chooses not to offer yields or lending. The criteria are a candidate checklist for assessing Apokatas itself and any custody provider, not adopted requirements.

## Limits

- Several OneGold help articles have not been updated since 2018–2021. Where a help article conflicted with the user agreement, the agreement was preferred.
- State money-transmitter licensing was not checked. No FinCEN money-services registration was found; a precious-metals dealer may not need one.
- OneGold is not an API or white-label provider, and its customers have no relationship with its custodians, so it is not a provider lead for Apokatas. Its suppliers are noted in [provider leads](provider-leads.md).
