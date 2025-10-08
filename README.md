# Customer Churn Analysis
This repository contains an analysis of banking customer churn data. The dataset provides insights into customer behavior and characteristics, aiming to identify factors contributing to churn and to inform data-driven business decisions.

## Dataset

### Description
The dataset includes customer information from a banking institution. Each record represents a customer, with various attributes describing their demographics, account details, and activity. The target variable, `Exited`, indicates whether a customer has churned (1) or not (0).

### Columns
The dataset contains the following columns:
- **RowNumber**: Serial number for each record.
- **CustomerId**: Unique identifier for each customer.
- **Surname**: Customer's surname.
- **CreditScore**: Customer's credit score.
- **Geography**: Country of residence.
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Tenure**: Number of years the customer has been with the bank.
- **Balance**: Customer's account balance.
- **NumOfProducts**: Number of bank products used by the customer.
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary**: Estimated annual salary of the customer.
- **Exited**: Target variable indicating churn (1 = Yes, 0 = No).
- **Complain**: Whether the customer has raised complaints (1 = Yes, 0 = No).
- **Satisfaction Score**: Customer satisfaction score.
- **Card Type**: Type of credit card owned by the customer.
- **Point Earned**: Points earned through loyalty programs.

## Analysis Overview
The project explores the dataset to answer key business questions such as:
1. Which customer demographics are most likely to churn?
2. How does credit score correlate with churn rates?
3. What is the relationship between customer tenure and churn?
4. Are active members less likely to churn than inactive members?
5. How does customer satisfaction impact churn rates?

## 🔍 Insights from the Analysis
**1. Customer Demographics and Churn**
- Gender: Female customers (56%) churn slightly more than males (44%).
- Age Group: The 40–49 and 50–64 age ranges show the highest churn, while younger customers (18–29) are the least likely to leave.
- Geography: Germany records the highest churn rate, followed by France, while Spain has the lowest.

➡️ Conclusion: Middle-aged female customers in Germany are the most likely to churn.

**2. Credit Score and Churn**
- Customers with lower credit scores (300–669) churn significantly more often than those with high scores (740+).
- The "Fair" credit category (580–669) has the highest number of churned customers (685).

➡️ Conclusion: There is a negative correlation between credit score and churn rate — lower scores imply higher risk.

**3. Tenure and Churn**
- Customers with shorter tenures (<5 years) have higher churn rates.
- Those with longer tenures (8–10 years) are more likely to stay loyal.

➡️ Conclusion: Customer loyalty increases with tenure, highlighting the importance of early-stage engagement.

**4. Active vs. Inactive Members**
- Inactive members are significantly more likely to churn.
  *	Inactive Females: 725 churned
  *	Active Females: 414 churned
  *	Inactive Males: 578 churned
  *	Active Males: 321 churned

➡️ Conclusion: Engagement reduces churn — active members demonstrate stronger retention.

**5. Satisfaction and Churn**
- The average satisfaction score among churned customers is 3.0 / 5.
- Moderate satisfaction indicates that customer experience improvements could reduce churn.

➡️ Conclusion: Increasing satisfaction and proactive feedback management can meaningfully improve retention.

## 🧠 Recommendations
1.	Customer Segmentation & Retention Programs:
  *	Focus retention initiatives on middle-aged female customers with low-to-medium credit scores in Germany.
  *	Offer tailored financial products and relationship incentives.
2.	Customer Engagement Strategies:
  * Encourage inactive customers to use services through loyalty programs, product education, and targeted offers.
3.	Credit Improvement Programs:
  *	Provide credit counseling or tools to help customers improve credit health, reducing churn risk.
4.	Early Tenure Retention:
  *	Implement strong onboarding and follow-up systems for customers in their first few years.
5.	Satisfaction Monitoring:
  *	Conduct regular surveys and use predictive models to detect early signs of dissatisfaction.


## Tools Used
- **Microsoft Excel**: For initial data exploration and analysis.
- **Power BI**: For visualizing trends, patterns, and insights.

## Future Work

