# C2 Skyworld — Engine Fleet & Performance Evidence

## Reading this document

**Historical / developed** means a capability or result has been reported from previous work; **isolated qualified** means specific tests passed within a defined boundary; **V7 in progress** means integration or acceptance is outstanding; **roadmap** means an intended capability, not a delivered feature.

## Engine fleet catalogue

| Segment | Engines / components | Public status statement |
| --- | --- | --- |
| Multi-asset markets | Forex, Metals, Commodities, ETFs, Stocks | Portfolio catalogue; individual maturity and test coverage vary. |
| Execution strategies | Arbitrage, Scalp, Liquidity, Downward Trend | Previous Engine migration work reported; integrated V7 qualification is not established here. |
| Extended strategies | Copy, Grid, Momentum, HFT | Listed in platform licensing and roadmap catalogue; no production claims. |
| Derivatives | Crypto Futures, Futures, Options, Indices | Listed in platform catalogue; no production claims. |
| Decentralised | Web3 / DEX | Cross-chain and DEX readiness is an architectural requirement; no production claims. |
| Intelligence | Whale, Research, Symbol Market Scanner | Existing intelligence groundwork and V3 upgrade plan; maturity differs by component. |

## Evidence ledger — examples currently available

| Evidence ID | Subject | Result | Scope / limitation |
| --- | --- | --- | --- |
| TR-001 | EULUSDT historical example | +8.50 USDT on 150 USDT over 41.87 hours; +5.67% reported return | Single example; exchange, fees, drawdown and complete trade ledger not independently validated for publication. |
| ENG-001 | UAM Batch 19 | Windows MSVC build PASS; CTest 12/12 PASS | Isolated qualification; not an end-to-end production sign-off. |
| ENG-002 | UAM Batch 05 | 27/27 automated assertions PASS | Scoped exchange-connection registry and policy checks; not full platform acceptance. |
| ENG-003 | Market Scanner | V2 groundwork operational in earlier testing | Scanner V3 not yet designed/built as a completed product. |
| ENG-004 | Investment Management | Adapter compile attempt failed on missing `core/runtime/service_runtime.hpp` | No executable produced; must not be labelled PASS. |
| ENG-005 | VertexFX | Read-only connectivity and schema validation reported | Live account; no live order endpoints authorised in qualification. |

## Metals, Forex and Commodities — publication slots

Historical test evidence is known to exist, but the complete verified trade ledgers and test reports are not included in this public draft. Do not insert aggregate profits, win rates, drawdowns, number of trades, annualised returns or comparative rankings until supported by approved source records.

| Engine | Test window | Trades | Net P&L | Return | Max drawdown | Fees included? | Evidence reference | Publication status |
| --- | --- | ---: | ---: | ---: | ---: | --- | --- | --- |
| Metals | Pending approved records | — | — | — | — | Unknown | Pending | Not yet verified for public release |
| Forex | Pending approved records | — | — | — | — | Unknown | Pending | Not yet verified for public release |
| Commodities | Pending approved records | — | — | — | — | Unknown | Pending | Not yet verified for public release |
| ETFs / other Engines | Pending approved records | — | — | — | — | Unknown | Pending | Not yet verified for public release |

## Assessment comparison — do not present as external benchmark

| Measure | Historical figure | Post-upgrade target | Verification |
| --- | --- | --- | --- |
| Internal maturity assessment | 81/100 (reported previous assessment) | 100/100 (proposed scenario) | Methodology, criteria and final qualification evidence must be supplied before asserting a verified outcome. |

## Evidence publication checklist

Before publishing performance statistics, confirm the originating report, date range, instrument, account mode (simulation/demo/live), initial capital, gross and net P&L, fees, trade count, drawdown, risk exposure, test conditions, and permission to disclose. Distinguish backtests, forward tests, paper trading and live trades. Remove account identifiers, API credentials and any confidential strategy details.

## Roadmap and acceptance boundary

The V7 upgrade is intended to strengthen shared broker infrastructure, UAM, Investment Management, Scanner V3, licensing and safety controls. Standalone safety, reconciliation, no-duplicate execution, risk gates and live-mode authorisation remain mandatory acceptance conditions. Passing an isolated test does not imply platform-wide production readiness.

**© 2026 C2 Skyworld. All rights reserved.**
