# NFTeria

**An independent builder. Its current product is UNICA.**

## UNICA — merchant settlement on Uniswap v4

UNICA is an MIT-licensed settlement hook and modular integration layer for Uniswap v4.
A payer pays in one currency, a recipient receives another, in one transaction, through
Uniswap's official Universal Router, into a pool whose hook admits a swap only on that
path and only for a registered order, and which emits a versioned receipt.

**UNICA is testnet only. There is no mainnet deployment and no real value at risk. No
part of it has been audited.**

| | |
|---|---|
| Code | [github.com/NFTeria/UNICA](https://github.com/NFTeria/UNICA) — MIT |
| App | [nfteria.github.io/UNICA](https://nfteria.github.io/UNICA/) |
| About | [nfteria.github.io](https://nfteria.github.io) · [nfteria.click](https://nfteria.click) |

Built on Uniswap v4, ENSv2 on Sepolia, and The Graph. NFTeria is an independent builder;
UNICA is not commissioned by, affiliated with, endorsed by, or reviewed by Uniswap or any
other ecosystem named here.

### Every release at the rung it has actually reached

| Release | State | What is true |
|---|---|---|
| **V1** | live, testnet | Live on Ethereum Sepolia. Source-verified on Sourcify as a partial match. One settlement: 0.001 ETH in, 2.003660 USDC out. |
| **V2** | blocked | Written and frozen as rc1, deployed nowhere. Held back by an internally identified Critical finding, published as Security Advisory 001. |
| **V3** | live, testnet | Settled on Ethereum Sepolia: 0.001 ETH in, 2.216294 USDC out. A second settlement ran in a browser, where the merchant was a name, `nfteria.eth`, resolved on ENSv2 Sepolia and shown to the payer before signing. Deployed and source-verified at one address on Ethereum, Unichain, Base and Arbitrum Sepolia; it has settled only on Ethereum Sepolia. |
| **Experimental** | testnet, outside the release line | One order settled on Robinhood Chain testnet (chain 46630) on 2026-09-11 through a separate experimental hook: 0.001 Robinhood test TSLA in, 0.393052 uTUSD out. Robinhood test tokens have no real-world value, and neither does uTUSD. There is no oracle in that path, and its source is not verified on the explorer. |
| **v4** | designed | Being designed. Not built, not deployed. It will be a separate deployment with its own addresses, not an upgrade of anything above. |

"UNICA v4" is a UNICA release name. It is not Uniswap v4, the AMM UNICA is built on.

## Earlier work

**[Access0x1](https://github.com/Access0x1/Access0x1)** — built for ETHGlobal New York and
ETHGlobal Lisbon. An MIT-licensed, non-custodial rail for onchain identity and USD-priced
payments in USDC, with a merchant layer over it. Its own repository states where it
stands: **testnets only, no mainnet deployment, no token**, and a first-party self-audit
by its maintainer rather than an external audit. UNICA is separate work, written from
scratch, and shares no code with it.

## This repository

Organization files only: this profile page, the security policy, and the privacy
statement. Product code lives in its own repository.
