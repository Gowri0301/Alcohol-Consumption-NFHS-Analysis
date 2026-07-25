📊 A Statistical Analysis of Alcohol Consumption Among Adults Across Indian States Using NFHS-4 and NFHS-5 Data

📌 Project Overview

This project presents an end-to-end statistical analysis of alcohol consumption among adults across Indian States and Union Territories using data from the National Family Health Survey (NFHS-4: 2015–16 and NFHS-5: 2019–21).

The objective was to examine changes in alcohol consumption over time, compare trends between women and men, and identify state-wise variations using descriptive and inferential statistical methods implemented in Python.

---

🎯 Objectives

- Compare alcohol consumption among women between NFHS-4 and NFHS-5.
- Compare alcohol consumption among men between NFHS-4 and NFHS-5.
- Assess whether the observed changes are statistically significant.
- Examine the relationship between male and female alcohol consumption.
- Identify states with the largest increases and decreases in alcohol consumption.

---

📂 Dataset

Source: National Family Health Survey (NFHS)

- NFHS-4 (2015–16)
- NFHS-5 (2019–21)

The dataset contains state-wise percentages of adults who consume alcohol.

Variables used:

- State/UT
- Percentage of women who drink alcohol (NFHS-4)
- Percentage of men who drink alcohol (NFHS-4)
- Percentage of women who drink alcohol (NFHS-5)
- Percentage of men who drink alcohol (NFHS-5)

---

🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

---

📈 Statistical Techniques Used

 Data Preparation

- Data Cleaning
- Missing Value Treatment
- Feature Creation

 Descriptive Statistics

- Mean
- Median
- Standard Deviation
- Variance
- Range
- Coefficient of Variation

 Exploratory Data Analysis

- Histograms
- Boxplots
- Scatter Plot
- Correlation Heatmap
- Q-Q Plot

 Statistical Analysis

- Shapiro–Wilk Normality Test
- Skewness
- Kurtosis
- Wilcoxon Signed-Rank Test
- Paired t-test
- Pearson Correlation Analysis
- Linear Regression

---

📊 Key Findings

- Alcohol consumption declined significantly among both women and men between NFHS-4 and NFHS-5.
- Women's alcohol consumption showed a statistically significant decrease based on the Wilcoxon Signed-Rank Test.
- Men's alcohol consumption showed a statistically significant decrease based on the Paired t-test.
- A moderate positive correlation was observed between male and female alcohol consumption across states.
- Linear regression indicated that men's alcohol consumption significantly predicts women's alcohol consumption.
- State-wise analysis identified substantial regional differences in alcohol consumption trends.

---

📌 Major Results

 Women's Alcohol Consumption

- Mean (NFHS-4): **3.28%**
- Mean (NFHS-5): **2.10%**

 Men's Alcohol Consumption

- Mean (NFHS-4): **35.96%**
- Mean (NFHS-5): **29.37%**

 Hypothesis Testing

| Test | Result |
|------|--------|
| Wilcoxon Signed-Rank Test (Women) | Significant (p < 0.001) |
| Paired t-test (Men) | Significant (p < 0.001) |

 Correlation

- Pearson Correlation (Men vs Women, NFHS-5): **r = 0.547**

 Regression

- R² = **0.299**

---

📷 Visualizations

This project includes:

- Histograms
- Boxplots
- Q-Q Plot
- Correlation Heatmap
- Regression Plot
- State-wise Change Analysis

---

📁 Project Structure

```
Alcohol-Consumption-NFHS-Analysis/
│
├── Alcohol_Consumption_Analysis.ipynb
├── NFHS_Alcohol.csv
├── README.md
```

---

🚀 How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells sequentially.

---

📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Hypothesis Testing
- Data Visualization
- Regression Analysis
- Correlation Analysis
- Python Programming
- Statistical Interpretation

---

📄 Conclusion

This project demonstrates the application of statistical techniques to analyze public health survey data. The findings indicate significant reductions in alcohol consumption among adults between NFHS-4 and NFHS-5 while highlighting important state-level variations. The analysis also reveals a moderate positive relationship between male and female alcohol consumption across Indian states.

---

👩‍💻 Author

Gowrilal B

M.Sc. Statistics
 
 - LinkedIn: https://www.linkedin.com/in/gowrilalb
 - GitHub: https://github.com/Gowri0301
