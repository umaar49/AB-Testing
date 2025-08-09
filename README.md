# 📊 A/B Testing Analysis – Conversion Rate Comparison
This project analyzes A/B test data to compare conversion rates between two website landing pages — the **old page** (control group) and the **new page** (treatment group). It performs data cleaning, visualization, statistical hypothesis testing, and confidence interval calculation to determine whether the new page leads to a higher conversion rate.

## 📂 Project Structure
ab_data.csv # Dataset containing A/B test results
ab_testing_analysis.ipynb # Python script for analysis
README.md # Project documentation

## 📌 Steps in Analysis
1. **Data Loading & Exploration** – Load dataset with Pandas, check for missing values/duplicates, and inspect group/landing page distributions.
2. **Data Cleaning** – Remove mismatches between groups and landing pages, drop unused columns, and convert timestamps to datetime.
3. **Data Visualization** – Plot conversion counts for each group and daily conversion trends.
4. **Conversion Rate Calculation** – Calculate conversion rates for control and treatment groups.
5. **Statistical Hypothesis Testing** – Perform two-sided z-test for proportions and calculate 95% confidence intervals.

## 🛠 Technologies Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (visualization)
- Statsmodels (statistical tests)

  ## 📈 How to Run the Code
1. Clone the repository  
   ```bash
   git clone https://github.com/umaar49/AB-Testing.git
   cd AB-Testing
   
2. Install dependencies
  pip install pandas numpy matplotlib seaborn statsmodels

3. Run the script
   python AB-Testing.ipynb
