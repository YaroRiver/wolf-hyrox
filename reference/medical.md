# Medical Constraints — Yaro

> **Information here directly affects training decisions. Read whenever calves, B12, sleep, or cardiac signals appear in data.**

---

## Pernicious Anemia / B12 Deficiency

**Diagnosis:** Pernicious anemia (autoimmune impairment of B12 absorption)

**Implications for training:**
- B12 absorption via diet is insufficient → injection therapy required
- B12 deficiency contributes to muscular fatigue, calf cramping, reduced fatigue tolerance
- Without B12 management, training quality and recovery degrade

### Current B12 Protocol
- **Frequency:** once per month
- **Timing:** typically from the beginning of the month
- **Dose:** 1 ml per injection
- **Last injection:** 2026-06-02 (W23 MON — athlete confirmed 2026-06-06)
- **Previous injection:** 2026-05-14 (W20 THU — calves improved significantly post-injection)

### Coaching Rules
- Track every B12 injection date in `trackers/readiness_trend.md` or daily current_week.md entries
- If calf symptoms escalate without recent B12 → flag possible deficiency or timing miss
- B12 timing matters for recovery; do not stack hard sessions immediately post-injection
- Monthly injection cadence means risk window late in the month before next dose; calibrate Saturday probes accordingly when injection is overdue

---

## Calf Status — Load-Sensitivity Watch

**Athlete correction (2026-07-05):** this is not a diagnosed chronic condition. It is an overreach strain — calf/Achilles/soleus pain appeared when training volume/intensity was pushed hard, consistent with the athlete's general pattern of self-directed overload. Framed here as a load-sensitivity watch, not a standing chronic injury. The history below (real, tracked signals) is kept for context; treat it as "how this athlete's calves respond under accumulated load," not as an ongoing diagnosis.

**History:**
- W17 onward: intermittent calf tightness during running and BBJ
- W18 TUE 2026-04-28: near-cramp signal after heavy lunges + sled pull → BBJ removed Wednesday for protection
- W19–W20: warning signals returned (cramping attempts, under-knee pulling)
- W20 THU 2026-05-14: B12 injection corrected calf state significantly; session executed clean
- W20 FRI 2026-05-15: calves held through aerobic reset

**Risk pattern:**
- Calves flare under accumulated load (multiple high-impact days in sequence)
- BBJ + speed running + lunges combo = high calf cost
- Sleep debt amplifies risk
- B12 timing window matters (late in month = higher risk)

**Hard rules:**
- Morning calf rating 0–2/10 → Green, proceed
- Morning calf rating 2.5–3.5/10 → Yellow, modify (reduce BBJ distance, lower lunge load)
- Morning calf rating 4/10+ → Red, no high-impact session
- Night cramp attempt → Red regardless of other markers
- Under-knee pulling during warm-up → Red, abort session

**Daily tracking:** required in current_week.md morning readiness blocks

**Adductors added as a watch-item (athlete request, 2026-07-05):** no adductor issue is on record to date — this is a new signal to track going forward, alongside calves, particularly post-loaded-carry and post-lunge sessions and during the post-Sydney recovery window. Same rating scale and hard rules apply until a distinct pattern (if any) emerges.

---

## Planned GP Checkup (2026-07-05, pre-Melbourne-block baseline)

Athlete drafted a full checkup request to his GP, to be actioned as part of Phase 0 (`reference/master_plan_melbourne_draft_v1.md` §6, W29 "Rule 0"). Full requested panel, for reference when results come back:

- **General/iron:** FBC, iron studies, ferritin, transferrin/saturation
- **B12/pernicious anaemia:** active B12 (holotranscobalamin), serum B12, serum folate, MMA, homocysteine, intrinsic factor antibodies, parietal cell antibodies
- **Kidney/electrolytes:** UEC, eGFR, sodium, potassium, chloride, bicarbonate, calcium, phosphate, magnesium, uric acid
- **Liver/protein:** LFT (ALT/AST/ALP/GGT/bilirubin), albumin, total protein
- **Muscle/inflammation:** creatine kinase (CK), hs-CRP, ESR
- **Metabolic:** fasting glucose, HbA1c, lipid profile
- **Vitamins/hormones:** vitamin D, TSH, free T4, free T3, morning cortisol, total/free testosterone, SHBG
- **Cardiac:** resting 12-lead ECG, referral for echocardiogram, referral for exercise stress test/stress ECG
- **GI (B12-history driven):** discuss gastroscopy/colonoscopy referral

**New symptom details surfaced in this request (not previously logged in this file):**
- **Post-race cramping was full-body, not calf-only:** strong cramps after finishing Sydney, in calves, thighs, and adductors/groin. Previously this file only tracked calf/Achilles — the thigh/adductor/groin involvement is new information and broadens the post-race cramp picture beyond the calf-only framing.
- **Cardiac "jolts":** athlete describes occasionally noticing brief unusual heart sensations ("jolts"), alongside a low resting heart rate (athletic bradycardia). This is being raised with the GP directly, ahead of any maximal VO₂max testing or hard training resumption. Distinct from, but relevant context alongside, the W13 cardiac event below.

**Coaching rule:** no maximal-effort testing (VO₂max field test, hard sim work) until GP/cardiac clearance is back, regardless of how W28/W29 recovery gates read otherwise.

## GP Checkup Results (2026-07-16 review of 2026-07-11 bloods) + Holter + Stress Echo Booking

**Holter monitor:** Athlete reports (verbal, from GP, 2026-07-16) — normal, no significant rhythm abnormality found during the monitoring period. **Not yet seen as a written report** — logged as athlete testimony, not a verified document. A Holter captures ambulatory/resting rhythm; it does not capture exercise-induced arrhythmia or ischemia, which is exactly what the "jolt" pattern (correlated with deep athletic bradycardia ~42–43 bpm during heavy training) needs ruled out.

**Cardiac stress test — booked, not yet done:** Transthoracic/Stress Echocardiogram, Victoria Heart, Windsor VIC, **Monday 2026-07-27, 16:00**. This is the actual clearance gate for exercise-induced cardiac response. **The coaching rule above stays in force until this test is done and reviewed — a normal Holter does not satisfy it.**

## Stress Echocardiogram Result (2026-08-02, athlete-reported)

**Result:** Normal ("echo v normi" — athlete verbal report, 2026-08-02, six days after the 2026-07-27 test). **Not yet seen as a written report** — same caveat as the Holter above: logged as athlete testimony pending the formal document.

**Coaching implication:** This was the standing clearance gate for maximal-effort work (VO₂max field test, hard sim work, WB/sled/BBJ ceiling probes, sprint work) held since W28. With a normal result, that specific restriction lifts. The permanent rule is unchanged and does not depend on this or any test: any jolt/palpitation sensation → immediate abort, no exception.

**Bloods (verified from pathology report, collected 2026-07-11, referred by Dr Ilona Jakab):**
- HbA1c 4.9% (30 mmol/mol) — excellent, no diabetes signal.
- FBC/Hct/RBC/platelets/white cells/ESR — all normal, no anaemia, no inflammatory pattern.
- CRP <1 — no systemic inflammation.
- Vitamin D 134 nmol/L — strong.
- Folate 29.0 nmol/L — strong.
- B12 768 pmol/L (H, ref 163–740) — mildly elevated, consistent with monthly B12 injection therapy, not a concern.
- TSH 2.69 mU/L — normal, euthyroid.
- Liver panel (bilirubin, ALP, GGT, ALT, AST, albumin) — all normal.
- Electrolytes/kidney: Sodium 146 (H, ref 135–145), Bicarbonate 19 (L, ref 20–32), Urea 8.4 (H, ref 3.0–8.0), eGFR 81 (>59, acceptable but not >90 as in the 2025-03 baseline) — mild deviations, plausibly hydration/pre-analytical; report itself notes eGFR 60–90 can be normal if stable over time. **Follow-up item, not urgent.**
- **Glucose discordance (new, not flagged in athlete's own summary):** same draw shows two glucose values — Serum glucose (fasting) 6.3 mmol/L (H, ref 3.6–6.0) vs Plasma glucose (fasting) 5.0 mmol/L (normal). These should track together; a same-draw discordance this size is unusual. Given HbA1c 4.9% is excellent, this is very unlikely to indicate real dysglycaemia — most likely a pre-analytical/assay artifact — but **raise directly with the GP** rather than dismiss silently, since it wasn't in the athlete's own report summary.
- Lipids: Total cholesterol 5.7 (H, target <4.0 per report's own high-risk guideline), LDL 3.9 (H, target <2.5), Cholesterol/HDL ratio 4.8 (H, target <4.5 or better), Non-HDL 4.5 (H, target <3.3). HDL itself is good (1.19, >1.00 target). **Follow-up item for GP discussion** — not race-blocking, but worth addressing over the Melbourne block (diet, and physician's read on personal cardiovascular risk given the broader cardiac workup already underway).

**Cramp detail clarified (athlete, 2026-07-05):** the full-body cramping did not happen during the race or immediately at the finish line — it happened afterward, at rest. Athlete lay down post-race and the cramps arrived as a wave (calves/thighs/adductors/groin, per above), resolved by getting up and moving again, and did not recur afterward. Pattern: rest-onset, wave-like, movement-responsive, single episode, non-recurring. Worth mentioning to the GP as post-exertional rest cramping, not active in-race cramping.

---

## Cardiac History (Brisbane Build, W13)

**Event:** 2026-03-27 (W13 FRI) — irregular heartbeat sensations during pre-session warm-up
**Decision:** training cancelled, full rest taken
**Recovery:** SAT walk only, SUN 10 km clean run with 0 cardiac events monitored before/during/after

**Interpretation (athlete + analysis):**
- Likely autonomic imbalance from accumulated training stress, not structural
- No recurrence in W14–W20

**Pattern detail clarified (athlete, 2026-07-05) — resting HR correlation:** the "jolt" sensations (skipped-beat feeling) began during a period of heavy training volume + work load, coinciding with VO₂max testing, when resting heart rate dropped to roughly **42–43 bpm**. Athlete was frightened by this. By contrast, during the post-vaccine illness period, resting HR rose to around **64 bpm** (elevated from athletic baseline) and, per the athlete's own account, **zero jolt episodes occurred** for the entire duration of that higher-resting-HR illness window. Pattern as reported: lower resting HR (deep athletic bradycardia, ~42–43) correlates with jolt episodes; higher resting HR (~64, illness-elevated) correlates with none. Flagged explicitly for the GP/cardiac referral (see "Planned GP Checkup" above) — this is exactly the kind of pattern a resting ECG/Holter or stress test is meant to characterize (e.g. bradycardia-associated ectopy is a recognized, often benign finding in endurance athletes, but should not be assumed without the actual test).

**Coaching rules:**
- Mention to physician before race for clearance (flagged in W13 assessment)
- If any palpitation sensation returns → immediate session abort, walk-only recovery, no return to quality until clean
- HRV pattern monitoring also serves as cardiac watch

---

## Sleep Profile

**Status:** chronic sleep debt; no formal disorder diagnosed

**Pattern:**
- Difficulty with sleep onset (the primary issue)
- Variable restful percentage (35–47% across W20)
- 3-day rolling target frequently below 100%
- Best nights observed during build: W18 MON 7h53 / HRV 88, W17 SAT post 95★ / HRV 80

**Coaching rules:**
- Sleep < 6h00 → Red for hard sessions
- Sleep 6h00–6h30 → Yellow
- Sleep 7h30+ → Green threshold (achieved when achieved, not assumed)
- Two consecutive nights < 7h00 → automatic Yellow even if other markers green

---

## Other

- No known allergies relevant to training
- No injury history requiring permanent modification beyond calf protocol
- No medication interactions with training nutrition (B12 protocol noted above)

---

## Update Protocol

This file updates only when:
1. New medical diagnosis or test result
2. B12 protocol changes (frequency / dose / timing)
3. New injury or condition emerges
4. Cardiac event repeats
5. Sleep pattern changes structurally

For day-to-day calf / sleep / HRV tracking: daily entries in current_week.md.
