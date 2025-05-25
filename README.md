# Quantium Retail Analytics – Customer Segmentation for Chips Category

## Overview

This project is part of a data analytics case study involving Quantium's retail transaction data. The objective is to analyze customer purchasing behavior in the chips category and deliver actionable business insights. The workflow includes data preprocessing, merging datasets, performing exploratory data analysis (EDA), and segmenting customers based on their buying patterns.

---

## Objectives

- Clean and prepare customer and transaction datasets
- Explore patterns in chip purchases
- Identify customer segments using key behavioral and demographic attributes
- Provide strategic recommendations based on insights

---

## Dataset Description

The dataset includes:
- **Customer Data**: Demographic attributes such as `Lifestage`, `Premium Customer` flags, and `Customer ID`
- **Transaction Data**: Contains `DATE`, `PRODUCT_ID`, `QUANTITY`, `SALES_VALUE`, and other attributes
- **Product Data**: Describes products such as `Brand`, `Product Name`, and `Pack Size`

---

## Project Structure

```
quantium_chips_analysis/
│
├── data/                     # Raw and cleaned datasets
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb     # Data loading and preprocessing
│   ├── 02_exploratory_analysis.ipynb  # Visual and statistical analysis
│   └── 03_customer_segmentation.ipynb # Insights and segmentation
│
├── outputs/                  # Plots and exported results
│   └── report.pdf            # Final report or visual summary
│
├── README.md                 # Project overview and instructions
└── requirements.txt          # Python packages used
```

---

## Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Scikit-learn (for basic segmentation logic if needed)

---

## Key Insights

- Premium customers in certain life stages (e.g., young singles/couples) tend to spend more per transaction.
- Significant differences were observed in brand preference and pack size across segments.
- Potential to target high-value segments through personalized promotions.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/arnavrajpurohit/quantium_chips_analysis.git
   cd quantium_chips_analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

---

## Author

**Arnav Rajpurohit**  
Data Analytics Enthusiast  
[LinkedIn](https://www.linkedin.com/in/arnavrajpurohit) | [GitHub](https://github.com/arnavrajpurohit)

---

## License

This project is licensed for educational purposes only. Data is used as provided in the Quantium case study.
