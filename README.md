# Task 1 — Sales Performance Dashboard

**Author:** Elethu Mahlangeni

---

## Overview

This project takes a real dataset of online retail transactions and turns it into an interactive, browser-based sales dashboard. No coding knowledge is required to use it.

---

## Files

| File | Description |
|------|-------------|
| `online_retail.csv` | Raw sales data — 541,000+ rows covering Dec 2010 to Dec 2011 |
| `sales_dashboard.html` | Interactive dashboard — open in any browser |
| `README.md` | This file |

---

## How to Use the Dashboard

1. Double-click `sales_dashboard.html` — it opens in Chrome, Edge, or Firefox.
2. Click **"Choose CSV File"** and select `online_retail.csv`.
3. All charts and KPIs load automatically within seconds.
4. To reload with updated data, click **"Load new file"** (top-right corner).

---

## Key Findings

- **Total Revenue:** £10,666,684 across 19,960 orders
- **Revenue peaks in November** — nearly double August — driven by wholesale Christmas buying
- **No Saturday orders** and peak activity at 10 AM confirms a B2B customer base
- **Top product:** PAPER CRAFT, LITTLE BIRDIE — #1 in both revenue and units sold
- **84.6% of revenue** comes from the UK; 37 countries represented internationally
- **Cancellation rate: 1.71%** — operationally very healthy

---

## Top Recommendations

1. Prepare stock and marketing from **August** to capture the Q4 surge
2. **Grow Netherlands, Ireland, and Germany** — already strong, high upside
3. Never let **REGENCY CAKESTAND 3 TIER** or **PAPER CRAFT, LITTLE BIRDIE** go out of stock
4. Recover **25% anonymous transactions** by introducing a loyalty/account system
5. Run **Q1 promotions** (Jan–Mar) to smooth the post-holiday revenue dip
6. Segment the **4,338 customers** by recency, frequency, and spend — top 20% likely drive 80% of revenue

---

## Data Cleaning Summary

| Issue | Rows Removed |
|-------|-------------|
| Cancelled orders (InvoiceNo starts with "C") | 9,288 |
| Negative quantities (returns) | Excluded |
| Zero-price items | Excluded |
| Missing product descriptions | 1,454 |
| **Retained** | **530,104 rows (97.8%)** |

A `Revenue` column was added: `Quantity × UnitPrice`.

---



