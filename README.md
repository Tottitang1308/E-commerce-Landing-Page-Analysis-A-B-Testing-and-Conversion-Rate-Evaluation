# E-commerce Landing Page Analysis: A/B Testing and Conversion Rate Evaluation

## Project Overview
This repository contains a Jupyter notebook analyzing an A/B test conducted by an e-commerce company to test a new landing page design. The goal was to determine if the new design resulted in a higher conversion rate compared to the existing design.

## Files Included
- **ab_data.csv**: Dataset containing user interaction data including user ID, timestamp, group assignment (control or treatment), landing page type (old or new), and conversion status.
- **Ecommerce_Landing_Page_Analysis.ipynb**: Jupyter notebook containing Python code for data cleaning, statistical analysis (including two-proportion z-test), visualization of conversion rates, and interpretation of results.

## Key Steps
1. **Data Cleaning**: Mismatched entries between group and landing page were identified and removed.
2. **Basic Statistics**: Calculated conversion rates for both control and treatment groups.
3. **Hypothesis Testing**: Performed a two-proportion z-test to assess statistical significance of differences in conversion rates.
4. **Visualization**: Visualized conversion rates, conversion distribution, and session duration by group using seaborn and matplotlib.
5. **Conclusion**: Concluded that there was no statistically significant difference in conversion rates between the old and new landing pages, suggesting further adjustments may be needed before implementation.

## Technologies Used
- Python, pandas, numpy for data manipulation and analysis.
- seaborn, matplotlib for data visualization.
- statsmodels for statistical testing (proportions_ztest).

## Conclusion
The analysis indicates that the new landing page did not outperform the old page in terms of conversion rates. Further iterations or adjustments may be necessary to improve user engagement and conversion on the company's website.
