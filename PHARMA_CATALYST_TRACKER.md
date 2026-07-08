# Pharma / Biotech Catalyst Tracker

**Last updated:** Jul 8, 2026  
**Purpose:** Forward lotto / volatility research — dated catalysts + options signals. Not a cron alert system; refresh manually every 2–3 days or T−3 to any event.  
**Account context:** Satellite only — not core (DRAM / GEV sleeve). Tiny size if any.

> Not financial advice. PDUFA dates are FDA *targets* and can slip or decide early. Options flow is an attention filter, not a prediction.

---

## 3-tier framework (post Jul 7 revision)

Use this to rank **volatile movement** (up or down), not direction.

| Tier | Goal | Filters | Jul 7 examples |
|------|------|---------|----------------|
| **A — Lotto** | ±20%+ on catalyst day | Rel options vol **>8×** (ideally >15×) + mkt cap **<$500M** + dated catalyst **≤7 days** (data readout, AdCom, below-cash re-rate) | **TVRD** (+54%, 97× vol) — best miss |
| **B — Volatility watch** | ±10–25% | Catalyst ≤14 days + IV **>80%** OR rel vol **>4×**; cap $500M–$5B | **TTRX** (+26%, 9× vol, webcast known) |
| **C — Calendar binary** | ±5–15% | Known PDUFA on **>$3B** cap; IV elevated but move capped | **VERA** (+7% on approval) |

**Skip / deprioritize:**
- Surprise M&A (**CRNX** +99%) — not screenable
- Deal headlines with rel vol **<2×** (**SCLX**, **PYXS**) — need 8-K math, not options scan
- High IV with **no dated catalyst** (**NAUT**) — noise

### Detection stack (Robinhood + Alpaca)

Run manually — no automation required.

```
Score = (Catalyst dated ≤7d) × (Rel options vol) × (Small cap) × (Stock rel vol)
```

| Step | Tool | Action |
|------|------|--------|
| 1 | This doc + 8-K / IR | List names with catalyst ≤14 days |
| 2 | Robinhood `run_scan` | Rel options vol >2×, sort by IV; flag health-tech, cap <$500M, vol >8× |
| 3 | Alpaca `get_option_chain` | ATM straddle % = market’s expected ±move |
| 4 | Alpaca `get_news` | Confirm catalyst type (data vs PDUFA vs deal) |
| 5 | Kill rule | No date on calendar → Tier B at best; vol-only → skip |

### Options anomalies checklist

| Flag | Look for |
|------|----------|
| Front-month IV elevated | Event priced in |
| ATM straddle / stock | Market’s expected move (e.g. ±25%) |
| Vol / OI > 1–2× on a strike | Fresh positioning |
| OTM call OI wall | Prior bullish bets |
| Put skew (put IV > call IV) | Downside demand / hedges |
| Rel. options volume > 8× (RH) | **Tier A** attention |
| Rel. options volume > 4× (RH) | **Tier B** attention |

### Sizing rules (this account)

- Max **1–2% of equity** per binary name (stub only).
- Prefer **stock** over naked options when IV >100% (IV crush).
- Never size like DRAM / GEV core.
- Kill if thesis is only “options look busy” with no catalyst on calendar.

---

## Forward watchlist (ranked — Jul 8)

| Rank | Ticker | Tier | Next catalyst | Price | Cap | IV / vol signal | Expected move (options) |
|------|--------|------|---------------|-------|-----|-----------------|-------------------------|
| **1** | **CAPR** | **A** | **AdCom Jul 29**; PDUFA Aug 22 | $22.18 | ~$1.3B | **260–280%** Aug $22–25C; chain active | Straddle ~±15–20%; **two binaries** |
| 2 | CELC | B | PDUFA Jul 17 | $115.63 | ~$5.3B | 110–132% Jul $110C; +6.5% week | ~±10% |
| 3 | CORT | C | PDUFA Jul 11 | $94.01 | ~$9.7B | ~55% Jul $90C; whale alert Jun 29 | ~±5% |
| 4 | MRNA | C | PDUFA Aug 5 | ~$80 | ~$32B | Monitor from late Jul | Smaller % |
| — | NAUT | — | No dated catalyst | $1.68 | ~$218M | IV 298%, 2.5× rel vol | Skip until date confirmed |

**Jul 7 movers — done / skip:** TVRD, TTRX, CRNX, VERA, AKTX, VRXA, SCLX, PYXS.

---

## Upcoming (ordered by date — soonest first)

### 1. CORT — Corcept Therapeutics

| Field | Detail |
|-------|--------|
| **PDUFA** | **Jul 11, 2026** |
| Drug | Relacorilant (NDA) — platinum-resistant ovarian cancer |
| ~Price (Jul 7) | **$94.01** |
| Mkt cap | ~$9.7B |
| PE | ~258× (already re-rated) |
| Nearest options | Jul 17, Aug 21 |

**Options snapshot (Jul 7, Jul 17):**

| Signal | Detail |
|--------|--------|
| IV | ~55% on Jul $90–92.5C |
| Priced-in move | ~$4–5 straddle ≈ **±5%** |
| RH screen | ~2.6× rel vol; whale alert Jun 29 |
| Tier | **C** — calendar binary, not lotto |

**Status:** WATCH — nearest PDUFA after VERA  
**Outcome:** _pending_  
**Notes:** Large cap, priced for success. Volatility trade possible; not TVRD-style. CRL still painful; approval may be muted (+5–10%).

---

### 2. CELC — Celcuity

| Field | Detail |
|-------|--------|
| **PDUFA** | **Jul 17, 2026** |
| Drug | Gedatolisib (NDA) — HR+/HER2− / PIK3CA WT advanced breast cancer |
| Review | Priority / Breakthrough / Fast Track |
| ~Price (Jul 7) | **$115.63** (+6.5% vs Jul 6) |
| Mkt cap | ~$5.3B |
| 52w range | ~$13 → ~$151 — massive prior run |

**Options snapshot (Jul 7, Jul 17):**

| Signal | Detail |
|--------|--------|
| IV | **110–132%** on Jul $100–110C |
| Priced-in move | ~$12 straddle width ≈ **±10%** |
| RH screen | ~2.4× rel vol |
| Tier | **B** — real binary, sell-the-news risk after multi-bagger run |

**Status:** WATCH  
**Outcome:** _pending_  
**Notes:** IV building into PDUFA. Better vol than CORT; worse than CAPR. Refresh chain week of Jul 14.

---

### 3. CAPR — Capricor Therapeutics ⭐ Tier A lead

| Field | Detail |
|-------|--------|
| **AdCom** | **Jul 29, 2026** (CTGTAC — live stream) |
| **PDUFA** | **Aug 22, 2026** |
| Drug | Deramiocel (CAP-1002) — DMD cardiomyopathy (BLA) |
| ~Price (Jul 7) | **$22.18** |
| Mkt cap | ~$1.3B |
| 52w range | ~$4.30 → ~$40 |
| Analyst ref | HC Wainwright Buy, **$60 PT** (May 2026) |

**Regulatory context:**
- FDA **resumed BLA review** Mar 2026 after prior CRL; PDUFA on track Aug 22.
- AdCom called Jun 26 → stock **−11%** (market reads panel as risk, not rubber-stamp).
- HOPE-3 Phase 3 hit primary (PUL v2.0) + cardiac (LVEF); HOPE-2-OLE 5-year data positive.
- Prior CRL + panel = **higher binary width** than clean PDUFA.

**Options snapshot (Jul 7, Aug 21 expiry):**

| Signal | Detail |
|--------|--------|
| IV | **260–280%** on $22–25 calls |
| Priced-in move | ATM straddle ~$3–4 on $22 ≈ **±15–20%** per event |
| Chain activity | Jul 7: 491 vol on $25C; greeks live on $22–29 strikes |
| RH screen | Not top rel-vol Jul 8 (build into T−7) |
| Tier | **A** — best forward lotto on calendar |

**Would CAPR do a TVRD-style massive move?**

| Factor | TVRD Jul 7 | CAPR forward |
|--------|------------|--------------|
| Cap | **$19M** microcap | **$1.3B** mid — harder to +50% in one session |
| Rel vol pre-move | **97×** | Not yet elevated — watch T−3 to Jul 29 |
| Catalyst | Surprise Phase 1 pop | **Known** AdCom + PDUFA — screenable |
| IV | ~1500% post-move | **260%** pre-event — market already prices big move |
| Direction skew | Upside rip | **Two-way** — AdCom fear (−11% on announce); prior CRL |
| Historical comp | — | Gene therapy AdComs often **±30–50%**; PDUFA Aug 22 = second shot |

**Verdict:** CAPR is the **best forward volatility setup** on our book — more like **TTRX (+26%)** or a sharp AdCom day than **TVRD (+54%)** or **CRNX (M&A)**. Realistic single-day scenarios:
- **Positive AdCom vote (Jul 29):** +25–40% toward $28–31 (sell-the-news risk into Aug PDUFA)
- **Negative / harsh panel:** −30–50% toward $11–15 (CRL echo)
- **Aug 22 PDUFA:** second ±20–40% leg if still holding binary

Not a guaranteed +50% microcap rip — but **higher ±% potential than CORT/VERA** and **catchable in advance** (date known since Jun 26 8-K).

**Status:** **ACTIVE WATCH** — refresh RH rel vol + Alpaca chain from **Jul 22** (T−7)  
**Outcome:** _pending_

---

### 4. MRNA — Moderna

| Field | Detail |
|-------|--------|
| **PDUFA** | **Aug 5, 2026** (target; confirm) |
| Drug | mRNA-1010 — seasonal influenza (adults 50+) |
| ~Price (Jul 7) | ~$80 |
| Mkt cap | ~$32B |

**Tier:** C — large cap, smaller binary %. Monitor from late Jul.  
**Status:** WATCH  
**Outcome:** _pending_

---

### 5. GILD — Gilead Sciences

| PDUFA ~Aug 27, 2026 — HIV combo. **Tier C / BACKGROUND.**  
**Outcome:** _pending_

---

### 6. BIIB — Biogen (w/ Eisai)

| PDUFA ~Aug 24, 2026 — Leqembi SC. **Tier C / BACKGROUND.**  
**Outcome:** _pending_

---

## Jul 7, 2026 — case study log

What the framework would have flagged **before** the move:

| Ticker | Move | Tier | Catchable? | Pre-move signals | Miss reason |
|--------|------|------|------------|------------------|-------------|
| **TVRD** | +54% | A | **Yes** | 8-K Jul 7 AM; webcast 8:30 ET; **97× rel vol**; $19M cap | PDUFA-first screen; ignored microcaps |
| **TTRX** | +26% | B | **Yes** | Jul 6 PR; webcast Jul 7 4:30 PM; **9× rel vol** | Not on PDUFA calendar |
| **CRNX** | +99% | — | No | Vertex M&A Jul 6 PM | Unpredictable |
| **VRXA** | +38% | B? | Partial | Mover screen | Verify catalyst |
| **PYXS** | +25% | — | Barely | $50M PIPE close Jul 2 8-K | Rel vol 1.2× only |
| **SCLX** | +23% | — | Barely | $100M term sheet Jul 6 | Rel vol 1.5×; deal math |
| **VERA** | +7% | C | Yes (low) | PDUFA Jul 7; 4.5× vol; $3B cap | Expected approval; IV ±25% two-way |

---

## September 2026 cluster (monitor from August)

| Date | Ticker | Company | Drug / note |
|------|--------|---------|-------------|
| ~Sep 11 | **TLX** | Telix | TLX101-Px — glioma |
| ~Sep 18 | **NUVL** | Nuvalent | Zidesamtinib — ROS1 NSCLC |
| ~Sep 19 | **RARE** | Ultragenyx | UX111 — Sanfilippo type A |
| ~Sep 21 | **MRK** | Merck | WINREVAIR — PAH expansion |
| ~Sep 22 | **IONS** | Ionis | Zilganersen — Alexander disease |
| ~Sep 27 | **PRAX** | Praxis | Relutrigine — DEEs |
| ~Sep 30 | **PTGX** | Protagonist | Rusfertide — polycythemia vera |
| ~Sep 30 | **NVO** | Novo Nordisk | Mim8 — hemophilia A |
| ~Sep 30 | **AZN** | AstraZeneca | Enhertu — HER2+ early breast |

Large-caps (MRK, NVO, AZN, GILD) = Tier C. Mid/small = Tier A/B candidates when vol spikes T−7.

---

## Elevated options — no near catalyst (Jul 8 scan)

Verify news before acting. **No date → skip for lotto.**

| Ticker | IV (RH) | Rel. options vol | Note |
|--------|---------|------------------|------|
| TVRD | 1509% | 2.6× (post-move) | Done — archive |
| CTXR | 629% | 2.0× | $17M cap; illiquid |
| NAUT | 298% | 2.5× | Oversold; no dated readout |
| CMPX | 82% | 3.7× | Compass; verify catalyst |
| BEAM | ~92% | ~2.1× | Gene editing |
| ARCT | ~91% | ~3.2× | mRNA / rare disease |

---

## Playbook summary

```
Done:        VERA (Jul 7 approved) — exit lotto
Soonest:     CORT (Jul 11) → CELC (Jul 17) → CAPR AdCom (Jul 29) → CAPR PDUFA (Aug 22)
Next:        MRNA (Aug 5) → Sep cluster
```

| Phase | Action |
|-------|--------|
| T−60 to T−30 | Note IV baseline; calendar in this doc |
| T−14 to T−7 | RH scan for rel vol >8× on watchlist names |
| T−7 to T−1 | IV peak; Alpaca straddle = expected move; size decision |
| T+0 | Binary — sell into pop if lotto thesis done |
| T+1 | Log outcome below |

---

## Outcome log

| Date | Ticker | Result | Stock move | Tier | Notes |
|------|--------|--------|------------|------|-------|
| Jul 7, 2026 | **VERA** | **FDA approved** TRUTAKNA (atacicept) IgAN | +7% ($40.06 → $42.98); peak ~$44.60 (+11%) | C | Sold pre-PR ~10:33 AM. ±25% IV was two-way width. **Exit — lotto done.** |
| Jul 7, 2026 | TVRD | Phase 1 TTI-109 data | +54% | A | 97× rel vol — should have been Tier A flag |
| Jul 7, 2026 | TTRX | Phase 2 interim GX-03 | +26% | B | Webcast pre-announced Jul 6 |
| Jul 7, 2026 | CRNX | Vertex M&A $85/sh | +99% | — | Not screenable |
| Jul 7, 2026 | PYXS | PIPE close | +25% | — | Low vol; deal headline |
| Jul 7, 2026 | SCLX | $100M term sheet | +23% | — | Low vol; deal terms |

---

## Update log

| Date | Changes |
|------|---------|
| Jul 4, 2026 | Created. PDUFA calendar + VERA options snapshot. |
| Jul 6, 2026 | Bought 1 VERA @ $40.99. Jul 7 PDUFA watch. |
| Jul 8, 2026 | **Major revision:** 3-tier framework (A/B/C), detection stack, Jul 7 case studies + outcome log. VERA approved — exit. Forward rank: CAPR #1, CELC, CORT. CAPR AdCom Jul 29 confirmed; options IV 260%+. CORT/CELC Jul 7 snapshots. |

*Refresh: Robinhood `run_scan` + Alpaca `get_option_chain` / `get_news`. Confirm dates on IR / FDA.*
