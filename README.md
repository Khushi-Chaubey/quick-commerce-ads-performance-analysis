# Quick Commerce Ads Performance Analysis

A self-built practice project simulating performance marketing analysis for a quick-commerce platform (Blinkit-style), created to prepare for a Business Analyst Intern interview.

## What this project does

Analyzes 12 mock ad keywords from a simulated quick-commerce campaign and calculates key performance metrics to identify which keywords are worth scaling and which should be paused or optimized.

## Metrics calculated

| Metric | Formula | What it tells you |
|---|---|---|
| **CTR** (Click-Through Rate) | Clicks ÷ Impressions | How relevant/appealing the ad is to people who see it |
| **CPC** (Cost Per Click) | Spend ÷ Clicks | How expensive each click is |
| **ROAS** (Return on Ad Spend) | (Conversions × Avg Order Value) ÷ Spend | Whether the keyword is actually profitable |

All metrics are built as **live Excel formulas**, not hardcoded numbers — changing any input (impressions, clicks, spend, conversions) automatically updates CTR, CPC, and ROAS.

## File structure

- **`Blinkit_Ads_Campaign_Analysis.xlsx`**
  - **Sheet 1 — Campaign Data:** Raw inputs (blue) + calculated metrics (black formulas) for each keyword, with totals row
  - **Sheet 2 — Insights & Recommendations:** Written analysis of best/worst performers and a budget reallocation recommendation

## Key findings

1. **Best performer:** "10 minute grocery delivery" — highest conversions (142) and strong ROAS → scale budget here
2. **Worst performer:** "baby products online" — very low conversions (4) relative to spend → pause or revise creative
3. **High CTR but low conversion efficiency:** "blinkit offers today" gets clicks but converts less efficiently → check landing page relevance
4. **Underused opportunity:** "blinkit near me" — low CPC, solid ROAS → good candidate for increased budget
5. **Recommendation:** Shift ~20% of spend from the two lowest-ROAS keywords into the two highest-ROAS keywords

## Why I built this

This role involves keyword harvesting, bid management, and performance reporting across quick-commerce ad platforms. I wanted hands-on practice with the actual decision-making — not just the vocabulary — so I simulated a small dataset and worked through it the way an analyst would: calculate the metrics, spot the outliers, and turn that into a budget recommendation.

## Tools used

Microsoft Excel / Google Sheets (formulas: basic arithmetic, SUM, SUMPRODUCT)
