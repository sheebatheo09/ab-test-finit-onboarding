# A/B Test Analysis: Onboarding Redesign & Free Trial
### Finit: Habit & Wellness Subscription App

---

## The Business Problem

Finit is a habit-tracking subscription app. Two compounding problems were identified in the new user journey:

1. **Activation gap** — 68% of new users never complete their first habit check-in within 48 hours. Users who don't activate within 48h have 7-day retention of just 11%, vs 54% for those who do.
2. **Paywall friction** — A hard paywall on day 3 drives churn. 61% of churned users said they didn't have enough time to decide if the product was worth paying for.

## The Experiment

**Hypothesis:** Redesigning onboarding to guide users to their first habit check-in immediately, combined with replacing the hard paywall with a 15-day free trial, will increase trial start rate by at least 5 percentage points.

| | Control (A) | Variant (B) |
|---|---|---|
| Post-signup | Generic home screen | Guided first habit prompt |
| Paywall | Day 3, hard paywall | 15-day free trial at end of onboarding |

**Primary metric:** Trial start rate within 24h of onboarding  
**MDE:** 5 percentage points  
**Baseline:** 12% → Target: 17%

## What This Project Covers

| Day | Section | What it demonstrates |
|-----|---------|---------------------|
| 1 | Experiment design | Hypothesis, metrics, sample size from first principles |
| 2 | Data simulation | Realistic user-level data with planted anomalies |
| 3 | Statistical analysis | SRM check, z-test, p-value, confidence intervals |
| 4 | Segmentation | Simpson's Paradox identified and resolved |
| 5 | Ship recommendation | Guardrail analysis + PM-ready decision write-up |

## Tools

- Python 3.11
- pandas, numpy, scipy.stats, matplotlib, seaborn
- Jupyter Notebook

## How to Run

```bash
git clone https://github.com/sheebatheo09/ab-test-finit-onboarding
cd ab-test-finit-onboarding
pip install pandas numpy scipy matplotlib seaborn jupyter
jupyter notebook ab_test_finit_onboarding.ipynb
```

---

*Project built to demonstrate end-to-end product analytics thinking — from business problem to ship decision.*
