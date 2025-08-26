# Employee_Retention_Prediction
Built and optimized a logistic regression model to predict employee retention using demographic, performance, and satisfaction data. Applied RFE for feature selection, evaluated with accuracy and ROC-AUC, and identified key retention drivers like job satisfaction and work-life balance
🎯 Business Objective
The primary business objective is to proactively identify employees who are likely to stay with the company and understand the factors that contribute to their loyalty. By analyzing key drivers of retention, the company can strengthen its workforce and create a more supportive work environment.

🛠️ Methodology
The analysis follows a structured approach, as outlined in the Jupyter Notebook:
Data Understanding: Initial exploration of the dataset, including checking dimensions, data types, and basic statistics.
Data Cleaning: Handled missing values, and performed categorical encoding and numerical scaling.
Train-Validation Split: The data was split into a 70% training set and a 30% validation set to prevent overfitting.
Exploratory Data Analysis (EDA): Analyzed the distribution of variables, checked for outliers, and examined correlations between features.
Feature Engineering: Transformed variables to improve model performance.
Model Building: Developed a Logistic Regression model to predict the likelihood of employee retention.
Prediction and Model Evaluation: Assessed the model's performance using metrics like accuracy, precision, and recall.

🔑 Key Findings
The model's analysis identified several key drivers of employee retention:
Job satisfaction: Employees with high satisfaction had the lowest attrition rates.
Performance Rating: High-performing employees were more likely to be retained.
Work-Life Balance: This factor, along with number of promotions, overtime, and performance rating, significantly influences whether employees will stay.
Age and Years at Company: There is a moderate positive correlation between age, years at the company, and company tenure, which is a normal relationship.
The model's ROC curve is well above the diagonal line, indicating that it performs significantly better than random at distinguishing between employees who are likely to stay versus those at risk of leaving.
