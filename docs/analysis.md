# Analysis

## Purpose

Guidance for post-session and longitudinal analysis of structured workouts.

## Key metrics to review

- Normalized Power (NP)
- Intensity Factor (IF)
- Training Stress Score (TSS)
- Peak and average power by interval
- Heart rate response and recovery
- Variability Index (VI) and power consistency

## How to perform an analysis

1. Export session data (power, cadence, HR) at 1s or 3s resolution.
2. Compute NP, IF, and TSS for the session.
3. Compare interval targets vs actuals: power, duration, and recovery.
4. Check heart-rate lag and perceived exertion (RPE) for internal load.
5. Track changes across weeks: interval power, recovery, and RPE trends.

## Practical checks

- Were intervals completed within ±2.5% of the target power?
- Did RPE and HR trend downward for the same power (improvement)?
- Did variability increase under fatigue (rising VI)?

## Tools and exports

- Use GoldenCheetah, TrainingPeaks, or Intervals.icu for computations.
- Export CSV or FIT/TCX for reproducible analysis.

## Example outputs to save

- Session summary CSV (time, power, HR, cadence)
- Interval summary table (target, mean, stddev, RPE)
- Weekly progression chart (interval power vs week)

---

If you'd like, I can add a small Python script to compute NP/IF/TSS from a CSV export.
