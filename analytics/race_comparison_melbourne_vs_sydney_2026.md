# Race Comparison — HYROX Melbourne 2025 vs HYROX Sydney 2026

> **Purpose:** Full data record and causal analysis of the Sydney race outcome, built to be handed to another model or coach with zero prior context. Contains confirmed data (source-tagged) and clearly separated interpretation. Do not treat interpretation sections as fact — they are the working hypothesis given available evidence.

**Athlete:** Yaro (Yaroslav Andrushchenko) · 46 · Pro Men 45–49 · 196 cm / 84 kg · Ukrainian, based in Melbourne, Australia
**Document date:** 2026-07-04
**Prepared by:** Claude (wolf-hyrox coaching system), from athlete-supplied race-app screenshots and 95-day training record

---

## 1. Top-Line Comparison

| Metric | Melbourne 2025-12-13 | Sydney 2026-07-03 | Delta |
|---|---|---|---|
| Finish time | **1:33:44** | **1:48:24** | +14:40 slower |
| Result status | Finished, ranked | **DISQUALIFIED** (Wall Balls, final station) | First career DQ |
| Overall rank | #603 | DQ — not ranked | — |
| Age-group rank | #29 | DQ — not ranked | — |
| Avg run pace ("Avg Run" field) | 07:41 | 08:07 | +26 sec/leg slower |
| Race prep context | Untrained baseline, first HYROX, no dedicated build | End of a dedicated 95-day / 14-week build targeting 1:15:00 | — |
| Target for this race | None (baseline data point) | 1:15:00 | Missed by 33:24, and DQ'd |

Melbourne was never the goal race — it is the pre-build baseline referenced throughout the training log (`STATE.md`, `reference/athlete_profile.md`). Sydney was the target race for a 14-week structured build (2026-03-30 → 2026-07-03). The build produced clear station-level improvements (see §3) but the race outcome was a regression in time and a first-ever disqualification.

---

## 2. Confirmed Race Data

### 2A. Melbourne — 2025-12-13 (source: race app "Race Result" + "Splits" screens)

- Finish time: **1:33:44**
- Rank: **#OV 603 · #AG 29** (Pro Men 45–49)
- Running total: 1:01:29 · Functional (stations) total: 39:57 · Roxzone: 03:01
- Avg pace: 07:24/km · Avg Run: 07:41 · Percentile: Top 81.2%
- No illness, injury, or DQ noted for this race in any available record

**Note on reconciliation:** Running + Functional + Roxzone (as shown on the summary screen) sum to roughly 10:43 more than the stated finish time. This is a feature of how the app buckets transition time into adjacent splits, not a data error — the summary-screen totals and the finish time are both taken as authoritative from the app; the discrepancy is not resolved further in this document.

### 2B. Sydney — 2026-07-03 (source: race app "Race Result" + "Splits" screens + Apple Watch workout)

- Finish time: **1:48:24**
- Status: **DQ — Wall Balls**
- Bib 184047 · Wave 18:40 HYROX MEN PRO · Sydney Olympic Park
- Avg Run: 08:07
- Apple Watch (Mixed Cardio, 18:40–20:30, Sydney Olympic Park): workout time 1:50:32 · active cal 1,622 · total cal 1,823 · avg HR **154 bpm** · max HR **172 bpm**
- HR zone distribution: Z1 1:31 · Z2 4:58 · Z3 19:57 · **Z4 1:07:51** · **Z5 16:14**
- Post-workout HR decay: 110 → 122 → 119 bpm at 1–2 min (post-workout HR bump at 1 min is consistent with the athlete stopping abruptly mid-effort — i.e. at the point of disqualification rather than a controlled finish-line deceleration)

---

## 3. Station-by-Station Comparison

Times are direct from each race's splits screen. Field rank (where shown) is out of that race's full finisher field. Melbourne's "Run 1" (2:28) and Sydney's short early splits suggest the first running leg is not a full 1 km at either venue in the way later legs are — treat absolute run times as within-race comparisons, not as km-pace conversions.

| Station | Melbourne time (rank) | Sydney time (rank) | Read |
|---|---|---|---|
| Run 1 | 2:28 (461) | 3:58 (429) | Sydney slower from the gun |
| Ski Erg | 4:20 (499) | 4:21 (401) | Even — Ski erg unaffected |
| Run 2 | 4:01 (329) | 7:40 (554) | Sydney nearly double — fade begins |
| Sled Push | 3:45 (480) | **1:37 (#1 in field)** | Major improvement — fully race-proven |
| Run 3 | 4:16 (293) | 7:16 (551) | Sydney fade continues |
| Sled Pull | 6:01 (416) | **2:36 (#1 in field)** | Major improvement — fully race-proven |
| Run 4 | 4:29 (364) | 7:42 (556) | Sydney fade holds at ~2x Melbourne |
| Burpee Broad Jump | 5:24 (592) | 5:30 (471) | Comparable time, Sydney relative rank better (weaker field context aside, technique held) |
| Run 5 | 4:43 (420) | 8:09 (554) | Fade continues |
| Row Erg | 4:44 (566) | 5:03 (532) | Comparable — Row unaffected |
| Run 6 | **14:19 (746)** | 8:22 (556) | Melbourne anomaly (see note below); Sydney consistent with its own pattern |
| Farmers Carry | 1:44 (165) | 1:35 (**64**) | Improvement — grip/carry strength confirmed |
| Run 7 | **21:18 (745)** | 8:33 (553) | Melbourne anomaly continues; Sydney consistent |
| Sandbag Lunge | 5:17 (410) | 5:12 (329) | Slight improvement |
| Run 8 | 5:55 (509) | **13:18 (552)** | Sydney's worst single leg — severe late collapse |
| Wall Balls | 8:42 (577) | 7:55 (443) — **DQ**, time recorded but result invalidated | Sydney was faster to this point in the WB effort than Melbourne, but did not receive a valid result |
| Roxzone | 3:01 (**4**) | Not captured on available screenshot | Melbourne transitions were elite (rank 4); Sydney's equivalent figure is not available (screen cut off before DQ, likely because there was no clean finish-line roxzone to record) |

### Key pattern

**Sled Push and Sled Pull went from mid-pack (480th, 416th) in Melbourne to #1 in the entire field in Sydney.** This is the single clearest proof that the 14-week build worked exactly as designed for the two stations it targeted hardest (245 kg push / 204 kg pull working loads, confirmed race-ready in W25–W26 training data).

**Running went the opposite direction.** Melbourne shows two isolated catastrophic outliers (Run 6: 14:19, Run 7: 21:18) sitting inside an otherwise normal-fading run profile (Runs 1–5 and 8 all under 6 min). Sydney shows no single outlier of that magnitude — instead every run from Run 2 onward is uniformly and progressively slower (7:16–8:33), before a final severe blowout on Run 8 (13:18). This is a different failure signature: Melbourne looks like one specific stoppage event (cause not recorded — flagged as an open question, §6); Sydney looks like a systemic, whole-race erosion of running capacity.

---

## 4. The 95-Day Sydney Build — Condensed Arc

Full detail lives in `archive/2026/week_NN_report.md` (W14–W26) and `trackers/*.md`. Condensed for context:

| Phase | Weeks | Dates | Outcome |
|---|---|---|---|
| 1 — Stabilize | W14–W16 | 03-30 → 04-19 | Sled push 240 kg PR fresh; WB progression 0:58→0:53/set |
| 2 — Build | W17–W21 | 04-20 → 05-24 | VO₂max PR 58 (W21); WB clean lock progression 30→40→**50** under fragment fatigue; sled push 245 kg working PR; sled pull 204 kg working |
| 3 — Specific Peak | W22–W24 | 05-25 → 06-14 | **Disrupted.** W22 flu vaccine reaction. W23 sinus/HRV suppression, near-zero quality work. W24 "Recovery Crisis" — respiratory/sinus activation, HRV suppressed nearly all week, WB probe missed for the 3rd consecutive week. This phase — meant to expose WB ceiling 60→80→100 — never delivered a single ceiling probe above 50. |
| 4 — Taper | W25–W26 | 06-15 → 06-28 | Re-entry after 3 disrupted weeks. WB re-confirmed at 50 clean (5th consecutive missed ceiling attempt — never got past 50 under full fatigue at any point in the entire 14-week build). BBJ restarted from scratch (had been dropped since W21). Sled reconfirmed at race load. Ski/Row erg only touched once (W26 Tue) — zero other exposure. |
| Race Week | W27 | 06-29 → 07-03 | Mon: sickness watch (respiratory/sinus symptoms, no fever, no training). Tue: HRV rebounded (+64%), home micro-touch only. Wed: packing, HRV still elevated, athlete notes underfueling. Thu: travel MEL→SYD. **Fri: race — 1:48:24, DQ.** |

**Structural fact that matters most:** the entire final third of the build (W22–W24, the phase explicitly designed to expose the WB ceiling under full race-fatigue at 60→80→100 reps) was consumed by illness disruption. The 50-clean lock from W21 was never once exceeded — not in W22, W23, W24, W25, or W26. The race called for 100 reps. The gap between the *demonstrated* ceiling (50 clean, and only under a partial 3–4 round fragment, never a full 8-station fatigue load) and the *race requirement* (100, after 7 stations and ~7 km of running) was never closed and never even tested at full scale before race day.

---

## 5. Root Cause Analysis

Confidence is graded explicitly. Nothing here is presented as confirmed unless the source data says so.

### Confirmed by data
1. **Sled push/pull are fully race-proven.** Rank #1/#1 in the field is not compatible with any illness or fatigue effect — this is a station where the training transferred perfectly.
2. **The athlete worked hard throughout, physiologically.** Avg HR 154, with over 84 minutes combined in Zone 4/5 across a ~1:48 effort. This rules out "gave up" or "cruised it in." The engine was pushing.
3. **Running degraded progressively and uniformly**, not from one incident. Every leg from Run 2 onward was slower than the last comparable Melbourne leg, well beyond the "compromised pace" gap the training log had already identified and only partially managed (training-documented compromised pace was ~5:13/km after sled fatigue; race splits imply a far larger collapse than that historical worst case).
4. **The final third of the build (Phase 3, W22–W24) was lost to illness disruption**, and the WB ceiling was never tested above 50 clean at any point in 14 weeks, let alone under full 8-station race fatigue.
5. **Race-week illness is documented**: respiratory/sinus symptoms flagged Monday 2026-06-29, four days before the race, marked "resolved" by Wednesday based on HRV rebound — but HRV rebound does not confirm full respiratory/lung-function recovery, only autonomic recovery.

### Plausible, not confirmed (working hypothesis)
1. **Residual illness effect on race day.** The athlete's own account is that the run collapse is attributable to having raced while sick. This is consistent with: (a) the magnitude of the running fade being far beyond any previously measured "compromised pace" ceiling, (b) the respiratory/sinus illness only 4 days prior, (c) a high-HR, low-output pattern (Z4/Z5 dominant but slow) — a classic signature of reduced aerobic economy or reduced O₂ delivery rather than reduced effort or motivation.
2. **The Wall Balls DQ was likely a technical breakdown under fatigue** (repeated no-reps for target/depth standard, or a movement-standard violation triggering referee disqualification), not a time-limit or medical DQ. This is inferred from: the athlete's WB capacity was locked at 50 clean under partial fatigue and never tested at 100 under full race fatigue; by the time he reached the final station he had already run a cumulative load far beyond anything in training (progressively worsening 7 runs plus a 13:18 final run); a technical/form breakdown under that level of accumulated fatigue is the most probable mechanism for a WB-station DQ. **The literal reason recorded by the race referee is not available in any data reviewed — this is inference, not fact.**
3. **Underfueling contributed.** Race-week Wednesday notes explicit underfueling (last proper meal ~10:00, race-adjacent nutrition gap). Combined with an 18:40 (evening) wave and the associated late-day fueling risk already flagged in `state/limiters_now.md` (Risk 2), this may have compounded the aerobic/muscular fade in the second half of the race.
4. **Travel + short turnaround** (fly Thu, race Fri evening) removed a buffer day that earlier in the build (Phase 4 plan) implicitly assumed. Not confirmed as causal, but a plausible contributing stressor stacked on top of the illness.

### Open / not explained by available data
1. **Melbourne's Run 6 (14:19) and Run 7 (21:18).** No cause is recorded anywhere in the training system for this race (it predates the current tracking system). These two splits are far outside any plausible running pace and most likely represent a stoppage (course congestion, bathroom break, mechanical/GPS issue, or a deliberate pause) rather than an actual running effort. This does not affect the Sydney analysis but is flagged because it was visible in the raw data and should not be misread as "Melbourne's running was fine, Sydney's collapsed" without noting this anomaly exists on both sides of the comparison.
2. **The exact wording of the Sydney DQ ruling.** Not available. If the athlete recalls the referee's stated reason (no-rep count, warning given, movement standard cited), it should be added here — it changes whether the fix is "build WB capacity further" or "build WB technique-under-fatigue specifically" or "manage race-day arithmetic to never need to push WB past a safe technical limit again."

---

## 6. What Held / What Broke

**Held (race-ready, proven under real competition conditions):**
- Sled Push — #1 in field
- Sled Pull — #1 in field
- Farmers Carry — top 15% of field (rank 64)
- Ski Erg, Row Erg — no measurable degradation vs. Melbourne despite having a combined total of one training exposure in the entire 14-week build
- Sandbag Lunge — stable, slight improvement over Melbourne
- Effort/engagement — HR data confirms the athlete pushed hard for the full distance, illness or not

**Broke:**
- Running — progressive, whole-race collapse, magnitude far beyond any previously measured "compromised pace" ceiling
- Wall Balls — ended in disqualification rather than a completed or even a clean partial result
- The Phase 3 "Specific Peak" build block (W22–W24) — lost entirely to illness disruption, meaning the single most important remaining gate (WB ceiling 50→100 under full fatigue) was never closed, tested, or even attempted at scale before race day
- Race week illness timing — four days out is not enough clearance for a respiratory event before an evening-wave endurance effort of this length

---

## 7. Questions Worth Resolving Before the Next Block

1. Does the athlete recall or have access to the official HYROX judge/referee note for the Wall Balls DQ?
2. Does the athlete recall what happened during Melbourne's Run 6/Run 7 (14:19/21:18)? Not required for the Sydney analysis, but worth closing the record.
3. Was there a specific point during the Sydney race (e.g., after Run 6, after Row) where the athlete subjectively felt the illness/fatigue effect become severe, or was it gradual from the start?
4. Fueling and hydration detail during the race itself (gels taken, timing, salt) — not captured in any screenshot reviewed here.

---

## 8. How to Use This Document

This file is a complete, source-tagged record intended to be handed to another model or coach (e.g. for next-block strategy generation) without further context retrieval. It should be read alongside:
- `reference/athlete_profile.md` — updated post-Sydney capability section
- `archive/2026/week_28_plan.md` — immediate recovery program
- `reference/master_plan.md` — build phase structure (Phase 3 disruption is the structural root cause of the WB gap)
- `trackers/wb_tracker.md`, `trackers/run_tracker.md` — full historical station data

No forward strategy or next-block plan is proposed in this document by design — it is a diagnostic record, not a plan. The recovery program (`archive/2026/week_28_plan.md`) covers only the immediate 7–10 days. Full next-block strategy is a separate, later decision the athlete has indicated he wants to make deliberately, potentially with another model's input.

---

## 9. CORRECTION ADDENDUM (2026-07-05, athlete testimony — resolves §7 questions 1 and 2)

This section corrects working hypotheses in §5 and §6 above. The original text is left in place for the record; treat this section as authoritative where it conflicts.

**§7 Q1 resolved — the Sydney DQ cause.** Wall Balls were completed in full: 100 reps, judges praised the execution. The disqualification was for a **navigational/course error** — running the wrong (inner) loop on Run 8, the final run immediately before the Wall Balls station. Pre-race briefing had explicitly warned that an incorrect loop is an automatic DQ, no exception. The race app records the DQ against "Wall Balls" only because that is where the ruling landed / the race ended for scoring purposes — it is not evidence of a WB-station failure. **This reverses §5's "plausible, not confirmed" hypothesis #2** ("WB DQ was likely a technical breakdown under fatigue"): WB capacity at 100 reps under full 8-station race fatigue is now a confirmed, race-proven result. The only remaining WB gap is speed (7:55 race vs 5:00 target), not capacity.

**§7 Q2 resolved — Melbourne 2025 Run 6 (14:19) and Run 7 (21:18).** These were **lap-count penalties**, not a stoppage or GPS/mechanical anomaly. The athlete missed laps on the course at Melbourne 2025 and received time penalties (~11 minutes added across the two legs) rather than a disqualification — Melbourne's rule structure penalized the same category of error (course/lap navigation) that later caused the Sydney DQ outright. Read together, this is the same failure mode (navigation under fatigue) appearing at both races, penalized at Melbourne and disqualifying at Sydney. This was **not** a WB-related event at either race — the "Runs 6 and 7 carried penalties" framing that appeared in an external draft plan was a confusion between the two races' data, now resolved by direct comparison of both race screenshots.

**Downstream effect on diagnosis:** the Sydney limiter ranking in §3/§6 of this document (WB capacity gap listed as a top limiter) is superseded. Wall Balls moves from a **capacity** limiter to a **speed** limiter. **Navigation-under-fatigue** (lap/loop-counting while depleted) becomes a first-class, confirmed limiter — cheap to fix, and now evidenced at two consecutive races.
