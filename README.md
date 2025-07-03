# 🪔 Diwali Sales Data — Exploratory Data Analysis

## 📌 Project Goal
Understand purchasing behaviour during India's Diwali festival and surface insights that could help retailers optimise marketing, product mix and regional campaigns.

## 💾 Dataset
- **File:** `Diwali Sales Data.csv` 
- **Rows:** 11,330   **Columns:** 15  
- **Time‑frame:** October–November 2020  
- **Description:** Contains customer purchase data during the Diwali festival, including gender, age, occupation, marital status, product category, and amount spent.
  

## 🔬 Key Steps
| Step | Highlights |
| --- | --- |
| **1. Import & Inspect** | Checked dtypes, nulls, basic stats |
| **2. Clean** | Dropped `Status`, fixed encoding, converted `Amount → int` |
| **3. Feature Engineering** | Created `age_group`, renamed `Marital_Status → Shaadi` |
| **4. Visual EDA** | 10+ bar plots (gender, age, state, occupation, product category) |
| **5. Insights** | Segmented findings summarised below |

## 📊 Top Insights
- **Demographic sweet‑spot:** Married women, 26–35 yrs, spend the most.
- **High‑value states:** Uttar Pradesh › Maharashtra › Karnataka drive ~45 % of revenue.
- **Occupation wins:** IT, Healthcare, Aviation customers show highest average basket.
- **Product mix:** Food, Clothing, Electronics = 60 % of sales.

*(See “Conclusion” section in the notebook for full commentary.)*

## 📁 Files Included
| File | Description |
|------|-------------|
| `Employee_Attrition.pbix` | Main Power BI dashboard file |
| `Emp_attrition_csv.csv` | Source dataset |


## 🚀 Quick Start

```bash
# clone the repo
git clone https://github.com/<your‑username>/diwali-sales-eda.git
cd diwali-sales-eda

# create environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# launch notebook
jupyter notebook notebooks/Diwali_Sales_EDA.ipynb
