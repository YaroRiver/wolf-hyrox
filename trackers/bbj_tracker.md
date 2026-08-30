# Burpee Broad Jump (BBJ) Tracker

> **Append-only log.**

**Official current Men Pro race standard (corrected 2026-08-29, Master Plan v2.3): 80 m continuous, not "80 reps over ~30 m."** The line below is obsolete historical training-format language, kept for context on old rows only — do not use it as the current race standard.
**Working distances in training:** 20 m (race-fragment) and 30 m (compromised testing); new 2026-08-29 progression adds 40 m and 80 m continuous distances — see "Master Plan v2.3 exposure-ladder" below.

---

## BBJ Performance History

### Thursday HYROX Rhythm — 2-round fragments

| Date | Week | Distance | R1 | R2 | Fade | Notes |
|---|---|---|---|---|---|---|
| 2026-04-16 W16 THU | Sydney W3 Phase 1 | 30 m | ~2:00 | 2:27 | 27 sec | First BBJ data in current arc |
| 2026-04-23 W17 THU | Sydney W4 Phase 2 W1 | 30 m | 2:23 | 2:26 | 3 sec | Consistent, slow |
| 2026-04-30 W18 THU | Sydney W5 Phase 2 W2 | 30 m | 1:56 | 2:10 | 14 sec | R1 pace dropped, R2 fade emerged |
| 2026-05-07 W19 THU | Sydney W6 Phase 2 W3 | (calf-protected) | — | — | — | BBJ likely removed or reduced |
| 2026-05-14 W20 THU | Sydney W7 Phase 2 W4 | 30 m | **1:34** | **2:06** | **32 sec** | LIMITER CONFIRMED; R1 too fast → R2 collapse |
| 2026-05-21 W21 THU | Sydney W8 Phase 2 W5 | 30 m × 3 (90m total) | 2:23 | 2:10 | 2:01 | ~4.0 sec/m; improved each round under fatigue; 3-round format within [run+BBJ+WB] structure |
| 2026-05-23 W21 SAT | Sydney W8 Phase 2 W5 | 20 m × 4 (80m total) | 0:58 | 0:54 | 0:48 | 0:49 | ~4.0 sec/m; inside full round structure (run+lunge+BBJ+WB); no fade |

### Saturday race-fragment — 20 m (W18, W19, W20)

| Date | Week | Distance | Format | Notes |
|---|---|---|---|---|
| 2026-05-02 W18 SAT | Sydney W5 | 20 m | 4 rounds within fragment | Controlled, no fade noted |
| 2026-05-09 W19 SAT | Sydney W6 | 20 m | 4 rounds within fragment | Calf-controlled; clean |
| 2026-05-16 W20 SAT | Sydney W7 | 20 m | 4 rounds within fragment | **R4 1:27; mild calf awareness, athlete slowed correctly, NO cramp/pulling; NO R1→R2 fade pattern (race-distance format)** |
| 2026-08-15 W33 SAT | Melbourne Phase I W2 | 20 m | 4 rounds within [600m run + BBJ + 25 WB] hybrid block | **REINTRODUCTION after dormant since 2026-06-27 (W26): 0:56 / 0:54 / 0:59 / ~1:10 (corrected, ~15s watch glitch on R4).** Deliberately submaximal — used to regulate breathing between fast 600m runs, not a fatigue-curve test. Zero quad collapse, zero pre-cramp, zero lower-leg "string" across all 4 rounds. W33 headline objective achieved; not yet a valid race-specific fatigue result (see `state/current_week.md` W33 Sat entry for the planned follow-up sequence: sled push → run → sled pull → run → BBJ) |

---

## Limiter Analysis (Refined 2026-05-16 W20 SAT)

### Distance-Specific Pattern (NEW INSIGHT)

The R1→R2 fade is **distance-specific**, not general:

- **30 m (Thursday rhythm format):** R1 over-pace → R2 collapse persists across W17–W20
- **20 m (Saturday race-fragment format):** No fade observed; controlled rhythm holds
- **W20 SAT R4 BBJ 1:27 @ 20 m** — proves race-distance pacing is locked

### Root Cause (cross-reference Brisbane W12, still applicable for 30m)
W12 SUN Baby Hyrox identified the same root cause:
- Quad fatigue post-lunges
- Lactate at WB entry
- Lack of reset before high-cost stations
- Diagnosed in March; resolved at 20 m, NOT at 30 m

### Fix Protocol
1. **Round 1 pacing discipline at 30 m:** target 1:50–2:00 (NOT 1:34)
2. **Race-distance (20–30 m HYROX-spec):** already locked
3. **Practice in Phase 3 Thursday sessions:** controlled R1 to preserve R2 at 30 m
4. **Probe test in Phase 3:** confirm new pacing model under fragment fatigue at 30 m

### Status (post W20 SAT)
- Race-fragment BBJ: **resolved** ✓
- Long-distance (30 m) BBJ pacing: **still active limiter**
- Calf interaction: managed by athlete pacing intelligence

---

## Race Target

- 80 BBJ over 30 m at HYROX as Station 5 of 8
- Target time: 4:00–4:30 (steady cost; not a station to chase)
- Required: R1 pacing discipline to preserve later stations (WB above all)

---

## Append Protocol

Every BBJ-relevant session adds a new row.

Source data: session reports in `state/current_week.md` or `archive/2026/week_NN_report.md`.

Special attention: this is the active primary limiter. Every Thursday and Saturday entry must capture R1 vs R2 timing for fade pattern tracking.

---

## Status update, 2026-08-30 (W35 close-out)

**Dormant a 2nd consecutive week (W34, W35) since the W33 Sat reintroduction.** No BBJ session in either week. This is no longer tracked as a standalone "dormancy risk" — Master Plan v2.3 folds the reintroduction directly into its own W37 measurement-gate ladder (see below), so the next BBJ exposure is structured, not a maintenance-touch afterthought.

## Master Plan v2.3 — official standard correction (2026-08-29)

- Current HYROX Men Pro BBJ race distance is **80 m**, not "80 reps over ~30 m." Older tracker wording above is obsolete training-format language only.
- Formal current 80 m benchmark is still missing.
- BBJ reclassified from a confirmed primary limiter to a **"highest-priority measurement unknown"** — structurally capable of becoming race-defining (station time + next-km penalty), but not labelled a confirmed limiter until race-distance data exist.
- Primary KPI going forward: **BBJ + transition + next 1 km total clock** — not station time alone.

## Master Plan v2.3 — W37 exposure ladder (repaired, 2026-08-29)

1. **Tuesday W37 (2026-09-08):** 2×40 m controlled BBJ, measured lane, 0–20m/20–40m splits recorded, 3:00–4:00 full recovery between reps. Success = mechanics/jump-length consistency, not speed.
2. **Saturday W37 (2026-09-13):** 80 m continuous BBJ baseline (first-ever formal continuous benchmark) → 30–45s transition → 1 km at controlled maximum sustainable effort. Returns two outputs: the 80m station clock/quarter-drift profile, and the post-BBJ 1km cost.
3. **W37 decision rule:** if station time, quarter drift, or post-BBJ run penalty materially threaten the race budget, BBJ is promoted to a confirmed limiter and W41 accumulated-fatigue testing proceeds. If cost is modest and mechanics stable, BBJ becomes maintain/monitor only.
4. **W41 (conditional on W37):** 80 m BBJ under accumulated fatigue → 1 km, compared against the W37 fresh baseline.

Required KPIs from W37 onward: total 80m time, 20m splits (0–20/20–40/40–60/60–80), split drift, jump count per 20m, average jump length, cadence, HR entering/leaving, transition time, post-BBJ 1km total + first 250m + final 750m.
