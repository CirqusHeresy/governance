# Treasury

Every address that holds the Order's funds is listed here. If an address is not on this page, it is not the Order's.

| Purpose | Chain | Address | Control |
|---|---|---|---|
| Temple NFT contract | Base | [`0xe7922d3Ed1EA62466da8589cc7Fe2a111f66CaEF`](https://basescan.org/address/0xe7922d3Ed1EA62466da8589cc7Fe2a111f66CaEF) | Contract owner — see protocol issue #1 |
| Treasury (interim) | Base, Ethereum | **cirqus.eth** — [`0x232429a07704D0aeD7e795e882dF5De05dC33091`](https://basescan.org/address/0x232429a07704D0aeD7e795e882dF5De05dC33091) | Founder-held hardware wallet, single signer |

> ⚠️ **Interim arrangement.** Until the multisig exists, the Order's funds are held in the founder's hardware wallet. This address is also the founder's personal wallet, so not every asset or movement on it belongs to the Order — every Order-related movement is listed in [`../reports/`](../reports/).

## Rules

- Target setup: a Safe multisig on Base, **2-of-3** at start; the current hardware wallet becomes one of its signers. Signers are listed publicly by role.
- Once the Safe exists, cirqus.eth will point to it and this page will be updated in the same pull request.
- Until then, funds are held by the founder and every movement is reported in [`../reports/`](../reports/).
- Spending from the treasury is a decision of both chambers once they are constituted.
