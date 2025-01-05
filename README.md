# Telecom Customer Churn Analysis

## Overview
This project analyzes customer churn within the telecom industry, aiming to uncover the key factors driving churn and offer actionable strategies to enhance customer retention. By examining demographic, service usage, and account data, the analysis focuses on contract types, payment methods, tenure, and other significant attributes.

## Objectives
- Identify the factors most strongly associated with customer churn.
- Provide actionable recommendations to reduce churn and improve retention.

## Key Insights
1. **Contract Types**
   - Churn is highest for *month-to-month contracts* (42%) compared to *yearly (11%)* and *two-year contracts (3%)*.
   - **Recommendation:** Incentivize long-term contracts with discounts or loyalty programs.

2. **Payment Methods**
   - Customers using *electronic checks* have a churn rate of 45%, compared to 15-18% for other methods (e.g., credit cards, bank transfers).
   - **Recommendation:** Encourage secure payment methods like credit cards or bank transfers.

3. **Tenure**
   - Churn is highest (50%) for customers with less than one year of tenure and drops to 15% after three years.
   - **Recommendation:** Focus on customer engagement during the first year to boost retention.

4. **Internet Service Type**
   - Churn is higher for *fiber optic services* (30%) compared to *DSL services* (20%).
   - **Recommendation:** Address customer concerns about fiber optic services, such as speed and reliability.

5. **Senior Citizens**
   - Senior customers (65+) experience a higher churn rate (41%) compared to non-senior customers (26%).
   - **Recommendation:** Develop senior-friendly programs or personalized support to improve satisfaction.

## Visualizations
- **Bar Charts and Line Graphs:**
  - Visualize churn rates by contract type, payment method, tenure, and internet service type.
- **Percentage Distributions:**
  - Highlight disparities in churn rates across payment methods, contract types, and tenure.

## Recommendations
1. **Promote Long-Term Contracts:** Offer discounts or loyalty rewards for customers switching to yearly or two-year plans.
2. **Enhance Payment Method Security:** Educate customers about the advantages of secure payment options and offer incentives to switch.
3. **Engage Early:** Focus on personalized offers and excellent customer service during the first year.
4. **Senior Citizen Programs:** Provide tailored assistance or discounts for senior customers to improve satisfaction.
5. **Improve Fiber Optic Services:** Conduct surveys and address feedback to enhance speed and reliability.

## Project Structure
- **`data/`**: Raw customer churn dataset.
- **`notebooks/`**: Jupyter notebooks for data preprocessing, analysis, and visualization.
- **`charts/`**: Exported visualizations of churn insights.
- **`reports/`**: Summaries and key findings from the analysis.
- **`README.md`**: Overview and instructions for using the project.

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/telecom-customer-churn.git
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Analysis Notebook:**
   ```bash
   jupyter notebook notebooks/customer_churn_analysis.ipynb
   ```
4. **Explore Visualizations:** Check the `charts/` folder for detailed insights.

## Future Enhancements
- Build machine learning models to predict churn and identify high-risk customers.
- Analyze additional demographic and behavioral data for deeper insights.
- Design and test targeted retention strategies based on customer segmentation.

## License
This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this analysis as needed.

