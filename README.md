### DecodeLabs Data Analytics Project: Boardroom-Ready Insights 

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-orange.svg)]()
[![Status](https://img.shields.io/badge/Project-Complete-success.svg)]()

An executive-level data analytics framework designed to transform raw transactional data into actionable corporate strategy. Following the structured training disciplines of **The Architect, The Editor, and The Storyteller**, this project processes ecommerce transactions to expose hidden macro-trends, identify operational leaks, and optimize marketing allocation.

---

### Executive Summary & Core Insights

Rather than just displaying data, this project answers the critical business question: **"So What?"** Here are the core strategic observations extracted from the analysis:

* **Revenue Growth Pattern:** Monthly revenues exhibit cyclical spikes and highly consistent mid-year surges, highlighting key windows for targeted marketing blitzes.
* **Product Performance:** Desks and high-ticket electronics drive the largest share of overall gross sales volume. Inventory optimization should prioritize anchoring these categories.
* **Acquisition Mix Efficiency:** Social and Direct referral channels heavily dominate transaction volume. Digital ad spend should be reallocated here to exploit maximum acquisition yield.
* **Operational Leakage:** An analysis of order status counts exposes exactly how much revenue is trapped or lost inside "Cancelled" and "Returned" states, allowing logistical teams to target supply-chain friction points.

---

### Tech Stack & Architecture

* **Language:** Python 3.8+
* **Data Manipulation:** `pandas` for structural extraction, clean datetime conversions, parsing periods, and handling missing data.
* **Visualization Engine:** `matplotlib.pyplot` and `seaborn` for fine-tuned graphic layouts, color-spotlight branding, and high data-to-ink integrity.

---

### Project Repository Structure

```text
├── data/
│   └── Dataset for Data Analytics (3).xlsx - Sheet1.csv  # Raw transaction logs
├── scripts/
│   └── generate_insights.py                              # Core processing script
├── output_charts/                                        # Saved boardroom visuals
│   ├── chart1_revenue_trend.png
│   ├── chart2_product_performance.png
│   ├── chart3_referral_share.png
│   └── chart4_order_status.png
├── README.md                                             # Project documentation
└── requirements.txt                                      # Dependencies list
