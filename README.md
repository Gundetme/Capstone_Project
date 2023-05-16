# Capstone_Project
In this project, the aim is to analyze a dataset of customer information from a telecommunications company to identify factors that contribute to customer churn (i.e., when a customer cancels their service)

### Project Title: Analyzing Customer Churn in a Telecommunications Company

**Author:** Ezra OcubaMichael

#### Executive Summary
In the current age of digital communication, the telecommunications industry is fiercely competitive. Businesses within the industry are continuously seeking ways to maintain and grow their customer base. One critical area that companies focus on is understanding and preventing customer churn.

In this project, I aimed to analyze customer churn in a telecommunications company. I also leveraged a dataset that included diverse customer information, such as demographics, account information, and usage patterns. Our goal was to identify the factors that contribute significantly to customer churn.

I utilized various data analysis techniques, including data cleaning, exploratory data analysis, and feature engineering. I also employed machine learning models to develop a predictive model for customer churn.

Through our analysis, I discovered several factors that are strongly associated with churn, including the type of internet service, lack of online backup and device protection, absence of tech support, the contract's nature, the payment method, and the customer's senior citizen status. Customers with fiber optic internet service, those without online backup and device protection, without tech support, on a month-to-month contract, using paperless billing, paying by electronic check, and those who are senior citizens, are found to have a higher likelihood to churn.

Our findings can be employed to inform strategies for customer retention. By focusing on these identified areas, the company can potentially reduce customer churn and increase its customer retention rate. Future work could involve refining the predictive model and exploring other factors that could contribute to customer churn.

Overall, the insights generated from this project can help the telecommunications company understand its customers better and make informed decisions to enhance customer satisfaction and loyalty.

#### Rationale
The aim of this project is to analyze customer churn in a telecommunications company. Understanding why customers leave a company can help inform strategies for improving customer retention.

#### Research Questions
1. What are the most important factors that contribute to customer churn?
2. Are there any patterns or trends in customer churn over time?
3. Can a machine learning model be developed that accurately predicts which customers are most likely to churn?
4. How can these insights be used to improve customer retention and reduce churn rates in the future?

#### Data Sources
The dataset used in this project was obtained from the following link: [Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

#### Methodology
The methodology of this project includes data collection, data cleaning, exploratory data analysis, feature engineering, model selection and training, model evaluation, and model interpretation.

#### Results
After a detailed Exploratory Data Analysis (EDA) on the telecommunications company's customer dataset, several key insights were obtained that can help understand the churn behavior:

Customer Demographics: Senior citizens have a higher churn rate compared to their younger counterparts. This could possibly be due to the lack of familiarity or comfort with the technology or the service.
Internet Service: Customers with fiber optic internet service show a significantly higher churn rate. The reasons could be many, including the price or quality of the service.
Additional Services: Customers without online backup, device protection, and tech support tend to churn more. These services could be perceived as value-added services, and lack of them might lead to dissatisfaction among customers.
Contract and Billing: Customers on a month-to-month contract, those with paperless billing, and those who pay by electronic check show a higher propensity to churn. This might indicate that customers who are not locked into a long-term contract and those who prefer digital transactions are more likely to explore other options available in the market.
These findings provide a valuable understanding of customer churn behavior. By addressing these factors, the company may be able to significantly reduce churn and increase customer satisfaction and loyalty. However, these are preliminary insights, and further analysis is needed to make accurate predictions and develop effective retention strategies.

#### Next Steps
Next Steps and Improvements

The findings from the EDA stage provide a strong foundation for further analysis. Here are some potential next steps and improvements that could be made:

Develop Predictive Models: Use the insights from the EDA to develop predictive models. This could include logistic regression, decision trees, random forests, gradient boosting, or neural networks. The goal would be to predict which customers are most likely to churn based on their characteristics and behaviors.
Feature Engineering: Experiment with creating new features that might be predictive of churn. This could include interaction terms, polynomial features, or other transformations of the existing data.
Hyperparameter Tuning: Once a model is selected, optimize it using hyperparameter tuning to increase its predictive power.
Model Evaluation: Evaluate the performance of the model using appropriate metrics such as precision, recall, F1-score, and ROC-AUC curve.
Implementation of Recommendations: Based on the findings, develop and implement strategies aimed at reducing customer churn. For instance, offer discounts or special packages to senior citizens, improve the quality of fiber optic internet service, provide more value-added services such as online backup and device protection, or provide more flexible contract options.
Periodic Re-evaluation: Churn analysis should be an ongoing process. Periodically re-evaluate the model's performance and update it with new data to ensure its effectiveness in predicting churn.
Customer Feedback: Incorporate customer feedback mechanisms to understand the reasons behind their churn. This could provide additional qualitative insights that might not be captured in the data.
These steps will not only improve the churn prediction but also help in creating more efficient strategies for customer retention.

#### Outline of Project

- [Data Collection and Data Inspection](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2020.1%20Initial%20Report%20and%20Exploratory%20Data%20Analysis%20(EDA).ipynb)
- [Data Cleaning and Pre-processing](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2020.1%20Initial%20Report%20and%20Exploratory%20Data%20Analysis%20(EDA).ipynb#Data Cleaning and Pre-processing)
- [Exploratory Data Analysis (EDA)](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2020.1%20Initial%20Report%20and%20Exploratory%20Data%20Analysis%20(EDA).ipynb#Exploratory Data Analysis (EDA))
- [Preparing Data for Machine Learning](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2020.1%20Initial%20Report%20and%20Exploratory%20Data%20Analysis%20(EDA).ipynb#Preparing Data for Machine Learning)

##### Contact and Further Information
(Provide your contact information or any other relevant information here.)
