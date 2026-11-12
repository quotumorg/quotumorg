<p align="center"><a href="https://quotum.org"><img src="https://quotum.org/favicon.svg" width="76" alt="quotum: the ice Q"></a></p>

<h1 align="center">quotum</h1>

<p align="center"><b>Hermes Agent plugins · an x402 facilitator on Robinhood Chain · a hundred seats on the Venice API</b></p>

<p align="center">
<a href="https://quotum.org/facilitator"><img alt="x402 facilitator network, read live from pay.quotum.org/supported" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fpay.quotum.org%2Fsupported&query=%24.kinds%5B0%5D.network&label=x402%20facilitator&color=4b3bb0&style=flat-square"></a>
<a href="https://quotum.org/usage"><img alt="bells rung" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fquotum.org%2Fbells.json&query=%24.latestCompleted&label=bells%20rung&color=180b51&style=flat-square"></a>
<a href="https://x.com/quotumorg"><img alt="X @quotumorg" src="https://img.shields.io/badge/X-%40quotumorg-0b0b0b?style=flat-square&logo=x&logoColor=white"></a>
<a href="https://quotum.org/discord"><img alt="Discord" src="https://img.shields.io/badge/Discord-quotum-4b3bb0?style=flat-square&logo=discord&logoColor=white"></a>
</p>

<p align="center"><sub><a href="https://github.com/pulls?q=is%3Apr+author%3Aquotumorg+is%3Amerged">12 pull requests merged</a> in other teams' repos, among them Hermes Agent, Built in Venice and DefiLlama · 4 Hermes plugins · a public census of x402 on Robinhood Chain</sub></p>

## plugins

| plugin | what it does · install |
|---|---|
| **[rh-preflight](https://github.com/quotumorg/rh-preflight)**<br><img alt="release" src="https://img.shields.io/github/v/release/quotumorg/rh-preflight?style=flat-square&label=&color=180b51"> | reads public records from HEY Research Lab and ten Robinhood Chain projects, then applies your go / ask / stop rules before Hermes acts. ask waits for your answer. never signs or pays. built with [HEY Research Lab](https://github.com/hey-research-lab), off until you enable it<br>`hermes plugins install quotumorg/rh-preflight --no-enable` |
| **[precedent-log](https://github.com/quotumorg/precedent-log)**<br><img alt="release" src="https://img.shields.io/github/v/release/quotumorg/precedent-log?style=flat-square&label=&color=180b51"> | you answer a Hermes Kanban worker's question once, later workers reuse your ruling instead of asking again<br>`hermes plugins install quotumorg/precedent-log --enable` |
| **[exfilbar](https://github.com/quotumorg/exfilbar)**<br><img alt="release" src="https://img.shields.io/github/v/release/quotumorg/exfilbar?style=flat-square&label=&color=180b51"> | checks uploads Hermes starts from terminal or Python against the routes you allow and blocks off-route ones. not a sandbox<br>`hermes plugins install quotumorg/exfilbar --enable` |
| **[hermes-quotum](https://github.com/qvotvm/hermes-quotum)**<br><img alt="release" src="https://img.shields.io/github/v/release/qvotvm/hermes-quotum?style=flat-square&label=&color=180b51"> | a quotum seat or prepaid project as a Hermes model provider. `hermes usage` shows cap, spend and time to the bell<br>`hermes plugins install qvotvm/hermes-quotum --enable` |

community plugins for Hermes Agent, not made by Nous Research. separate from the four: [hermes-team-kit](https://github.com/qvotvm/hermes-team-kit), a Hermes team that can't approve its own work.

## x402 facilitator

point an x402 seller at `https://pay.quotum.org`. it verifies and settles x402 v2 payments in USDG on Robinhood Chain (eip155:4663, scheme exact). the buyer pays the seller directly, and the pilot terms set no fee. terms and signup at [quotum.org/facilitator](https://quotum.org/facilitator).

[quotum.org/x402](https://quotum.org/x402) is a public census of x402 settlements on Robinhood Chain, by facilitator: 23,573 in the 30 days to 12 Nov 2026.

## merged

the main ones, 2026:

- **Hermes plugin catalog** · exfilbar [#151980](https://github.com/NousResearch/hermes-agent/pull/151980) (10 Nov) · precedent-log [#150678](https://github.com/NousResearch/hermes-agent/pull/150678) (8 Nov) · quotum 0.3.1 [#149918](https://github.com/NousResearch/hermes-agent/pull/149918) (8 Nov) · quotum provider [#132910](https://github.com/NousResearch/hermes-agent/pull/132910) (5 Oct)
- **Built in Venice** · quotum in the directory [#198](https://github.com/veniceai/builtinvenice/pull/198) (5 Nov)
- **DefiLlama** · quotum fees on Robinhood Chain [#10052](https://github.com/DefiLlama/dimension-adapters/pull/10052) (10 Oct)

in review: rh-preflight in the Hermes plugin catalog, [#153679](https://github.com/NousResearch/hermes-agent/pull/153679).

## seats

a hundred seats for private and anonymized models via the Venice API, paid for by trading tax. the chart, the mechanism and governance live at [qvotvm](https://github.com/qvotvm).

<details>
<summary>the bell, last two weeks</summary>
<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qvotvm/.github/main/profile/bells-dark.svg">
  <img alt="inference spent and QUOTUM burned, per bell" src="https://raw.githubusercontent.com/qvotvm/.github/main/profile/bells-light.svg" width="100%">
</picture>
</details>

<p align="center"><sub><a href="https://quotum.org">quotum.org</a> · <a href="https://quotum.org/docs">docs</a> · <a href="https://x.com/quotumorg">X</a> · <a href="https://quotum.org/discord">Discord</a> · <a href="https://t.me/qvotvm">Telegram</a> · issues go to each repo</sub></p>
