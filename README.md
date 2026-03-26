# Brand Performance & ROI Analysis | Two-Wheeler Sector

> Evaluating marketing channel effectiveness and dealership incentive ROI — enabling a 10% budget reallocation toward higher-converting digital campaigns.

---

## Overview

Marketing spend in the two-wheeler sector is distributed across a wide range of channels — digital ads, dealership incentives, on-ground activations, and more. Without rigorous measurement, budgets tend to stay where they are rather than where they work.

This project maps **marketing spend against sales conversion rates** to calculate ROI per channel, identifies underperforming allocations, and produces a data-backed recommendation for budget reallocation.

---

## Key Results

| Metric | Value |
|---|---|
| Marketing channels evaluated | Multiple (digital, dealership, traditional) |
| Underperforming channels identified | Yes — specific channels flagged |
| Budget reallocation recommended | 10% shift toward higher-converting digital channels |
| Method | Spend-to-conversion mapping + incremental ROI analysis |

---

## Problem Statement

The marketing team had visibility into spend but limited insight into **what that spend was producing**. Decisions about channel budgets were often based on historical allocation patterns rather than performance data. This project changes that by:

- Establishing a unified ROI metric across channels
- Identifying which channels drive incremental sales vs. which capture existing intent
- Recommending a reallocation that improves overall marketing efficiency

---

## Methodology

```
Marketing Spend Data (by channel, by period)
        ↓
Sales Conversion Data (leads → test drives → purchases)
        ↓
Attribution Mapping (spend aligned to conversions)
        ↓
ROI Calculation per Channel
        ↓
Incremental Uplift Analysis
        ↓
Reallocation Recommendation
```

### ROI Formula Used

```
Channel ROI = (Revenue Attributed to Channel - Channel Spend) / Channel Spend × 100
```

---

## Channels Evaluated

| Channel | Type |
|---|---|
| Digital display & search ads | Online |
| Social media campaigns | Online |
| Dealership incentive programmes | Offline |
| On-ground activations & test drive events | Offline |
| Traditional media (print, radio) | Offline |

---

## Key Insight

> Digital channels showed **1.8× higher conversion-to-cost ratios** compared to traditional channels, yet were receiving only 35% of the total marketing budget at baseline.

A 10% budget shift from low-performing traditional spend to targeted digital campaigns was projected to increase marketing-attributed sales by ~8% without increasing total spend.

---

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.10 / SQL |
| Data Manipulation | Pandas, NumPy |
| Visualisation | Power BI / Matplotlib / Seaborn |
| Statistical Analysis | Scikit-learn (regression), SciPy |
| Environment | Jupyter Notebook |

---

## Repository Structure

```
brand-roi-analysis/
│
├── notebooks/
│   ├── 01_data_preparation.ipynb          # Spend and conversion data cleaning
│   ├── 02_attribution_mapping.ipynb       # Linking spend to sales outcomes
│   ├── 03_roi_calculation.ipynb           # ROI computation per channel
│   ├── 04_channel_comparison.ipynb        # Visualising channel performance
│   └── 05_reallocation_model.ipynb        # Budget optimisation scenarios
│
├── data/
│   └── sample_marketing_data.csv          # Anonymised sample dataset
│
├── src/
│   ├── attribution.py                     # Attribution logic
│   ├── roi.py                             # ROI calculation functions
│   └── optimise.py                        # Budget scenario modelling
│
├── reports/
│   └── roi_analysis_summary.pdf           # Executive summary with charts
│
├── requirements.txt
└── README.md
```

---

## Sample Output

```
Channel: Digital Search Ads
  Total Spend:        ₹12,00,000
  Attributed Revenue: ₹38,40,000
  ROI:                220%
  Verdict:            ✅ High performing — increase allocation

Channel: Print Advertising
  Total Spend:        ₹8,00,000
  Attributed Revenue: ₹9,60,000
  ROI:                20%
  Verdict:            ⚠️ Low performing — reduce allocation
```

---

## Status

> 🚧 Notebooks and anonymised sample data will be added progressively. Star the repo to follow updates.

---

## Contact

**[Your Name]**
[LinkedIn URL] | [Email]
