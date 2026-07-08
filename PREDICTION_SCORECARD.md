# Daily High-Mover Prediction Scorecard

**Started:** Jul 8, 2026
**Purpose:** Predict the biggest daily winners/losers (±10%+) *in advance*, across all sectors, then grade myself objectively to refine the research process over time.

> Not financial advice. This is a research calibration exercise — I am NOT trading these. The point is to measure whether disciplined, catalyst-driven research can predict outsized moves better than noise.

---

## Scoring rules

Grading uses **close-to-close %** (prior session close → prediction-day close) as the objective metric.

| Outcome | Points |
|---|---|
| Predicted WINNER moves **+10% or more** | **+2** |
| Predicted LOSER moves **−10% or more** | **+2** |
| Prediction wrong (direction wrong, OR move < 10% in predicted direction) | **−1** |
| Explicitly excluded a "trap" that would've been a wrong pick | (noted, no points — discipline log) |

- 3–5 winners and 3–5 losers per day.
- A pick that moves the right direction but only, say, +6% still scores **−1** (the bar is 10%, no partial credit). This is intentionally harsh to force real conviction.
- Monthly total + hit-rate tracked at the bottom.

---

## Research methodology / thesis

The core insight from the user's critique: **fading yesterday's top gainers is not prediction — it's regression to the mean dressed up as analysis, and it blows up on the exact names that matter most.** A real edge requires identifying *why* a stock will move tomorrow via a mechanism, not just "it was up a lot."

### The move must have a MECHANISM. I bucket every candidate into one of 5 archetypes:

**A. Dated binary catalyst (highest-quality signal).**
A scheduled, calendar-known event with a yes/no outcome and a short time horizon → near-guaranteed large move, direction uncertain but often lean-able.
- Examples: PDUFA decisions, AdCom votes, top-line data webcasts, Phase readouts on a fixed date.
- Edge: I know *it will move*; the skill is leaning the direction from setup (endpoint design, cash runway, prior data, analyst posture).

**B. Momentum continuation on a real-catalyst low-float runner.**
A microcap that moved on *genuine* news (real data, real deal) with a tiny float tends to continue Day 2 as retail/momentum piles in before exhausting Day 3.
- Requires: real catalyst (not a vague pump), low float, closed at/near highs, after-hours strength.
- Edge: crowd behavior + supply squeeze. Medium confidence, two-sided risk.

**C. Mechanical dilution / exhaustion fade.**
A parabolic microcap up on a **dilutive** event (reverse merger, ATM, S-1 financing, warrants near-the-money) where the float squeeze is exhausting. The *mechanism* (share issuance overhang) pulls it down — this is NOT a lazy "it went up so it'll fall."
- Requires: dilution overhang documented in filings + after-hours fade + extreme float turnover.

**D. Sector/factor beta unwind.**
A high-beta proxy (crypto-treasury names, leveraged single-stock themes) that overshot and will mean-revert with its underlying overnight.

**E. Earnings / guidance gap.**
A scheduled report (BMO or prior-day AMC) with a history of large post-print moves.

### The anti-pattern I explicitly avoid (discipline log)
- **CRNX (+98.7% Jul 7): DO NOT FADE.** This is a **Vertex all-cash buyout at $85/share** (closed $83.53). It is now a **merger-arb pin** — it will trade flat near $85 until the Q3 close, NOT revert. A naive "fade the biggest gainer" model shorts this and loses. Excluded from both buckets. *This is the single most important discipline point in the whole exercise.*
- Any move driven by a firm cash acquisition price = pinned, exclude.

---

## Predictions — for Jul 8, 2026 (Wednesday)

**Reference:** prior close = Jul 7, 2026. Scoring metric = Jul 7 close → Jul 8 close.

### WINNERS (predict +10%+)

| # | Ticker | Jul 7 close | Archetype | Mechanism / thesis | Confidence it moves ±10% | Confidence direction (up) | Invalidation |
|---|---|---|---|---|---|---|---|
| 1 | **MCRB** (Seres) | ~$8.00 | A — dated binary | **Jul 8, 8:30 AM ET webcast** = top-line data from 15-pt IST of SER-155 in checkpoint-inhibitor enterocolitis. Clean binary endpoint (Day-15 immunosuppressive-free response). BTD + Fast Track drug, cash into Q1'27 (low dilution pressure), HC Wainwright Buy PT $12 vs $8. Company scheduling a dedicated webcast = mild positive tell. | **~85%** | ~55% (lean up, but genuinely two-sided) | Vague/"mixed" data language, or a "we need funding" pivot on the call |
| 2 | **TVRD** (Tvardi) | $3.10 | B — momentum continuation | Day 1 was +54% on *real* Phase 1 STAT3-inhibitor (TTI-109) data, 97× rel vol, $29M cap, closed mid-range with AH tick to $3.23. Tiny float + real catalyst = classic Day-2 follow-through setup. | ~55% | ~45% | Gap-and-fade at open; no follow-through volume |
| 3 | **FHTX** (Foghorn) | $6.01 | B — momentum continuation | +18.8% Day 1, closed at session high ($6.24 range top), AH ask $7.20 (thin but bullish). Oncology, Strong Buy. Strength into the close + AH = momentum carry. | ~45% | ~45% | AH quote was thin; opens flat and stalls |

### LOSERS (predict −10%+)

| # | Ticker | Jul 7 close | Archetype | Mechanism / thesis | Confidence it moves ±10% | Confidence direction (down) | Invalidation |
|---|---|---|---|---|---|---|---|
| 1 | **CLRO** (ClearOne) | $13.66 | C — dilution/exhaustion fade | +97% on **reverse merger** with Cortigent/Vivani. Legacy holders end up ~13% owners; **12.5M shares to Vivani + $10–15M S-1 unit financing with $10 warrants** (near-the-money). Float turned over **48×** — a supply-starved squeeze, not fundamentals. AH already faded $16.29 → $13.27. Dilution overhang + exhaustion. | ~65% | ~55% | Low-float squeezes are violent both ways — a fresh momentum gap-up can extend before it breaks |
| 2 | **ABTC** (American Bitcoin) | $6.52 | D — factor beta unwind | Crypto-treasury proxy, already −23% Jul 7. Trades at premium to BTC NAV; BTC soft (~$62.6k). Premium compression + broken momentum. AH $6.52 vs intraday $8.33 high = rolling over. | ~55% | ~50% | BTC rips overnight; Trump-branded name gets a retail bid |
| 3 | **SECZ** (Securitize) | $8.09 | C/D — post-break continuation | −26% Jul 7, **AH bid ~$7.00** (another ~−13% indicated). No visible stabilizing catalyst; wide spread + heavy supply. AH quote suggests it opens lower. | ~50% | ~50% | Thin AH quote unreliable; a dip-buy bounce erases the gap |

### Watchlist (not scored — insufficient conviction/edge)
- **SKYQ** — oil/short-squeeze play on Strait of Hormuz shipping disruption; direction depends on unpredictable oil headlines.
- **PYXS** — +24.8% oncology Strong Buy, but weak rel vol (1.2×) → catalyst unclear, likely no follow-through.
- **AZZ** — earnings Jul 8 **after close**, so the move lands Jul 9, not scored here.

---

## Honest confidence statement

- The **only** genuinely high-probability "**it will move ±10%**" call is **MCRB** (dated binary). Everything else is 45–65% on magnitude and roughly coin-flip on direction.
- Realistic expectation for next-day *directional* ±10% prediction, even with disciplined research: **~40–55% hit rate.** Anyone claiming higher on single names a day out is guessing.
- The value of this exercise is **calibration over a month** — which archetypes actually pay, and whether my confidence numbers are honest (do my "55%" picks hit ~55%?).

---

## Grading — Jul 8, 2026 *(fill in after close)*

| Ticker | Bucket | Predicted | Jul 8 close | Actual % | Hit? | Points |
|---|---|---|---|---|---|---|
| MCRB | Winner | +10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| TVRD | Winner | +10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| FHTX | Winner | +10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| CLRO | Loser | −10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| ABTC | Loser | −10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| SECZ | Loser | −10%+ | _tbd_ | _tbd_ | _tbd_ | _tbd_ |
| **Day total** | | | | | | **_tbd_** |

**Discipline check:** Did CRNX stay pinned near $85 (correct exclusion)? _tbd_

---

## Monthly scorecard (July 2026)

| Date | Picks | Hits | Points | Notes / lessons |
|---|---|---|---|---|
| Jul 8 | 6 | _tbd_ | _tbd_ | First run. Thesis: dated binary (MCRB) is the anchor; testing momentum-continuation vs dilution-fade archetypes. |
| **MTD total** | | | **_tbd_** | |

### Process learnings (update after each grading)
- _tbd — e.g. "Momentum-continuation (archetype B) went 0/2, day-2 fades dominated → tighten to only names with AH strength >X%."_
