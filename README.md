# Cross-Country Socioeconomic Analysis Using Random Sampling

## Project Overview
This project analyzes socioeconomic and demographic indicators for a **random sample of 37 countries** selected from all countries worldwide using Microsoft Excel’s `RAND()` function. The goal was to explore global patterns, relationships, and inequalities using **descriptive statistics, inferential statistics, correlation analysis, and linear regression**.

The analysis focuses on how economic, educational, and social factors relate to inequality and health outcomes across countries.

---

## Data Description
The dataset includes the following variables:

- **GDP per capita**
- **Unemployment rate**
- **Gini index** (income inequality)
- **Female literacy rate**
- **GDP spent on education**
- **Infant mortality rate**
- **Predominant religion**

All data were compiled and analyzed in Microsoft Excel.

---

## Methodology

### Random Sampling
- A simple random sample of **37 countries** was generated using Excel’s `RAND()` function to avoid selection bias and ensure representativeness.

### Descriptive Statistics
- Measures of central tendency (mean, median, mode)
- Frequency distributions and histograms for:
  - GDP per capita
  - Gini index
- Pie chart of predominant religions across sampled countries

### Inferential Statistics
- **95% confidence intervals** were constructed for:
  - Mean GDP per capita
  - Mean GDP spent on education
- **Hypothesis testing** on the proportion of predominantly Christian countries using a one-sample z-test for proportions

### Correlation and Regression Analysis
- Correlation analysis between:
  - Female literacy rate
  - Infant mortality rate
- Simple linear regression modeling infant mortality as a function of female literacy rate

---

## Key Findings

### Economic and Inequality Patterns
- GDP per capita exhibited a **right-skewed distribution**, with a small number of very high-income countries and a majority clustered at lower income levels.
- Gini index values varied substantially across countries, indicating **significant differences in income inequality** worldwide.

### Education and Health Outcomes
- A **strong negative relationship** was found between **female literacy rate** and **infant mortality rate**.
- The regression model produced:
  - **Multiple R ≈ 0.89**
  - **R² ≈ 0.79**
- This indicates that approximately **79% of the variation in infant mortality rates** can be explained by differences in female literacy rates alone.

### Religion Distribution
- The sampled countries displayed religious diversity, with **Muslim, Sunni, Protestant, and Christian** majorities represented.
- A hypothesis test on the proportion of Christian countries **did not provide sufficient evidence** to conclude that Christians make up more than 50% of the sample.

---

## Interpretation
The results highlight the critical role of **female education** in improving public health outcomes. Countries with higher female literacy rates consistently showed **lower infant mortality**, reinforcing findings from global development research. Economic inequality and income levels also varied widely, emphasizing structural disparities between countries.

---

## Tools Used
- **Microsoft Excel**
  - RAND function for random sampling
  - Descriptive and inferential statistics
  - Charts and visualizations
  - Correlation and regression analysis

---

## Files
- `Cross-Country-Socioeconomic-Analysis.xlsx` — Full dataset, statistical analysis, visualizations, and regression output

---

## Author
**Aaron Sanders**

