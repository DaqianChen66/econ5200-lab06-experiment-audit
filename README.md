# econ5200-lab06-experiment-audit
# Experiment Design Audit — Power, Selection & Weighting

## Objective
I studied how experiment design and selection bias can affect statistical results.

## Methodology
- I audited an A/B test with 2% treatment traffic and 1,000 treatment users.
- I calculated statistical power and the required sample size.
- I compared a naive wellness-program estimate with an IPW estimate.
- I used Meng's data defect correlation to measure the effect of selection bias.

## Key Findings
- The original A/B test had only 19.8% power to detect a 0.8pp lift.
- Reaching 80% power required 12,514 users per group.
- Splitting the same 50,000 users evenly would give 97.7% power.
- The naive wellness-program estimate was -$1,396, compared with the true effect of -$500.
- IPW improved the estimate to -$522.
- 389,090 biased poll responses had an effective sample size of about 140 random observations.
