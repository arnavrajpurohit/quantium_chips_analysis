# Quantium Retail Analytics – Customer Segmentation and Trial Analysis

This project is part of the Quantium Analytics Virtual Experience Program. It simulates a real-world retail analytics engagement, helping a supermarket client understand chip purchasing behavior and evaluate the success of a retail trial across selected stores.

## Repository Structure

```
quantium_chips_analysis/
├── data/
│   ├── raw/                # Raw input files
│   └── processed/          # Cleaned data
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_trial_analysis.ipynb
├── report/
│   ├── final_presentation.pdf
├── README.md
└── requirements.txt
```

---

## Task 1: Data Cleaning & Customer Analytics

In this task, we cleaned and explored customer and transaction data to identify trends in chip purchasing behavior. Key steps included:

- Merging transaction and customer datasets
- Extracting features like brand and pack size
- Identifying top-performing customer segments based on:
  - Lifestage
  - Premium vs Budget customer classification
- Exploring product sales distribution and spending behavior

**Output:** Cleaned dataset (`merged_data.csv`), customer insights, and visuals

---

## Task 2: Trial vs Control Store Performance Analysis

We evaluated the impact of a trial marketing campaign run in Stores 77, 86, and 88. Key actions:

- Selected control stores based on sales, customers, and transactions
- Used statistical and visual comparisons (e.g., line charts, t-tests)
- Assessed trial outcomes across three KPIs:
  - Total sales revenue
  - Total number of customers
  - Average number of transactions per customer

**Output:** Control store pairings, trial uplift plots, and significance tests

---

## Task 3: Executive Report & Strategic Recommendation

We compiled findings from Tasks 1 and 2 into a client-ready PowerPoint report. This report follows the Pyramid Principle and includes:

- Executive summary of key insights
- Category analysis of spending trends by customer group
- Trial performance outcomes with visual evidence
- Final recommendation on trial success and scalability

**Output:** `final_presentation.pdf` (PowerPoint exported to PDF)

---

## Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Excel (optional for charting)
- PowerPoint (final report formatting)

---

## Summary

This end-to-end project demonstrates a practical application of data cleaning, customer segmentation, A/B trial evaluation, and stakeholder communication — simulating the hybrid analyst-consultant role typical at Quantium.

### 📄 Final Report

Due to confidentiality markings in the official template, the original presentation is not included in this repository. However, a version of the insights and findings can be made available on request.

