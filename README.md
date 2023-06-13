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

Comparing the performance of the four models (Random Forest Classifier, SVM, Logistic Regression, Neural Network) in terms of their accuracy, precision, recall, F1-score, and ROC-AUC, we can observe the following:

| Model                  | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------------------------|----------|-----------|--------|----------|---------|
| Random Forest          | 0.794    | 0.610     | 0.497  | 0.548    | 0.695   |
| SVM                    | 0.794    | 0.604     | 0.511  | 0.554    | 0.700   |
| Logistic Regression    | 0.793    | 0.596     | 0.540  | 0.566    | 0.709   |
| Neural Network         | 0.779    | 0.584     | 0.406  | 0.479    | 0.655   |


**Based on these metrics, we can make the following observations:**

Random Forest Classifier, SVM, and Logistic Regression perform relatively better than the Neural Network model in terms of accuracy, precision, recall, and F1-score.
Logistic Regression has the highest ROC-AUC score, indicating better discrimination power between churn and non-churn cases.
Random Forest Classifier and SVM show similar performance across most metrics.
The Neural Network model lags behind the other models in terms of recall, indicating it struggles to correctly identify churn cases.
Considering the overall performance, Logistic Regression emerges as the top-performing model, followed closely by Random Forest Classifier and SVM. The Neural Network model, while achieving a reasonable accuracy, struggles in capturing churn cases effectively.

However, it's important to note that model performance can vary depending on the dataset, preprocessing techniques, hyperparameter tuning, and feature engineering. It's recommended to further explore and fine-tune the models based on specific requirements and objectives to achieve the best possible performance.

**Based on the evaluation of multiple models for predicting customer churn, the following conclusions can be drawn:**

* **Random Forest Classifier:** The random forest classifier achieved an accuracy of 79.4% with a precision of 61.0%, recall of 49.7%, F1-score of 54.8%, and ROC-AUC of 69.5%. It showed decent overall performance in predicting churn.
* **SVM:** The support vector machine (SVM) model achieved an accuracy of 79.4% with a precision of 60.4%, recall of 51.1%, F1-score of 55.4%, and ROC-AUC of 70.0%. It performed similarly to the random forest classifier, indicating its effectiveness in predicting churn.

* **Logistic Regression:** The logistic regression model achieved an accuracy of 79.3% with a precision of 59.6%, recall of 54.0%, F1-score of 56.6%, and ROC-AUC of 70.9%. It showed comparable performance to the other models, highlighting its suitability for churn prediction.
* **Neural Network:** The neural network model achieved an accuracy of 77.9% with a precision of 58.4%, recall of 40.6%, F1-score of 47.9%, and ROC-AUC of 65.5%. It exhibited slightly lower performance compared to the other models, suggesting room for improvement.

Overall, all models showed reasonably good accuracy in predicting customer churn. The random forest classifier, SVM, and logistic regression demonstrated similar performance, outperforming the neural network model in most metrics. Depending on the specific requirements and constraints of the problem, any of these models can be considered for churn prediction. Further experimentation and fine-tuning of the models may lead to even better results.

#### Conclusion

In this project, I aimed to analyze and predict customer churn for a telecommunications company. I started by collecting and inspecting the dataset, followed by data cleaning and preprocessing. Exploratory data analysis (EDA) allowed us to gain insights into the relationships between various features and churn.

Key findings from the EDA revealed that customers with fiber optic internet service, no online backup, no device protection, no tech support, month-to-month contracts, paperless billing, and who pay by electronic check are more likely to churn. These factors can be further investigated and targeted for customer retention strategies.

I performed feature engineering to transform categorical variables using one-hot encoding and label encoding techniques. Subsequently, I developed predictive models including Random Forest Classifier, SVM, Logistic Regression, and Neural Network. I evaluated the performance of these models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Based on the evaluation, all models demonstrated reasonable accuracy in predicting customer churn. The Random Forest Classifier, SVM, and Logistic Regression models exhibited similar performance, outperforming the Neural Network model. These models can be further optimized and fine-tuned to improve their predictive power.

The insights gained from this project can be leveraged to develop strategies for customer retention and reduce churn rates. By identifying the key factors contributing to churn, the telecommunications company can implement targeted interventions, such as improving customer service, offering incentives, and providing better support for specific services. This can ultimately lead to increased customer satisfaction, loyalty, and business growth.

In conclusion, this project highlights the importance of data analysis and predictive modeling in understanding and addressing customer churn. The developed models provide a foundation for ongoing analysis and improvement in customer retention efforts, ultimately benefiting the telecommunications company in maintaining a loyal customer base.

#### Next Steps
Next Steps and Improvements
There are several potential next steps and improvements that can be considered for this project:

* **Feature selection and engineering:** Further analyze the importance of individual features and consider dropping or transforming less relevant ones. Additionally, explore the creation of new features that could provide more predictive power.
* **Model tuning and optimization**: Fine-tune the hyperparameters of the models to improve their performance. This can be done through techniques such as grid search, random search, or Bayesian optimization.
* **Ensemble methods:** Explore ensemble methods such as stacking, bagging, or boosting to combine the predictions of multiple models and potentially improve overall performance.
* **Handling class imbalance:** Address the class imbalance issue in the dataset, as the number of churned customers is typically lower than non-churned customers. Techniques like oversampling, undersampling, or SMOTE (Synthetic Minority Over-sampling Technique) can be used to balance the classes and potentially improve the models' performance.
* **Time-based analysis:** Conduct a time-based analysis to identify any patterns or trends in customer churn over time. This can help understand seasonality, changes in customer behavior, or the impact of specific events or promotions.
* **Customer segmentation:** Apply customer segmentation techniques to divide the customer base into distinct groups based on their characteristics and behaviors. This can provide deeper insights into the different factors influencing churn within each segment and allow for targeted retention strategies.
* **External data integration:** Explore the integration of external data sources, such as demographic or socio-economic data, that could provide additional insights into customer churn.
* **Deploy and monitor the model:** Once a satisfactory model is developed, deploy it in a production environment and continuously monitor its performance. This allows for timely identification of any degradation in model performance and the opportunity to retrain or recalibrate the model as needed.
Cost-benefit analysis: Perform a cost-benefit analysis to quantify the potential impact of implementing the strategies derived from the model. This analysis can help prioritize retention initiatives based on their expected return on investment.
* **Continuous improvement:** This project should be viewed as an iterative process. Continuously analyze customer churn, collect feedback, and refine the models and strategies based on new data and insights.
By considering these next steps, the project can continue to evolve and provide valuable insights and strategies for improving customer retention and reducing churn rates.

#### Outline of Project

- [Data Collection and Data Inspection](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb)
- [Data Cleaning and Pre-processing](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb#Data%20Cleaning%20and%20Pre-processing)
- [Exploratory Data Analysis (EDA)](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb#Exploratory%20Data%20Analysis%20(EDA))
- [Machine Learning models](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb#Random%20forest%20classifier)
- [Comparision:](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb#Comparision:)
- [Conclusion](https://github.com/Gundetme/Capstone_Project/blob/main/Capstone%20Project%2024.1:%20Final%20Report.ipynb#Conclusion)


##### Contact and Further Information
(Provide your contact information or any other relevant information here.)
