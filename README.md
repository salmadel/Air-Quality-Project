# Air Quality Classification using Machine Learning

## Project Overview
Air pollution is a critical environmental issue that impacts public health and overall quality of life. This project utilizes machine learning to classify air quality as Normal or Abnormal, helping in effective monitoring and decision-making. By analyzing key environmental factors, the model identifies pollution patterns and provides actionable insights.

The project follows a structured workflow, including Exploratory Data Analysis (EDA) to understand patterns, data preprocessing to clean and prepare the data, and model training using XGBoost, a powerful gradient boosting algorithm. The trained model is then evaluated to ensure high accuracy, and the results are visualized for better interpretation.

The goal is to develop an accurate classification model that can help monitor air pollution and support proactive environmental actions.

## Project Objectives
 • Build a highly accurate air quality classification model.
 
 • Identify key environmental factors that influence air pollution levels.
 
 • Provide data-driven insights to support air quality monitoring and decision-making.
 
 • Enhance awareness of air pollution trends for better environmental management.

## Team Members
**1. Dr/** [Mohamed Elsayed Nassar](https://github.com/Mohamed-Nassar88)

**2. Dr/** [Amal Adel Sheta](https://github.com/DrAmalSheta)

**3. Eng/** [Ahmed Hamdy Kandil](https://github.com/AhmedKandil2014)

**4. Eng/** Yara Saeed Abdelfadil

**5. Eng/** [Salma Adel Saleh](https://github.com/salmadel)

## Dataset

The dataset is sourced from Kaggle, a platform for machine learning and data analytics competitions. It contains 1.2 million+ observations collected from 14 different sensors between December 31, 2018, and February 28, 2020.

[Dataset Link](https://www.kaggle.com/code/genjihasky/classification-model-map-visualization/input)

## Attributes Information

The dataset consists of 14 columns, including:

 **1. Time_stamp** – Timing records at 3-minute intervals.
 
 **2. boxName** – Categorical variable representing 14 different sensors (e.g., ‘iGude’, ‘Rothschildallee’).
 
 **3. PM 2.5** – Particulate Matter 2.5 concentration.
 
 **4. temp** – Temperature at the sensor location.
 
 **5. pressure** – Atmospheric pressure.
 
 **6. humidity** – Humidity percentage.
 
 **7. wind_speed** – Wind speed at the sensor location.
 
 **8. Time of Day** – Time category (Morning, Afternoon, Evening, Night).
 
 **9. Peak/NoPeak** – Indicates whether it is a peak traffic time.
 
 **10. Day** – Day of the week (Monday-Sunday).
 
 **11. Week Day** – Identifies whether it is a workday or weekend.
 
 **12. Weather** – General weather condition.
 
 **13. Weather Description** – Detailed weather description.
 
 **14. label** – Target variable: Normal (Good air quality) or Abnormal (Poor air quality).

## Project Workflow
 #### 1. Exploratory Data Analysis (EDA)
 • Understanding data distribution and patterns

 • Visualizing correlations between features
 
 • Identifying missing values and outliers
 #### 2. Data Preprocessing
 • Handling outliers
 
 • Feature selection and scaling
 
 • Encoding categorical variables 
#### 3. Model Training & Evaluation
 • Training XGBoost model
 
 • Evaluating performance using metrics like Accuracy, Precision, Recall, and F1-score
 
 • Hyperparameter tuning for optimization
 #### 4. Results & Visualization
 • Feature importance analysis
 
 • Confusion matrix and classification reports
 
 • Mapping air quality predictions on a geographical scale

## Used Technologies
 • Python
 
 • Pandas, NumPy (Data processing)
 
 • Matplotlib, Seaborn (Visualization)
 
 • Scikit-learn (Machine Learning models)
 
 • Folium (Geographical visualization)

## Results & Insights
 The best-performing model **XGBoost** achieved:
 
 **• Accuracy:** 99.3%
 
 **• Precision:** 90.2%
 
 **• Recall:** 95.7%
 
 **• F1 score:** 92.9%
 
![download (2)](https://github.com/user-attachments/assets/e9af3c02-fd8b-48b5-ad31-9cc5789e1de7)
![download (4)](https://github.com/user-attachments/assets/a9b68c21-79db-41fd-93cb-6adfc9dd3df9)
![download (3)](https://github.com/user-attachments/assets/ac8dbdaf-81ef-4d8c-a540-8cdc5651702a)

