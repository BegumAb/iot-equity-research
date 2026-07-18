# Samsara (NYSE: IOT) — "The Fade Is Too Aggressive"

An interactive 3D equity research presentation arguing a **LONG** in Samsara: the market is pricing a growth fade that the operating evidence does not yet support.

**▶ View it live: [begumab.github.io/iot-equity-research](https://begumab.github.io/iot-equity-research)**

*Begüm (Victoria) Abanonu · Equity Research · July 2026*

---

## The thesis

> The market is right that basic telematics commoditizes — wrong to assume Samsara fades like pure telematics.

| | View |
|---|---|
| **Market view** | Samsara is fleet telematics. Features reach parity, Motive and Geotab compete on price, revenue growth fades 24% → 19.6% → 18.6%, and the multiple de-rates 13.7x → 9.8x NTM revenue. |
| **My view** | Samsara is becoming an **embedded physical-operations system**. One install supports 5+ departments, multi-product expansion deepens the installed base, and physical switching costs slow the fade. |

**I do not need growth to avoid fading. I only need a slower fade.** The base case cuts net-new ARR growth from +27% LTM to +15% / +5% — and still lands FY28 revenue **6.5% above Street**.

## Debate 1 — Does growth fade?

Net-new ARR growth, year over year:

| Q1 FY26 | Q2 FY26 | Q3 FY26 | Q4 FY26 | Q1 FY27 |
|---|---|---|---|---|
| 5% | 19% | 24% | 33% | 30% |

Three quarters of acceleration followed by a still-strong 30% print — the leading indicator has not faded.

Supporting evidence: core NRR ~115% · 96% of $100K+ customers use 2+ products · 70% use 3+ · $100K+ ARR mix 56% → 62% · average large-customer ARR $338K → $365K.

## Debate 2 — Commoditization and new logos

Two separate battles, and the thesis concedes one of them.

- **Installed base — protected.** Hardware uninstall and reinstall are paid twice; deployment can take up to 12 months for a mid-size fleet; historical coaching data is difficult to transfer; insurance, TMS and workflow integrations must be rebuilt.
- **New logos — must earn the premium.** *Conceded:* Motive's 30–40% lower price is a real risk in compliance-only SMB. But 9 of the top-10 new-logo deals included 2+ products and 4 of 10 included 4+.

| Buyer | Priority | Advantage | Thesis impact |
|---|---|---|---|
| Compliance-only / SMB | Lowest price | Motive | Real risk |
| Workflow / safety / enterprise | ROI, insurance, integration, multi-product breadth | Samsara | Where the long is strongest |

## Debate 3 — Does the margin break?

Q1 FY27 COGS decomposition, from the filings: of a **+$34.5M** total COGS increase, device amortization was **+$6.9M (~20%)** and non-device **+$27.6M (~80%)** — cloud/AI, support, cellular, warranty.

Memory (NAND/DRAM) sensitivity, labeled as estimate: **base ≈ flat · high ≈ −54bps · stress ≈ −100bps**. Samsara's memory share of device BOM is **not disclosed** — industry and teardown proxies used. Device cost amortizes over five years, so the P&L sees a phased drip blended with cheaper vintages.

## Expert checks

Two customers, one competitor, one former insider — the bear evidence carries equal weight.

- **Customer stickiness** — logistics operator, 283 trucks, pays a 12–15% premium and renewed: switching would be difficult and risky.
- **ROI / must-have** — construction fleet, ~550 vehicles, low-double-digit insurance premium reduction.
- **Competitor concession** — a fleet-software rival on hardware installation, downtime and layered integrations making telematics sticky.
- **The real bear case** — former insider, now at a competitor: pure telematics is commoditizing and features are copied quickly. **This is the Tier-1 risk.**

## Valuation

| Scenario | NN ARR FY27 / FY28 | FY28 Revenue | FY28 EPS | Exit NTM P/E | Target | Weight |
|---|---|---|---|---|---|---|
| Bear | −20% / −30% | $2,180M | $0.74 | 35x | **$27.3** (−27%) | 25% |
| Base | +15% / +5% | $2,560M *(Street $2,404M)* | $0.97 *(Street $0.89)* | 45x | **$43.8** (+17%) | 50% |
| Bull | +25% / +15% | $2,720M | $1.06 | 52x | **$55.4** (+48%) | 25% |

Spot **$37.51** · probability-weighted **$42.58 (+13.5%)** · **Bull/Bear payoff 1.7x** (bull upside ÷ bear downside — labeled precisely, not a generic reward/risk figure).

The trade is driven by **estimate revisions, not multiple expansion.** Catalysts: September 3 print · December 3 print · FY27 tiered-pricing renewals. Data-center and regulation optionality are **not** included in the base case.

## What breaks the long — pre-committed kill criteria

1. **Thesis risk:** commoditization outruns multi-product expansion — new-logo pressure and expansion both weaken.
2. **Operating risk:** gross margin continues to compress despite flat guidance.
3. **Valuation risk:** the multiple de-rates before estimates revise upward.

**Kill lines:** net-new ARR growth below **+10% for two consecutive quarters** · core NRR below **~112%** · continued gross-margin compression against the flat guide.

**First public test: September 3, 2026.**

> The hardware is real. The workflows are sticky. But the long only works if the KPIs confirm a slower fade.

## Appendix — the NAND short thesis

Not undiscovered; magnitude remains the debate. The inflation is conceded in full: contract prices rose Q4 +33–38%, Q1 +55–60%, Q2 +70–75% (TrendForce), and visibility on supply shortened to a couple of quarters per the CFO in June.

What remains unproven: Samsara's *realized* cost (contracted and pre-bought, not spot), memory's share of device BOM (undisclosed by Samsara and every peer, verified), affected device volume, timing through five-year amortization, and any margin or EPS miss beyond guidance.

**Verdict: industry risk, not yet company-specific alpha.** The bridge question stands — walk from the part quote to an FY27 gross-margin and EPS miss through part spec, BOM share, realized price, unit volume and amortization. Graded September 3.

---

## Technical notes

Single self-contained HTML file — no build step, no dependencies, no network calls. Three.js (r128) is inlined so the presentation runs fully offline.

- One continuous 3D world across 9 chapters plus a Q&A appendix, navigated by camera moves rather than slide cuts
- Custom canvas-generated textures; label safe-zone clamping with leader lines; presenter notes and timer
- **Graceful degradation:** if WebGL is unavailable or disabled, the deck drops to a built-in **static view** carrying the same content rather than failing

**Controls:** `→` / `space` next · `←` back · `1–9`, `0` chapters · `F` fullscreen · `N` NAND Q&A · `P` notes · `H` hide UI · `S` screenshot · `R` reset

Best viewed in current Chrome, Edge, Firefox, or Safari with hardware acceleration enabled.

---

*Prepared as an equity research work sample. Figures reflect the author's own estimates and scenario weights. Not investment advice.*
