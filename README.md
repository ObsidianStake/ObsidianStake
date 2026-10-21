<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/forge-dark.svg?v=2" width="100%" alt="Obsidian Stake: forged in the block">

```console
$ obsidian --whoami
  guild      Obsidian Stake
  signs      cosmoshub · zetachain · cheqd · celestia (mocha)
  serves     fibre
  watches    26 chains across 7 forges
  front      TIA, live
  runs on    bare metal
```

A validator guild that signs blocks and builds its own instruments: a chronicle of what chains actually ship, and a battlefield that shows a market's mood without a single chart.

<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/divider.svg" width="100%" alt="">

## I · The Grid

The chains the guild signs for. Commission, uptime and every governance vote are on-chain, so the explorer is the source of truth, not this page.

| Network | Layer | Validator |
|:--|:--|:--|
| **Cosmos Hub** | Mainnet · ATOM | [`cosmosvaloper17p68…p6l53`](https://www.mintscan.io/cosmos/validators/cosmosvaloper17p68pwmc9kve6xqt0al5mnfak82dy53w6p6l53) |
| **ZetaChain** | Mainnet · ZETA | [`zetavaloper10rsf…z6ycyq`](https://ping.pub/zetachain/staking/zetavaloper10rsfgjpc70myjlv3d252mmsewxucseh4z6ycyq) |
| **cheqd** | Mainnet · decentralized ID | [`cheqdvaloper1y64h…t9m0n2`](https://explorer.nodestake.org/cheqd/staking/cheqdvaloper1y64hp0y5qlau3afnxaqu2lzhnnd3qpfqt9m0n2) |
| **Celestia** | Testnet · Mocha · Fibre | [`celestiavaloper17awy…a44vx24`](https://celestia-dashboard.krews.xyz/celestia-mocha/validators/celestiavaloper17awy8avky6rmnxketpf46dywegd86sla44vx24) |

**Fibre on Mocha.** Celestia's Fibre is a new data availability lane served by validators themselves: each one runs a Fibre server and registers its host on-chain. Our Mocha validator runs one, so the guild is already part of that path while Fibre is tested ahead of mainnet.

<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/divider.svg" width="100%" alt="">

## II · Emberwatch

<a href="https://obsidianstake.xyz/emberwatch/"><img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/emberwatch.svg" width="100%" alt="Emberwatch"></a>

Node and protocol releases, read straight from the repositories of 26 chains across 7 forges: modular & DA, parallel EVM, Move L1s, ZK, cross-chain, decentralized AI, DEX chains. Each entry says what changed: patch or minor, pre-release or not, whether it touches consensus or the RPC surface. No press-release paraphrasing.

The chronicle is plain JSON underneath. Point a bot at it:
[`articles.json`](https://obsidianstake.xyz/emberwatch/api/articles.json) every release, newest first ·
[`projects.json`](https://obsidianstake.xyz/emberwatch/api/projects.json) chains and their repos ·
[`categories.json`](https://obsidianstake.xyz/emberwatch/api/categories.json) the forges ·
[`market.json`](https://obsidianstake.xyz/emberwatch/api/market.json) prices behind the ticker

**→ [obsidianstake.xyz/emberwatch](https://obsidianstake.xyz/emberwatch/)**

<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/divider.svg" width="100%" alt="">

## III · Celestia Fights

<a href="https://obsidianstake.xyz/fightarea"><img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/fightarea.svg" width="100%" alt="Celestia Fights"></a>

The live TIA trade stream, turned into a battle on a purple planet. Every buy sends a soldier from one side, every sell from the other, and the front line moves with the order flow. Orbit view for the whole planet, surface scan for the trenches.

**→ [obsidianstake.xyz/fightarea](https://obsidianstake.xyz/fightarea)**

<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/divider.svg" width="100%" alt="">

## IV · The Anvil

1. **Bare metal, not rented cloud.** Sentry nodes face the network; the signer stays behind them.
2. **Keys never touch a public host.** Remote signing through TMKMS with double-sign protection.
3. **Every node is watched.** Prometheus and Grafana, alerts on missed blocks, peers, disk and height lag.
4. **Upgrades are rehearsed.** Testnet first, then applied at the governance height, not before.

<sub>Linux · Docker · TMKMS · Prometheus · Grafana · Ansible · Go · Python</sub>

<img src="https://raw.githubusercontent.com/ObsidianStake/ObsidianStake/main/media/divider.svg" width="100%" alt="">

## V · The Pact

> *Through fire, the stone is tempered. Through code, the network is secured.*

[obsidianstake.xyz](https://obsidianstake.xyz/) · [Instagram](https://www.instagram.com/obsidianstake) · [TikTok](https://www.tiktok.com/@obsidianstake)


