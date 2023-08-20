
<div style="text-align: center;">
  <img src="https://github.com/reginacrabbe/Indian-startup-ecosystem-LP1-project/assets/137375344/650a71ad-0bbb-4aea-9bf3-ca5f93175dc1" width="300" height="300" alt="Logo">
</div>

# Churn-Analysis-and-Customer-Retention-LP2-Project
This repository contains a comprehensive churn analysis project for a telecommunication company. 

# Title
### CHURN ANALYSIS AND CUSTOMER RETENTION STRATEGIES FOR A TELECOMMUNICATION COMPANY

# Table of Content
- Project Description
- Definition of Churn and its Significance
- Objective of the Project
- Project Approach
- Data Description
- Project Summary
    - Business Understanding
    - Data Understanding
    - Data Preprocessing
    - Exploratory Data Analysis
    - Hypothesis Testing
    - Feature Engineering
    - Modeling and Evaluation
    - Handling Imbalanced Data
    - Selection of Best Model
    - Future Prediction on Test Set
- Technologies Used
- Conclusion
- Recommendations
- License
- Social Media
- Acknowledgement
- Authors
- Contact 

## Project Description
In today's fast-paced and competitive business landscape, the telecommunication industry stands as a prominent example of sectors that experience intense rivalry. Among the numerous challenges that telecommunication companies encounter, customer churn emerges as a crucial concern that directly impacts revenue, profitability, and market standing. To address the complexity of customer churn, this project focuses on analyzing churn patterns, understanding key factors influencing churn, and building predictive models to forecast customer churn.

## Definition of Churn and its Significance
Churn, also referred to as attrition or customer turnover, holds immense significance in the telecommunication industry. It is a pivotal metric that quantifies the rate at which customers cease their subscription to services. Identifying and mitigating churn can lead to substantial gains, as reducing churn even by a small percentage can result in significant improvements in profitability and customer loyalty.

## Objective of the Project
The primary objective of this churn analysis project is to empower telecommunication companies with insights and strategies that can curtail customer churn rates and optimize customer retention efforts. By leveraging advanced data analysis techniques and predictive modeling, the project aims to unravel hidden patterns and key drivers behind customer churn. Armed with this knowledge, the project seeks to devise actionable recommendations for designing targeted interventions, personalized offerings, and customer-centric initiatives that effectively reduce churn rates. 


## Project Approach
The project followed the structured approach of the CRIPS-DM framework and ensured that all relevant steps are taken to achieve meaningful results.  The CRISP-DM (Cross-Industry Standard Process for Data Mining) framework is a widely used methodology for guiding data mining and data analysis projects. The project structure includes the following steps:

- Introduction and Objective
- Business Understanding
- Data Understanding
- Data Preprocessing
- Exploratory Data Analysis
- Hypothesis Testing
- Feature Engineering
- Modeling and Evaluation
- Handling Imbalanced Data
- Selection of Best Model
- Future Prediction on Test Set
- Conclusion and Recommendations
- References

### Data Description
1.	Gender: Whether the customer is a male or a female
2.	SeniorCitizen: Whether a customer is a senior citizen or not
3.	Partner: Whether the customer has a partner or not (Yes, No)
4.	Dependents: Whether the customer has dependents or not (Yes, No)
5.	Tenure: Number of months the customer has stayed with the company
6.	Phone Service: Whether the customer has a phone service or not (Yes, No)
7.	MultipleLines: Whether the customer has multiple lines or not
8.	InternetService: Customer's internet service provider (DSL, Fiber Optic, No)
9.	OnlineSecurity: Whether the customer has online security or not (Yes, No, No Internet)
10.	OnlineBackup: Whether the customer has online backup or not (Yes, No, No Internet)
11.	DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
12.	TechSupport: Whether the customer has tech support or not (Yes, No, No internet)
13.	StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
14.	StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No Internet service)
15.	Contract: The contract term of the customer (Month-to-Month, One year, Two year)
16.	PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
17.	Payment Method: The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))
18.	MonthlyCharges: The amount charged to the customer monthly
19.	TotalCharges: The total amount charged to the customer
20.	Churn: Whether the customer churned or not (Yes or No)

 
## Project Summary
### Data Preprocessing
Data preprocessing includes steps such as handling missing values, transforming categorical variables, and converting data types. Imputation strategies were used to address missing values, and categorical variables were encoded for modeling purposes.

### Exploratory Data Analysis
EDA involves visualizing data distributions, exploring relationships between variables, and identifying potential patterns. Key insights regarding customer churn, correlations between variables, and gender-based analysis were derived from EDA.

### Hypothesis Testing
Hypothesis testing is performed to evaluate the impact of variables on churn. Significance tests, such as chi-square were used to assess relationships between categorical variables and churn and logistic regression was also used to assess the impact of the numerical variables on the the target variable churn.

### Feature Engineering
Feature engineering involves creating new variables, encoding categorical variables, and selecting relevant features for modeling. Correlation analysis and domain knowledge guided feature selection.

### Modeling and Evaluation
Multiple machine learning algorithms, including Logistic Regression, Decision Trees, Random Forest, XGBoost, and Support Vector Machines, are trained and evaluated using precision, recall, F1-score, and accuracy metrics.

### Handling Imbalanced Data
To address class imbalance, techniques such as class weighting and SMOTE (Synthetic Minority Over-sampling Technique) were applied to improve model performance on the minority class (churned customers).

### Selection of Best Model
The best model is selected based on a combination of precision, recall, and F2-score. The chosen model was further evaluated using k-Fold cross-validation to assess its generalization performance. Hyperparameter tuning was done to help find the right balance between bias and variance, resulting in a model that generalizes well to new data.

### Future Prediction on Test Set
The best model is used to predict churn on the test set (unseen data). Predictions are saved in a results DataFrame, which is concatenated with the original test set for further analysis.

### Conclusion and Recommendations
The project concludes with actionable insights and recommendations to help telecommunication companies devise strategies for reducing churn rates, improving customer retention, and optimizing business outcomes.

### References
This section includes a list of sources, research papers and articles used in the project for reference and credibility.

|Code|Name of Project|Published Article|Deployed App|
|:---|:-------------:|:---------------:|-----------:|
|LPI |Indian Startup |https://medium.com/@rndcrabbe/exploring-the-dynamic-realm-of-indias-startup-ecosystem-a-data-analysis-project-e7f54216702e|Medium|

## Technologies Used
- Programming Language:
    - Python: Python is a widely used programming language for data analysis and machine learning. 
- Data Manipulation and Analysis Libraries:
    - Pandas: Pandas is a powerful library for data manipulation and analysis. 
    - NumPy: NumPy is used for numerical operations and mathematical computations in Python.
- Data Visualization Libraries:
    - Matplotlib: Matplotlib is a popular plotting library for creating static, interactive, and animated visualizations in Python.
    - Seaborn: Seaborn is built on top of Matplotlib and provides a higher-level interface for creating attractive and informative statistical graphics.
    - Plotly: Plotly is used for interactive and dynamic visualizations. 
- Machine Learning Libraries:
    - Scikit-learn: Scikit-learn is a machine learning library that provides simple and efficient tools for data mining and data analysis. It includes various algorithms for classification, regression, clustering, and more.
    - XGBoost: XGBoost is a popular gradient boosting library that often performs well in predictive modeling tasks.
    - Random Forest: Random Forest is an ensemble learning method used for classification and regression tasks.
    - Support Vector Machines (SVM): SVM is a powerful algorithm used for both classification and regression tasks.
    - StatsModels: StatsModels is used for estimating and interpreting statistical models.
- Jupyter Notebook:
    - Jupyter Notebook is an interactive document that allow you to combine code, visualizations, and explanations in a single environment. 
- Version Control:
    - Git: Git is a version control system that allows you to track changes in your code and collaborate with others efficiently.
    - GitHub: Platforms like GitHub provide repositories for hosting your code, collaborating with others, and managing project versions.
- Text Editor / Integrated Development Environments (IDEs):
    - Visual Studio Code: VS Code is a popular code editor that offers extensions for Python, data science, and version control.
- Libraries for Imbalanced Data:
    - imbalanced-learn: This library provides tools for dealing with imbalanced datasets. It includes techniques like SMOTE, ADASYN, and more to balance class distributions.
-  Learning Model Evaluation:
    - Metrics from Scikit-learn: Scikit-learn provides various metrics like accuracy, precision, recall, F1-score, and more for evaluating the performance of your machine learning models.
- Communication and Collaboration:
    - Documentation Tools: Markdown and tools like Readme files are essential for documenting your project and explaining your findings.
    - Communication Tool: Microsoft Teams was used to collaborate with team members.
- Reporting and Visualization Tool: Power BI

### Conclusion

In this Churn Analysis project, we conducted a comprehensive analysis of customer churn within a telecommunications company. Through data exploration, visualization, and statistical analysis, we gained valuable insights into the factors influencing churn and identified key patterns. The univariate analysis revealed the distribution of churn among different categories, while the bivariate and multivariate analysis helped us understand the relationships between various features and churn. The correlation analysis shed light on the connections between tenure, monthly charges, and total charges, highlighting potential multicollinearity.

Machine learning played a significant role in this project. By employing a predictive model, we were able to anticipate churn with a certain degree of accuracy. This model could be a valuable asset for customer retention strategies, allowing to proactively address the needs of customers who are more likely to churn.

Our findings provide a foundation for informed decision-making. By understanding the factors driving churn, the company can focus their efforts on improving customer experience, optimizing pricing strategies, and offering targeted promotions.

### Recommendations
Based on the insights gathered from our analysis, here are some recommendations:

- Tailored Customer Engagement: Utilize the predictive model to identify customers at higher risk of churning. Design personalized engagement strategies to address their concerns and needs effectively.
- Feature Importance: Concentrate on enhancing the quality of the most influential features contributing to churn.
- Competitive Pricing: Analyze the relationship between monthly charges, tenure, and total charges to ensure the pricing plans remain competitive and aligned with customer expectations.
- Promote Family-Centric Services: Develop service packages that emphasize benefits for customers with dependents. Highlight family-oriented services and bundle offerings to cater to this customer segment's needs.
- Paperless Billing Promotion: Encourage customers to opt for paperless billing and explore payment options beyond electronic checks to reduce churn among customers who prefer automated billing.
- Enhance Senior Citizen Engagement: Engage senior citizens through communication channels they prefer and offer services tailored to their unique requirements, ensuring their loyalty and retention.
- Contract Length: Consider offering incentives for longer-term contracts to increase customer retention.
- Regular Feedback Mechanism: Establish a mechanism to gather regular feedback from customers who have churned. This can provide actionable insights for improving our services.
- Monitoring and Refinement: Continuously monitor the performance of the churn prediction model. Refine the model periodically as new data becomes available to improve its accuracy.
- Collaboration: Share the insights with relevant teams such as customer service, marketing, and product development. Collaborate on implementing strategies that target churn reduction.

By implementing these recommendations, we aim to reduce churn, increase customer satisfaction, and enhance the overall success of our telecommunications business.


### License
MIT Lincense

### Social Media
Medium

### Team Logo
<img src="https://github.com/reginacrabbe/Indian-startup-ecosystem-LP1-project/assets/137375344/650a71ad-0bbb-4aea-9bf3-ca5f93175dc1" width="100" height="100">

### Acknowledgement
Much appreciation to the entire Azubi Team for your continuous support and kudos to Cape Cod Team for their hard work and dedication.

### Authors
- Regina Naa Dedei Crabbe
- Kodwo Amissah-Mensah
- Alvin Momoh
- Alliyah
- Leon

### Contact
Regina Naa Dedei Crabbe

rndcrabbe@gmail.com

