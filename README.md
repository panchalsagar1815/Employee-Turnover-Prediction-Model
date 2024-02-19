# Employee-Turnover-Prediction-Model

**Project: Employee Turnover Prediction - Plastic Elasticity of Demand Analysis**

**Objective:**
The project focuses on predicting employee turnover within a company by analyzing various employee-related features. The dataset includes attributes such as 'satisfaction_level,' 'last_evaluation,' 'number_project,' 'average_monthly_hours,' 'time_spend_company,' 'Work_accident,' 'left,' 'promotion_last_5years,' 'sales,' and 'salary.' The goal is to employ machine learning models to forecast whether an employee is likely to stay or leave, enabling proactive HR strategies.

**Project Phases:**

1. **Data Preprocessing:**
   - Conducted thorough data cleaning to handle missing values, and outliers, and ensure data consistency.
   - Employed preprocessing techniques suitable for categorical and numerical features.

2. **Data Visualization and Exploratory Data Analysis (EDA):**
   - Utilized visualizations to understand feature distributions, correlations, and patterns.
   - Explored relationships between employee attributes and the likelihood of turnover.

3. **Machine Learning Models:**
   - Implemented multiple machine learning models for turnover prediction:
      - **Logistic Regression**
      - **Random Forest**
      - **Support Vector Machine (SVM)**

4. **Model Evaluation Metrics:**
   - Calculated precision and recall to assess model performance.
      - **Recall:** Measures how often the classifier correctly predicts turnover.
      - **Precision:** Indicates the accuracy of predicting actual turnover when the classifier predicts it.

**Insights:**
- **Recall Measurement:**
  - Random Forest achieved the highest recall (95%), correctly identifying 991 out of 1038 turnover cases.
  - Logistic Regression and SVM had lower recall rates (26% and 85% respectively).

- **Precision Measurement:**
  - Random Forest demonstrated superior precision (95%), predicting turnover accurately in 991 out of 1045 cases.
  - Logistic Regression and SVM showed lower precision rates (51% and 77% respectively).

**Conclusion:**
The project not only provides accurate turnover predictions but also highlights the superior performance of the Random Forest model in both recall and precision metrics. These insights are crucial for HR strategies, enabling proactive measures to retain valuable employees. The analysis demonstrates the significance of leveraging machine learning for effective workforce management and employee retention.
