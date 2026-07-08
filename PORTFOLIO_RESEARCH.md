# Portfolio Research Tracker

**Last updated:** Jul 8, 2026 — VERA → CAPR rotation planned; AdCom lotto rules set  
**Account:** Robinhood individual margin ••••8849  
**Purpose:** Living doc for trade ideas, triggers, and portfolio rules.

> Not financial advice. Research for exploration only.

---

## Trading rules (confirmed)

- **Do not sell at a loss.** Hold until green; exceptions: broken thesis (e.g. ADBE) or **defined pharma binary** (CAPR AdCom — exit on event outcome even at loss).
- **QQQ is a stabilizer of last resort** — deploy cash there only when no compelling theme/opportunity exists.
- **Rotation pattern:** Sell green non-core positions → buy obliterated conviction names on dip days (e.g. Jul 2: AAPL → DRAM/SOXX/NBIS).
- **DRAM/SOXX are core holds** — do not trim for rebalancing.
- **Margin note:** Buying power ~$475 as of Jul 6 ($237 unleveraged). New buys require green rotation or deposit — not more margin.

---

## Account snapshot (Jul 6 EOD)

| Metric | Value |
|--------|-------|
| Net account value | ~$7,066 |
| Gross equity | ~$15,068 |
| Margin debt | -$8,105 |
| Buying power | ~$475 ($237 unleveraged) |
| 3mo realized P&L | +$2,494 |
| Open unrealized P&L | ~-$2,056 |

---

## Portfolio framework (thesis buckets)

| Bucket | Target weight | Current (Jul 6) | Holdings |
|--------|---------------|-----------------|----------|
| Memory (DRAM) | 25–35% | **~44%** ⚠️ | DRAM |
| Semis (SOXX) | 10–15% | ~9.5% ✓ | SOXX, AVGO |
| Optoelectronics | 3–7% | ~5.0% ✓ | AAOI |
| SaaS | 8–12% | ~6.0% | MSFT, NOW |
| Neo-Cloud | 5–10% | ~9.2% ✓ | NBIS |
| Hyperscaler capex | 5–10% | ~13.5% | GOOGL, AMZN |
| EV | 3–5% | ~3.2% ✓ | TSLA |
| Streaming | 3–5% | ~2.5% | NFLX |
| Stabilizer (QQQ) | 30–40% (when idle) | ~4.7% | QQQ |
| Leverage (RAM) | 0% | ~1.3% | RAM — hold until green, then exit |
| Pharma satellite | 0–2% | ~1.0% (planned) | CAPR (AdCom lotto; 3 shares) |

**SaaS hedge thesis:** DRAM down days → MSFT/NOW flat/up (validated Jul 2: DRAM -7.9%, MSFT +1.6%, NOW +0.5%).

---

## Open positions (Jul 8 — planned after Wed open)

| Position | Detail |
|----------|--------|
| **DRAM** | 111 shares @ $71.40 avg; ~$60 area post-Samsung (Jul 7) |
| **Short DRAM Jul 31 $80C** | 1 contract @ $2.30 credit ($230); 100 shares covered, 11 unhedged |
| **VERA** | 1 share @ $40.99 — **SELL Wed Jul 8 open** (PDUFA done; FDA approved Jul 7) |
| **CAPR** | **BUY 3 shares** Wed Jul 8 — limit **$22.00–22.50**; ~$66 notional (~1% equity) |

**Pharma satellite:** Rotate VERA proceeds → CAPR. Optional **4th share** only on dip **≤ ~$21.50**.

---

## CAPR trade plan (AdCom lotto — Jul 29, 2026)

**Thesis:** Tier A volatility binary — CTGTAC reviews deramiocel BLA. Not holding for analyst PTs ($38–62); holding for **Jul 29 panel outcome**. PDUFA Aug 22 is a separate trade unless 1 share kept after slam-dunk win.

**Entry (Jul 8):**

| Field | Plan |
|-------|------|
| Size | **3 shares** (4th only on better price) |
| Order | Limit **$22.00–22.50** — do not chase >$23 |
| Funding | Sell VERA at open → deploy proceeds |
| Max risk | ~$66–88 (full stub = acceptable lotto loss) |

**Catalyst calendar:**

| Date | Event |
|------|--------|
| Jul 11 | CORT PDUFA — sector noise; ignore unless gift entry on CAPR |
| **Jul 29** | **FDA AdCom (CTGTAC)** — **primary exit event** |
| Aug 22 | PDUFA — only relevant if shares kept after clean Jul 29 win |

**Rule:** Jul 29 is decision day. Default = **flat after event** unless explicitly keeping 1 share for Aug binary.

### Jul 29 sell playbook

```
Jul 29 AdCom
│
├─ Clear POSITIVE vote + stock up big (+15%+, e.g. $25+)
│     → SELL ALL 3 same day into rip, or next open if huge gap
│     → Exception: keep 1 / sell 2 only if vote unambiguous AND accept Aug PDUFA risk
│
├─ Clear NEGATIVE vote + stock down big (−15%+, e.g. <$19)
│     → SELL ALL 3 same day (or next open if halt)
│     → Do not hold to Aug PDUFA on broken AdCom thesis
│
└─ Mixed / flat / confusing (±5% chop, no clear vote)
      → SELL ALL 3 by Jul 29 close (default)
      → Or sell 2 + keep 1 with mental stop at entry (~$22)
```

| Outcome | Example (3 @ $22) | Action |
|---------|-------------------|--------|
| **Upside** | Sell 3 @ $28 → **~+$18** (+27%) | Sell all — lotto leg done |
| **Downside** | Sell 3 @ $15 → **~−$21** (−32%) | Sell all — bet didn’t work |
| **Muddy** | Unchanged | Sell all by close — don’t babysit |

**Aug PDUFA (only if shares remain):** Sell all remaining on PDUFA headline (approval pop or CRL). Do not let Aug become “forgot to sell in July.”

**Reference:** Full catalyst + options context in `PHARMA_CATALYST_TRACKER.md`.

---

## Mon Jul 6 trades (completed)

| Action | Detail |
|--------|--------|
| Sold **1× DRAM Jul 31 $80C** | @ **$2.30** ($230 credit) — near local high ~$65 |
| Sold **0.883 DRAM** | Trim at rip; 111 shares remain |
| Bought **1 VERA** | @ **$40.99** at close — pharma lottery stub |
| Skipped GEV / CRDO | Margin too tight (~$475 BP); correct call |

**Post-trade note:** Samsung earnings pulled DRAM to ~$60 AH (-6.5% from Fri close). Covered call is deep OTM; premium locked.

---

## Tue Jul 7 trades (completed)

| Action | Detail |
|--------|--------|
| Sold DRAM $80C (BTO) | @ $1.20 — +$110 vs Mon $2.30 sale |
| Re-sold DRAM $80C | @ $1.33 — new short; 111 sh, 100 covered |
| Sold VERA | @ $41.75 ~10:33 AM — **before** FDA approval PR |
| Re-bought VERA | @ $42.89 evening — paid up after missing midday pop |
| PENG lotto | Buy $61.90 → sell $68.11 ~+1 hr |
| BTC trim | Small loss |

**VERA PDUFA (Jul 7):** FDA **approved** TRUTAKNA. Stock +7% close (~$43); peak intraday ~+11%. IV ±25% was two-way width — Tier C, not lotto. **Exit Wed Jul 8** — thesis complete.

---

## Wed Jul 8 trades (planned)

| Action | Detail |
|--------|--------|
| **Sell VERA** | At open — market or limit near quote; take profit or small loss |
| **Buy CAPR ×3** | Limit $22.00–22.50; optional 4th ≤ ~$21.50 |

---

## Upcoming catalysts (memory)

- **Jul 7** — Samsung earnings (DRAM already reacting AH ~$60)
- **Jul 10** — SK Hynix ADR earnings
- **Jul 31** — DRAM $80C expires; assignment trims to 11 shares if DRAM > $80

## Upcoming catalysts (pharma satellite)

- **Jul 29** — CAPR FDA AdCom (primary exit — see sell playbook)
- **Aug 22** — CAPR PDUFA (only if shares held after clean AdCom)

---

## Filter for NEW ideas (H2 2026 → 2027 hypergrowth)

**Goal:** Find the next MU/SNDK-shaped names for **100–500% over 1–2 years** — not “cheap PE,” not “already done.”

**SNDK lesson:** Best stock of 2025 still did **600%+ in 2026**. Already-ran is fine if backlog/EPS still compound.

**Hard excludes:** Memory. Names already owned (NBIS, AAOI, AVGO, MSFT, NOW, GOOGL, AMZN, TSLA, NFLX, SOXX, QQQ, RAM, DRAM, CAPR).

**Must pass:**

| # | Rule |
|---|------|
| 1 | **Bottleneck** still binding into 2027–28 (sold-out / multi-year backlog / physics) |
| 2 | **Hyperscaler / AI capex** still rising into that bottleneck |
| 3 | **EPS still exploding or about to** (beats + rising estimates) |
| 4 | Real business (profitable) |
| 5 | Holdable **5–15%** |

Kill switches: estimate cuts for months, backlog cancellation, thesis death — not “stock already up.”

---

## Committed hypergrowth sleeve — H2 2026 through 2027

**Thesis:** Power is the binding constraint on AI. Own the scarce layers that convert hyperscaler capex into working campuses. EPS compounds as backlog converts; multiple can expand again (SNDK pattern).

### Tier A — highest conviction (build here first)

| Rank | Ticker | ~Price | Bottleneck | Why it can keep exploding | EPS proof |
|------|--------|--------|------------|---------------------------|-----------|
| **1** | **GEV** | ~$1,110 | **Gas turbines + transformers/grid** sold out through **~2028**; ~$163B backlog → $200B target | Power is the wall. No campus without MW. Pricing power on scarce slots. | Est climbing ($3.20 / $4.33); backlog conversion = multi-year EPS |
| **2** | **VRT** | ~$300 | **Rack power + liquid cooling** (100–140 kW racks) | Heat is physics. Every dense AI rack needs this. | EPS compounding; est $1.42 / $1.79 |
| **3** | **FIX** | ~$1,740 | **DC MEP install** capacity | Who wires/cools the building. Labor/capacity scarce. | **$4.09 → $10.51**; est still ~$10–11 |
| **4** | **STRL** | ~$700 | **DC site development** (E-Infrastructure) | Smaller cap (~$21B) = more torque. Builds the dirt/pad for campuses. | **$1.46 → $3.59**; est **$5.23 / $5.79** |

### Tier B — same stack, more torque / diversify

| Rank | Ticker | Bottleneck | EPS proof | Notes |
|------|--------|------------|-----------|-------|
| **5** | **CRDO** | AI rack **interconnect** (SerDes/AEC) | **$0.25 → $1.16** | Photonics-shaped electrical bottleneck |
| **6** | **POWL** | **Switchgear / e-houses** for DC power | $0.95 → $1.25; est $1.47 / $1.60 | Smaller (~$9B); electrical scarcity |
| **7** | **PWR** | **Grid construction** labor | Est $3.25 / $4.16 | Connects campuses to the grid |
| **8** | **NVT** | Electrical protection + **cooling** components | $0.59 → $1.09 | Vertiv-adjacent, smaller |
| **9** | **MOD** | **Liquid cooling** hardware | $0.92 → $1.71 | Thermal pure-play, higher beta |
| **10** | **DELL** | AI **servers** | Peak Q $4.86 | Volume enabler; less scarce than power |

### Priority order when rotating green cash

```
1. GEV  — primary (sold-out power through 2028)
2. STRL — highest EPS torque among smaller names
3. VRT or FIX — cooling / install (pick the dip)
4. CRDO / POWL — interconnect / switchgear satellites
```

---

## Thesis map (how these rhyme with MU / SNDK / NBIS)

```
Memory (owned): sold-out bits → ASP up → EPS explodes
     ↓ same shape, different scarce input
VRT / MOD / NVT: heat — liquid cooling mandatory at 100kW+ racks
FIX: install capacity — who can actually wire/cool the building
GEV / PWR: power — turbines + grid buildout years of backlog
CRDO: interconnect — SerDes/AEC bandwidth inside the rack
CLS / DELL: assembly — who ships AI servers at scale
AMD: compute — second source to NVDA (high PE, growth priced in)
```

**Why PE alone failed as a filter:** AMD at ~170× is exactly the “expensive but exploding” pattern you named. VRT at ~75× and CRDO at ~96× sit in that bucket — own them for the bottleneck, not the multiple.

---

## Skip / wait (not 5–15% core)

| Ticker | Why |
|--------|-----|
| CEG | Quality nukes, but **falling knife** (analyst cuts, PJM caps) — wait auction / ~$210–225 |
| BE | Power narrative, **unprofitable**, already ran hard from lows |
| RKLB, SYM, IONQ, OUST | Pre-profit / narrative — satellite only, not 5–15% |
| LITE, COHR, IREN, APLD | Either already sold for thesis reasons, or EPS/balance-sheet not holdable at size |
| SMCI | PE cheap but **EPS estimates declining** — growth broken |
| ETN, JCI | Real businesses, growth too steady for hypergrowth sleeve |

---

## Deployment (when cash available)

```
1. Hypergrowth sleeve (green rotation only — blocked at ~$475 BP):
     GEV first (sold-out power through 2028)
     STRL second (EPS torque, smaller cap)
     VRT / FIX on dips (cooling / install)
     CRDO / POWL as satellites
2. RAM → exit 100% when green (target 0%)
3. Do not buy CEG until Jul 14 auction or ~$210–225
4. Pharma: **CAPR only** (3-share AdCom lotto through Jul 29); see CAPR trade plan above
```

**Position sizing note:** Account is small (~$7k net / ~$15k gross) and levered. A “5–15%” sleeve means **of equity**, funded by green rotation — not new margin debt.

---

## Update log

| Date | Changes |
|------|---------|
| Jul 3, 2026 | Reset: cleared flawed sector “1-year no-brainer” research after CEG stress-test |
| Jul 3, 2026 | **Reframe:** PE is context, not veto. Already-ran is fine (SNDK 2025→2026 lesson) |
| Jul 3, 2026 | **Committed H2’26–’27 sleeve:** GEV #1, then STRL, VRT, FIX; CRDO/POWL/PWR/NVT/MOD/DELL |
| Jul 8, 2026 | VERA PDUFA approved Jul 7 — exit planned. **CAPR plan:** 3 shares, Jul 29 AdCom sell playbook; VERA→CAPR rotation Wed open |
| Jul 6, 2026 | Mon trades: DRAM $80C sold, 0.883 DRAM trim, 1 VERA bought; GEV/CRDO skipped (margin) |

---

## Next review triggers

- [x] **Tue Jul 7** — VERA PDUFA (approved); Samsung earnings; DRAM trades
- [ ] **Wed Jul 8** — Sell VERA; buy CAPR ×3 (limit $22–22.50)
- [ ] **Jul 10** — SK Hynix ADR earnings
- [ ] **Jul 11** — CORT PDUFA (pharma sector noise)
- [ ] **Jul 14** — PJM auction (CEG watch only)
- [ ] **Jul 22–23** — GEV / FIX earnings
- [ ] **Jul 27–31** — VRT, MOD, PWR, NVT earnings cluster; DRAM $80C expiry
- [ ] **Jul 29** — **CAPR FDA AdCom — execute sell playbook**
- [ ] **Aug 3** — STRL earnings (est $5.23)
- [ ] **Aug 22** — CAPR PDUFA (only if still holding shares)

*To update: refresh quotes/earnings via Robinhood MCP; kill on estimate cuts / backlog breaks only.*
