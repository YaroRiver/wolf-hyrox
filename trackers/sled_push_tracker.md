# Sled Push Tracker

> **Append-only log of all Sled Push performance data. STATE.md derives current working load from this file.**

**Iron Viking Gym track: 18 m (working format)**
**Race standard: 50 m at HYROX-spec weight (~152 kg male)**

---

## Working Load Progression

| Date | Week | Block | Load | Format | Times | Notes |
|---|---|---|---|---|---|---|
| 2026-03-02 onward | W10–W11 | Brisbane | 204 kg | 40 m race-distance | 1:31–1:35 | Brisbane race-spec |
| 2026-03-12 | W11 THU | Brisbane | 204 kg | 40 m | 1:22 ↑ | Best race-distance time |
| 2026-03-17 | W12 TUE | Brisbane | 220 kg | gym sets | — | Working at 220 |
| 2026-03-24 | W13 TUE | Brisbane | **225 kg PR** | 2 sets gym | S1 51s / S2 49s | First major load jump; clean execution |
| 2026-03-31 | W14 TUE | Sydney W1 | **240 kg PR** | 20 m fresh | 44 sec | New fresh PR; "race-fresh benchmark" |
| 2026-04-14 | W16 TUE | Sydney W3 | 240 kg | gym | "better than expected" | Repeatable working |
| 2026-04-21 | W17 TUE | Sydney W4 | **245 kg PR** | 3×18 m fresh | 50 / 51 / 53 sec | New working PR; first 245 confirmed |
| 2026-04-28 | W18 TUE | Sydney W5 | 240 kg | 3×18 m | 50 / 49 / 42 sec | S3 best time; calf near-cramp signal after |
| 2026-05-12 | W20 TUE | Sydney W7 | 240 kg | 3×18 m Yellow | 53 / 47 / 46 sec | Calf-protected day; clean despite Yellow |
| 2026-07-28 | W31 TUE | Melbourne Phase 1 W1 | 210 kg | 3×20 m | 40 / 33 / 32 sec | Post-cardiac-clearance return; lighter than the 245 kg overload-lane ceiling but +1 set vs plan; clean progressive |
| 2026-08-01 | W31 SAT | Melbourne Phase 1 W1 | **252 kg (new working reference)** | 4×20 m compromised (600m run + sled + 25 WB per round) | 39 / 43 / 48 / 50 sec | Self-directed overload, 7 kg above the written 245 kg cap; progressive controlled decline (+11 sec R1→R4, ~28%); no stall, no calf signal; correctly stopped before optional R5 (technique, not sled) |
| 2026-08-04 | W32 TUE | Melbourne Phase I W2 | 224 kg | 4×20 m | 32 / 35 / 38 / 37 sec | Above the 210–220 kg prescription; final set recovered 1 sec vs Set 3, retained force production; held ahead of the heavy Wed farmer carry |
| 2026-08-11 | W33 TUE | Melbourne Phase I W2 | 227 kg | 4×20 m | 35 / 33 / 34 / 33 sec | Slightly above the 224kg plan; 2 sec spread, no fade, final set 2 sec faster than Set 1 — clean maintenance-load execution ahead of a session that later revealed early illness onset |

---

## Thursday HYROX Rhythm — Race-Style Push at 204 kg

| Date | Format | R1 | R2 | Notes |
|---|---|---|---|---|
| 2026-04-16 W16 THU | 204→216 kg / 2 rounds | 41s | 43s | Slight load test |
| 2026-04-23 W17 THU | 204 kg / 2 rounds | 42s | 43s | Stable race-style |
| 2026-04-30 W18 THU | 204 kg / 2 rounds | 37s | 42s | R2 cost rising |
| 2026-05-14 W20 THU | 204 kg / 2 rounds | — | — | Times not captured separately |

---

## Demonstrated Capacity (Locks)

- **Working load (gym 18 m):** **245 kg** (W17 TUE 2026-04-21)
- **Working load fresh 20 m:** 240 kg (W14 TUE 2026-03-31 PR)
- **Race-distance 40 m:** 204 kg / 1:22 (Brisbane W11 THU)
- **Compromised working load (Melbourne build):** 252 kg × 4 × 20 m, 39/43/48/50 sec (W31 SAT 2026-08-01) — self-directed overload past the written 245 kg cap, held together across 4 rounds under real running/WB fatigue
- **Progression rule (Melbourne build, per `reference/master_plan_melbourne_draft_v1.md` §4):** sled frozen at proven working loads — already >20% above race requirement, no further load-chase needed; progression target is reducing time drift and transition cost, not adding weight

---

## Race Target

- HYROX Pro Men 45–49 sled push: ~152 kg / 50 m
- Required time: 1:20–1:40
- Current working load 245 kg vastly exceeds race demand → station is a weapon
- Phase 3 focus: race-distance simulation at race-weight for transitions

---

## Append Protocol

Every sled push session result added as new row.

**Never edit existing rows.** If correction needed, append new row with note.

Source data: session reports in `state/current_week.md` or `archive/2026/week_NN_report.md`.
