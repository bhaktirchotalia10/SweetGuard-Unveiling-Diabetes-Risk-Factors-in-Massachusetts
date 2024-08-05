# SweetGuard-Unveiling-Diabetes-Risk-Factors-in-Massachusetts

SweetGuard aims to assess diabetes risk based on lifestyle and health habits. This project leverages data from the Behavioral Risk Factor Surveillance System (BRFSS) and a primary survey to understand and predict diabetes risk factors in Massachusetts. The insights gained from this analysis are intended to guide public health interventions and inform personal health recommendations. The project's primary aim is to understand and quantify the risk factors associated with diabetes in Massachusetts. By focusing on diet, exercise, sleep, and overall health habits, SweetGuard seeks to provide a comprehensive understanding of diabetes risk factors, guiding both public health strategies and personal health recommendations.

**Project Overview**
SweetGuard focuses on unveiling diabetes risk based on various lifestyle and health habits. This initiative aims to address the escalating prevalence of diabetes, particularly type 2, by understanding the factors contributing to this condition. The project utilizes BRFSS data from 2012, 2017, and 2022, along with primary survey data, to build predictive models for diabetes risk.

**Data Sources**
We utilized publicly accessible data collected by the United States government, specifically the Behavioral Risk Factor Surveillance System (BRFSS) dataset and primary survey data.
1. BRFSS 2012 Survey Data : https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system/data?select=2012.csv
2. BRFSS 2017 Survey Data : https://www.cdc.gov/brfss/annual_data/annual_2017.html
3. BRFSS 2022 Survey Data : https://www.cdc.gov/brfss/annual_data/annual_2022.html

**Data Collection and Preparation**
The data collection involved:
1. Data Discovery: Accessing and integrating diverse datasets.
2. Data Cleaning: Handling missing values, outliers, duplicates, and ensuring data consistency.
3. Data Transformation: Standardizing variables and formats for uniformity.
4. Data Reduction: Pruning unnecessary attributes to focus on relevant data.

**Modeling Techniques**
To predict diabetes risk, we employed a variety of machine learning models, each bringing unique strengths to the analysis. We began with Logistic Regression, chosen for its interpretability and effectiveness in binary classification tasks. Despite its simplicity, it served as a reliable baseline model. To capture non-linear relationships, we implemented Decision Trees, which excel at modeling such interactions. Hyperparameters were optimized using GridSearchCV to enhance model performance. Building on these results, we applied Random Forest models, leveraging ensemble learning to improve predictive accuracy and robustness against overfitting. Additionally, we utilized Gradient Boosting (XGBoost) for its advanced boosting capabilities, which further improved model performance. We also explored K-Nearest Neighbors (KNN) for its simplicity and intuitive approach in identifying patterns, and Support Vector Machine (SVM) for handling high-dimensional spaces and complex classification tasks. Each model was meticulously tuned to balance complexity and interpretability, ensuring reliable and actionable insights.

**Results**
The modeling efforts yielded significant results. The Logistic Regression model for diabetes prediction achieved a training accuracy of 85%, but the F1 score on test data was relatively low, indicating limitations in capturing non-linear relationships. The Decision Tree model, after optimization, demonstrated substantial improvement with a test accuracy of 85% and an F1 score of 0.92. The Random Forest model achieved a test accuracy of 85% and a weighted F1 score of 0.80, highlighting its effectiveness in predicting diabetes risk factors. Gradient Boosting (XGBoost) further enhanced model performance, confirming its advanced capabilities in boosting accuracy. The K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) models also contributed valuable insights, with each technique offering distinct advantages in pattern recognition and handling complex data structures. These results underscore the importance of selecting and optimizing the right model to achieve accurate and actionable diabetes risk predictions.

**Learnings from the Project**

**1. Data Quality is Crucial:** Ensuring complete and accurate data is essential for reliable predictions. Addressing missing values and inconsistencies improves model robustness.

**2. Effective Model Selection:** Different models like Logistic Regression, Decision Trees, and Random Forests offer unique benefits. Selecting and optimizing the right model is key for accurate predictions.

**3. High-Risk Segment Identification:** Identifying demographic and behavioral risk factors enables targeted health interventions and improved public health strategies.

**4. Feature Engineering Impact:** Creating and selecting relevant features significantly enhance model performance and predictive power.

**5. Managing Data Challenges:** Overcoming data volume and quality issues is crucial for maintaining the integrity of the analysis.

**6. Actionable Insights:** Translating predictive model results into practical health policies and preventive measures can effectively reduce the burden of diabetes.
