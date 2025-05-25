# Machine_learning_EasyVisa
Python Project ( EasyVisa – Tourist Visa &amp; Education Consultant )

**Project Title:**

Visa Application Status Prediction Using Ensemble Machine Learning Techniques.

**Objective:**

To develop a predictive classification model for the Office of Foreign Labor Certification (OFLC) that assists in automating visa approval recommendations, using machine learning. The goal is to prioritize accurate pre-screening, minimize human review efforts, and improve the efficiency of visa processing.

**Approach:**

**1 Data Understanding & Preprocessing**

•	Dataset includes applicant and employer information (e.g., education, wage, job experience, continent, full-time flag).

**•	Preprocessing steps-**

o	Checked and confirmed no missing or duplicate values.

o	Maintained outliers since they represent meaningful market behavior.

o	Encoded categorical variables appropriately.

o	Used features such as: education_of_employee, has_job_experience, prevailing_wage, continent, region_of_employment, and unit_of_wage.

**2. Exploratory Data Analysis (EDA)**

**•	Univariate and Bivariate analysis:**

o	Most applicants came from Asia, followed by Europe.

o	Higher education and job experience are strongly associated with visa approvals.

o	Yearly wages are linked to higher certification rates, while hourly wage jobs often face denials.

o	Regions like Midwest have higher certification rates than others.

**3. Model Building and Evaluation**
   
**Applied various supervised classification models with hyperparameter tuning:**

✅ Decision Tree
✅ Bagging Classifier
✅ Random Forest
✅ AdaBoost
✅ Gradient Boosting
✅ XGBoost
✅ Stacking Classifier

Evaluation Metrics Used:

•	F1 Score, Recall, Precision (due to class imbalance and the importance of both false positives and false negatives).

**4. Model Selection**

•	Tuned Random Forest and Gradient Boosting Classifier provided the best F1 scores (~0.82–0.83).

•	Gradient Boosting was slightly better but more complex.

•	Tuned Decision Tree was slightly less performant but more interpretable for decision-making.
