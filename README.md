# Churn Analysis

## Table of Contents
- [Objective](#objective)
- [Background](#story)
- [Methodology](#methodology)
- [Recommendations](#recommendations)

## Objective
The objective of this project is to analyze customer churn using various statistical and machine learning techniques to uncover key drivers of churn. This analysis aims to provide actionable insights for developing customer retention strategies.

## Story
Company X is facing a significant issue with customer churn. Many customers are leaving and not returning, resulting in revenue loss and negatively impacting the company's growth.

The customer churn rate serves as a key performance indicator (KPI) for understanding this problem. The data reveals that 26.54% of customers have already churned, posing a serious risk to future revenue and business expansion.

To address this challenge, Company X needs to reduce the churn rate as much as possible. To develop an effective strategy, the company has gathered detailed data on customer demographics, service usage, contract types, billing preferences, and other usage patterns.

### Key Business Questions
1. **Understanding Customer Churn**: What are the key characteristics of customers who are leaving the company? How do factors like demographics, service preferences, contract types, billing methods, and usage contribute to churn?
2. **Retention Strategy**: What actionable insights can guide retention strategies? How can changes to service offerings, contract structures, and customer engagement efforts reduce churn rates? How can a churn prediction model identify high-risk customers for targeted interventions?

## Presentation
The detailed findings and insights from the churn analysis can be found in the [project presentation](https://docs.google.com/presentation/d/1sRRFKFrWIMNslA0oV5otsbJ210edorp8600_DCXuA-0/edit?usp=sharing).

## Methodology
1. **Descriptive Analysis**: Conducted exploratory data analysis (EDA) to understand the distribution of customer attributes, identify patterns, and visualize the relationship between various features and churn.
2. **Correlation Analysis**: Investigated the relationships between different variables to identify key factors that may contribute to customer churn.
3. **K-Means Clustering**: Applied clustering techniques to segment customers into groups based on their characteristics and behavior. This helped in identifying patterns related to churn in different customer segments.
4. **Predictive Analysis**: Implemented machine learning models such as logistic regression, decision trees, and random forests to predict churn based on customer attributes.
5. **Evaluation**: Evaluated the model's performance using metrics such as accuracy, precision, recall, and AUC-ROC to assess the effectiveness of the churn prediction.

## Recommendations
### Priority 1
**Focus on Cluster 1**: This cluster, characterized by short tenure and high monthly charges, represents a significant churn risk. Implement targeted strategies such as:
- **Discounts or Loyalty Programs**: Provide added value to retain these customers.
- **Contract Incentives**: Offer benefits for longer-term contracts to transition customers away from month-to-month plans.
- **Address Fiber Optic Users**: Since Cluster 1 is dominated by fiber optic users, investigate potential service issues or customer dissatisfaction. Address these issues through service quality improvements or support initiatives.

### Priority 2
**Use Predictive Insights** to identify medium-risk customers (1,304 customers). These customers are on the fence and may be swayed with the right engagement strategies:
- **Personalized Communication**: Reach out with tailored offers, product tutorials, or check-ins to enhance their experience.
- **Enhance Service Adoption**: Encourage the use of value-added services (e.g., online security, tech support) that correlate with reduced churn.

**Restructure Contract Offerings**: Since month-to-month contracts are a major predictor of churn, consider:
- **Discounts for Annual Contracts**: Offer additional benefits like free add-on services for long-term subscriptions.
- **Flexible Upgrade Paths**: Make it easier for customers to shift from month-to-month to yearly contracts.

**Improve High-Risk Services**: Services such as fiber optic internet, online security, and streaming services are correlated with churn risk. Focus on improving the quality and reliability of these services while actively promoting their benefits to reduce churn rates.


## Code
The code for this project can be found in the attached HTML file (`churn_analysis_by_fani.html`). It includes all the steps from data processing to model building and evaluation.

## Usage
1. **Prerequisites**: Ensure you have Python installed along with necessary libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`).
2. **Data Preparation**: Replace the dataset path in the code with the location of your customer churn dataset.
3. **Run Analysis**: Use the provided code to perform data preprocessing, clustering, correlation analysis, and predictive modeling.
4. **Results**: View the insights and visualizations generated in the analysis to understand the drivers of churn and develop retention strategies.

## Contact
For questions or collaboration, please reach out via [email](dwiluciaarfani35@gmail.com).
