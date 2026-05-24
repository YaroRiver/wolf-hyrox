# STATE — wolf-hyrox single source of truth

> **Read this file FIRST in every new chat. All other files are conditional.**

---

## TIME ANCHOR
- **Last updated:** 2026-05-24 (Sunday evening, Melbourne)
- **Race day:** 2026-07-03 (Friday) — HYROX Sydney
- **Days to race:** 40 (end of W21) / 39 (Monday W22 start)
- **Sydney Build Day:** 57 (Monday 2026-05-25)
- **Sydney Build Week:** 9
- **Annual Week:** 22 (starting 2026-05-25)
- **Phase:** Phase 3 — RACE SPECIFICITY (Week 1 — De-load/Transition)
- **Phase 2 BUILD:** COMPLETE (W9–W21, 8 build weeks, zero missed hard days)
- **Next phase boundary:** W23 (2026-06-01) → Phase 3 real build (post-vaccine)

---

## ATHLETE SNAPSHOT
- **Yaro · 46 · Pro Men 45–49 · 196 cm · 84 kg · BMI 21.9**
- **VO₂max:** 58 ml/kg/min (PR 2026-05-18 W21 Mon)
- **HR recovery:** 160→99 bpm in 2 min (excellent)
- **Race target:** 1:15:00 HYROX Sydney 2026-07-03
- **Gym:** Iron Viking, Moorabbin (Australia)
- **Medical:** Pernicious anemia, B12 monthly (last 2026-05-14, next ~2026-06-14); chronic calf-Achilles-soleus zone; cardiac event W13 resolved
- **2025 Melbourne baseline:** 1:33:44, rank #603, Pro M 45-49. Gap to target: 18:44.
- **Detailed profile:** `reference/athlete_profile.md`

---

## CURRENT LOCKS (verified dates)

| Capacity | Lock |
|---|---|
| **Wall Ball** | 50 clean single-set under full HYROX fatigue (W21 Sat); 35×3=105 under fatigue (W21 Thu); peak 60 fresh (W12). Race = break pattern (40-45 open + 35 + remainder), NOT unbroken 100. |
| **VO₂max** | 58 (PR W21 Mon 2026-05-18) |
| **Sled push** | 246 kg overshoot (race 202 kg, +22%) — confirmed, retired from chase |
| **Sled pull** | 206 kg × 20 m / 1:05 PR (race 153 kg, +35%) — confirmed |
| **Run** | 4:19/km @ HR147 Yellow (W21 Mon); 4:41/km @ HR150 under fatigue (W21 Sat) |
| **BBJ** | 80-90m session exposure; ~4.0 sec/m (gap to race target 1:55-2:00/m) |
| **Lunges** | 80m @ 28+28kg under fatigue; race 100m @ 30kg sandbag |
| **Tissue** | Calf intact through heaviest week W21; held at 2/10 post-Sat probe |

---

## ACTIVE LIMITER & RISKS

**Priority limiter order (Phase 3 entry):**
1. **BBJ pace/distance** — biggest race-completion gap (2× slower than race pace; no 80m continuous yet)
2. **Wall Ball ceiling** — improving (50 clean fatigue); target 55-60; not solved
3. **Lunge distance** — 80m → need 100m + sandbag specificity
4. **Untracked stations** — Ski/Row/Farmers no baseline yet (PENDING A/B/C answer)

NOT limiters: sled (confirmed), CV capacity (VO₂max 58), absolute strength.

**Active watch flags:**
- **Immune:** light nose/throat signal 3 days (Thu/Sat/Sun W21), not escalating. Resp rate 16.6→17.6. Monitor through vaccine.
- **HRV:** crashed to 35 Sunday (-22%) absorbing Sat probe; HR dip recovered to 26% (clean absorption). Expect rebound over W22.
- **Flu vaccine:** Wed 2026-05-27 16:15, Burwood Guardian Medical — restructures W22 (Tue = main quality, Wed-Thu light).
- **Power-nap dependency:** needed nap-to-train twice W21 — Phase 3 should start from Green mornings.

**Reference:** `state/limiters_now.md`

---

## ACTIVE PROBE TARGET
- **Saturday 2026-05-30 (W22 — CONDITIONAL):** WB ceiling push — floor 50 / target 55 / stretch 60 clean
- **Gate:** HRV ≥ 45 + no vaccine fatigue + immune clear + calves ≤ 1/10 (ALL required)
- **Stop rule:** clean technical failure ONLY — no ugly reps (lesson from W21 Sat)
- **If gate not met:** skip probe, W22 de-load stands on its own
- **Reference:** `trackers/probe_log.md`

---

## CALENDAR (race horizon)
- **W22 (05-25→05-31):** Phase 3 W1 — de-load/transition (vaccine Wed 2026-05-27)
- **W23-24 (06-01→06-14):** Phase 3 real build (WB ceiling, BBJ distance, lunge distance, station baselines)
- **W25-26:** Phase 4 taper
- **W27:** Race week (race 07-03)

---

## PENDING DECISIONS
1. **Ski Erg / Row / Farmers Carry** — training frequency A/B/C (needed for W23-24 station design)
2. **v3.1 master plan** — integrate corrected race math + PATCH 4 (conservative WB opening block) + vaccine-adjusted Phase 3 phasing

---

## READING ORDER FOR NEW CHATS
1. **STATE.md** (you are here)
2. `state/limiters_now.md`
3. `state/current_week.md` (today's session entries)
4. `state/current_week_plan.md` (this week's calibrated plan)

Conditional:
- For coaching decisions: `reference/decision_rules.md`, `reference/probe_rules.md`
- For probe history: `trackers/probe_log.md`
- For station history: `trackers/[station]_tracker.md`
- For phase context: `reference/master_plan.md`
- For deep history: `archive/2026/week_NN_report.md`

---

## WRITE CONTRACT
- **Trackers** (`trackers/*_tracker.md`): append-only, no edits
- **STATE.md**: auto-derived from trackers; Claude updates on lock change
- **current_week.md**: daily append by athlete + Claude (chronological)
- **Archive** (`archive/2026/week_NN_*.md`): immutable after weekly close-out

---

**This file last fully refreshed:** 2026-05-24 (Sunday — W21 close-out, W22 open)
**Next mandatory refresh:** Saturday post-probe 2026-05-30 + Sunday 2026-05-31 (W22 close-out)
