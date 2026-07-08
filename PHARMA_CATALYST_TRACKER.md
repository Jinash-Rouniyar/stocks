# Pharma / Biotech Catalyst Tracker

**Last updated:** Jul 6, 2026 (EOD)  
**Purpose:** PDUFA / FDA binary events ordered by date, plus options-chain flags.  
**Account context:** Satellite only — not core (DRAM / GEV sleeve). Tiny size if any.

> Not financial advice. PDUFA dates are FDA *targets* and can slip or decide early. Options flow is an attention filter, not a prediction.

---

## How to use this doc

1. Scan **nearest dates first** (top of list).
2. **4–8 weeks out:** watch stock run-up + IV rising + OTM call OI build.
3. **1–2 weeks out:** IV usually peaks — buying naked options is expensive (IV crush risk).
4. **Decision day:** binary — approval often +big, CRL often −40–80% on small/mid biotech.
5. After each event: mark **Outcome**, note move, archive to bottom.

### Options anomalies checklist (per name)

| Flag | Look for |
|------|----------|
| Front-month IV elevated | Event priced in |
| ATM straddle / stock | Market’s expected move (e.g. ±25%) |
| Vol / OI > 1–2× on a strike | Fresh positioning |
| OTM call OI wall | Prior bullish bets |
| Put skew (put IV > call IV) | Downside demand / hedges |
| Rel. options volume > 2× (RH screen) | Unusual activity vs history |

### Sizing rules (this account)

- Max **1–2% of equity** per binary name (stub only).
- Prefer **stock run-up** over long options into peak IV.
- Never size like DRAM / GEV core.
- Kill if thesis is only “options look busy” with no catalyst on calendar.

---

## Upcoming (ordered by date — soonest first)

### 1. VERA — Vera Therapeutics

| Field | Detail |
|-------|--------|
| **PDUFA** | **Jul 7, 2026** |
| Drug | Atacicept (BLA) — IgA nephropathy (IgAN) |
| Review | Priority Review; Breakthrough Therapy Designation |
| ~Price (Jul 6) | ~$40.13 close / ~$41.50 AH |
| Mkt cap | ~$3.0B |
| PE | N/A (clinical-stage, unprofitable) |
| Nearest options | Jul 17 (spans PDUFA) |
| **Position** | **1 share @ $40.99** (Jul 6 close) — ~0.3% of equity |

**Options snapshot (Jul 2, Jul 17):**

| Signal | Detail |
|--------|--------|
| IV | ~150–190% on active strikes |
| Priced-in move | ~$40 straddle ≈ **±25%** |
| Unusual | **$35 put** vol 1,025 / OI 592 (vol > OI) |
| Call wall | **$50 call** OI **1,229** (prior upside bets) |
| Fresh lottery | **$60 call** vol 159, OI 0 |
| Skew | Put IV > call IV at $35 (downside demand) |
| RH screen | High IV + rel. options vol ~2.9× |

**Status:** ACTIVE — PDUFA **Tue Jul 7**. Decision window open.  
**Outcome:** _pending_  
**Notes:** Cleanest live example of binary options pricing. Mixed call OI + fresh puts = both sides positioned. ±25% is options-implied move **on the FDA decision**, not pre-event daily drift.

**Decision-day watch (Jul 7):**

| Window | ET | What to expect |
|--------|-----|----------------|
| Pre-market | 4:00–9:30 AM | Possible gap if company PR drops overnight |
| Morning | ~8:00–11:00 AM | Common same-day announcement window |
| After close | 4:00–8:00 PM | Very common — pop in AH or gap Wed AM |

Watch: [ir.veratx.com](https://ir.veratx.com/news-releases) → SEC 8-K. **Post-approval:** sell into pop (lottery done). **CRL:** accept tiny loss. Do not add CORT (Jul 11) same week.

---

### 2. CORT — Corcept Therapeutics

| Field | Detail |
|-------|--------|
| **PDUFA** | **Jul 11, 2026** |
| Drug | Relacorilant (NDA) — platinum-resistant ovarian cancer |
| ~Price (Jul 2) | ~$90 |
| Mkt cap | ~$9.7B |
| PE | ~258× (already re-rated) |
| Nearest options | Jul 17, Aug 21 |

**Options / setup notes:**

- Already ran hard from 52w low (~$29). Run-up phase may be largely done.
- High PE → less “left for dead,” more “priced for success.”
- Watch Jul 17 chain for IV vs VERA-style extremes; refresh quotes week of Jul 7–11.

**Status:** WATCH  
**Outcome:** _pending_

---

### 3. CELC — Celcuity

| Field | Detail |
|-------|--------|
| **PDUFA** | **Jul 17, 2026** |
| Drug | Gedatolisib (NDA) — HR+/HER2− / PIK3CA WT advanced breast cancer (post CDK4/6) |
| Review | Priority / Breakthrough / Fast Track (per calendar sources) |
| ~Price (Jul 2) | ~$105 |
| Mkt cap | ~$5.3B |
| PE | N/A (unprofitable) |
| 52w range | ~$13 → ~$151 — **massive prior run** |

**Options / setup notes:**

- Stock already did the “missed opportunity” move for many. Binary still real on decision day.
- Liquid chain through Jul 17 / Aug 21 — check vol/OI and straddle % into the week of Jul 14.
- Higher risk of “sell the news” even on approval after a multi-bagger run-up.

**Status:** WATCH  
**Outcome:** _pending_

---

### 4. MRNA — Moderna

| Field | Detail |
|-------|--------|
| **PDUFA** | **Aug 5, 2026** (target; confirm) |
| Drug | mRNA-1010 — seasonal influenza (adults 50+) |
| ~Price (Jul 2) | ~$80 (near 52w high) |
| Mkt cap | ~$32B |
| PE | N/A (negative) |

**Options / setup notes:**

- Larger, more liquid than pure clinical biotechs — moves often smaller % than VERA/CELC on binary.
- Still watch front-month IV and OTM call/put flow into late July.
- Not a “tiny biotech lottery”; more franchise + pipeline narrative.

**Status:** WATCH — earlier in window (good for run-up monitoring)  
**Outcome:** _pending_

---

### 5. CAPR — Capricor Therapeutics

| Field | Detail |
|-------|--------|
| **PDUFA** | **Aug 22, 2026** |
| Drug | Deramiocel (CAP-1002) — DMD cardiomyopathy |
| AdCom | Calendar sources note advisory committee ~**Jul 29, 2026** (verify) |
| ~Price (Jul 2) | ~$23 |
| Mkt cap | ~$1.3B |
| PE | N/A |
| 52w range | ~$4.30 → ~$40 |

**Options / setup notes:**

- More time than VERA/CORT/CELC — classic **4–8 week** watch for IV + call OI build.
- AdCom (if confirmed) is a **second binary** before PDUFA — often moves stock hard.
- Smaller cap → larger % swings; size accordingly.

**Status:** WATCH — build options checklist from mid-July  
**Outcome:** _pending_

---

### 6. GILD — Gilead Sciences

| Field | Detail |
|-------|--------|
| **PDUFA** | **Aug 27, 2026** (target; confirm) |
| Drug | Bictegravir / lenacapavir — HIV |
| Profile | Large-cap, profitable franchise |

**Options / setup notes:**

- Lower binary blow-up risk than micro/mid biotech; options less “lottery.”
- Useful as liquid pharma flow reference, not a VERA-style stub.

**Status:** BACKGROUND  
**Outcome:** _pending_

---

### 7. BIIB — Biogen (w/ Eisai)

| Field | Detail |
|-------|--------|
| **PDUFA / action** | **Aug 24, 2026** (Leqembi IQLIK / SC formulation — confirm) |
| Drug | Lecanemab — early Alzheimer’s (at-home / SC related filing) |
| Profile | Large-cap; Alzheimer’s franchise sensitivity |

**Status:** BACKGROUND  
**Outcome:** _pending_

---

## September 2026 cluster (monitor from August)

| Date | Ticker | Company | Drug / note |
|------|--------|---------|-------------|
| ~Sep 11 | **TLX** | Telix | TLX101-Px — glioma (confirm listing/liquidity) |
| ~Sep 18 | **NUVL** | Nuvalent | Zidesamtinib — ROS1 NSCLC |
| ~Sep 19 | **RARE** | Ultragenyx | UX111 — Sanfilippo type A |
| ~Sep 21 | **MRK** | Merck | WINREVAIR (sotatercept) — PAH expansion |
| ~Sep 22 | **IONS** | Ionis | Zilganersen — Alexander disease |
| ~Sep 27 | **PRAX** | Praxis | Relutrigine — DEEs |
| ~Sep 30 | **PTGX** | Protagonist | Rusfertide — polycythemia vera |
| ~Sep 30 | **NVO** | Novo Nordisk | Mim8 — hemophilia A (also cited Jul 29 in some calendars — **verify**) |
| ~Sep 30 | **AZN** | AstraZeneca | Enhertu — HER2+ early breast (also Jul 7 cited in some calendars — **verify**) |

Large-caps (MRK, NVO, AZN, GILD) = smaller % binary, better liquidity.  
Mid/small (NUVL, RARE, IONS, PRAX, PTGX, CAPR, VERA, CELC) = larger % moves, higher wipeout risk.

---

## Elevated options activity — no near PDUFA on our list

From RH **high options vol / IV** screen (Jul 2). Catalyst may be trial data, M&A rumor, or noise — **verify news before acting**.

| Ticker | IV (screen) | Rel. options vol | Note |
|--------|-------------|------------------|------|
| **BEAM** | ~92% | ~2.1× | Gene editing; watch for data dates |
| **ARCT** | ~91% | ~3.2× | mRNA / rare disease |
| **INCY** | ~37% | ~3.3× | Profitable; flow ≠ binary lottery |
| **VCEL** | ~65% | ~2.3× | Smaller biotech |
| **IMTX** | ~60% | ~2.4× | Immatics |
| MENS / TLSA | extreme | elevated | Microcap noise — skip |

---

## Playbook summary

```
Soonest risk:     VERA (Jul 7) → CORT (Jul 11) → CELC (Jul 17)
Next window:      MRNA (Aug 5) → CAPR AdCom? (Jul 29) → CAPR PDUFA (Aug 22)
Build watch from: mid-Aug for September cluster
```

| Phase | Action |
|-------|--------|
| T−60 to T−30 | Note IV baseline; start watching call OI |
| T−30 to T−14 | Run-up often strongest; options still “cheaper” than T−3 |
| T−14 to T−1 | IV peak; long options = IV crush risk |
| T+0 | Decision; size already decided or flat |
| T+1 | Log outcome; update this doc |

---

## Outcome log

| Date | Ticker | Result | Stock move | Notes |
|------|--------|--------|------------|-------|
| | | | | |

---

## Update log

| Date | Changes |
|------|---------|
| Jul 4, 2026 | Created. Ordered by PDUFA: VERA → CORT → CELC → MRNA → CAPR → GILD/BIIB → Sep cluster. VERA options snapshot from Jul 2. |
| Jul 6, 2026 | Bought 1 VERA @ $40.99. Added decision-day watch for Jul 7 PDUFA. |

*Refresh: RH options quotes + PDUFA calendars (RTTNews, company 8-Ks). Dates slip — always confirm on IR / FDA.*
