#Project Overview
This project analyzes customer behavior patterns at Tatte Bakery & Café through observational data collection. Our research focuses on understanding whether weather conditions influence customer preferences for carry-out versus dine-in service.
Research Question
Does sunny weather significantly affect the proportion of customers who choose carry-out service at Tatte?
Hypothesis

H₀ (Null Hypothesis): The proportion of Tatte customers who take carry-out on a sunny day is 50%
H₀: p = 0.50
H₁ (Alternative Hypothesis): The proportion of Tatte customers who take carry-out on a sunny day is not 50%
H₁: p ≠ 0.50

#Test Type: Two-tailed test
Methodology
Data Collection

#Location: Tatte Bakery & Café
Method: Observational study

#Variables Tracked:

Customer service preference (carry-out vs. dine-in)
Weather conditions (sunny day observations)

#Statistical Analysis

Hypothesis testing for population proportion
Two-tailed significance test
Alpha level: 0.05 (standard)

#Repository Structure
├── README.md                          # Project documentation
├── task_6.ipynb                       # Main analysis notebook
├── tattedata.csv                      # Raw observational data
Technologies Used

#Python Google.colab
Libraries:
*scipy.stats.norm - Normal distribution calculations and z-tests
*math - Mathematical functions and calculations
*pandas - Data manipulation and analysis
*numpy - Numerical computations
*matplotlib & seaborn - Data visualization
*plotly - Interactive visualizations
*warnings - Suppressing warning messages for cleaner output

#Statistical Analysis Methods
Main Analysis

*Distribution Analysis - Examining the distribution of carry-out vs. dine-in preferences
*Confidence Interval (CI) - Calculating confidence intervals for proportion estimates
*Visualization - Creating charts and graphs to illustrate customer behavior patterns
*Two-Tailed Z-Test - Primary hypothesis test for population proportion (α = 0.05)

#Appendix Analysis

*Heatmap - Visual representation of data correlations and patterns
*Chi-Square Test - Testing independence between categorical variables
*Histogram - Distribution visualization of customer counts
*t-Test - Additional statistical testing for mean comparisons
