
**DevelopersHub-Co. Advanced Tasks**
This repository contains solutions for three core data science tasks, demonstrating proficiency in classification, unsupervised clustering, and time-series forecasting. Each project focuses on end-to-end implementation—from data preprocessing to model interpretability and evaluation.
________________________________________
**Task 1: Term Deposit Subscription Prediction (Bank Marketing)**
Dataset: Bank Marketing Dataset (UCI Machine Learning Repository)
Skills Used: Classification, Random Forest, SHAP (Explainable AI), Feature Engineering
🎯 **Objective**
To build a machine learning model that predicts whether a bank customer will subscribe to a term deposit. This helps financial institutions focus marketing efforts on high-probability leads to reduce costs.
💡 **Approach**
1.	Modeling: Developed and compared Logistic Regression and Random Forest classifiers.
2.	Efficiency: Used a representative subset for training and evaluation due to the dataset size.
3.	Explainability: Implemented SHAP (SHapley Additive exPlanations) to visualize which features drove the model’s "Yes/No" predictions.
📊 **Results and Insights**
•	Top Model: Random Forest outperformed Logistic Regression, handling complex relationships effectively.
•	Key Influencers: Call duration, campaign frequency, and previous campaign outcomes were the most critical factors.
•	Impact: SHAP values provide transparency, making the model interpretable for bank managers.
________________________________________
**Task 2: Customer Segmentation Using Unsupervised Learning**
Dataset: Mall Customers Dataset
Skills Used: K-Means Clustering, PCA, t-SNE, Elbow Method, Silhouette Analysis
🎯 **Objective**
To segment retail customers based on annual income and spending behavior, enabling data-driven, targeted marketing strategies.
💡** Approach**
1.	Clustering: Applied K-Means to group customers based on "Annual Income" and "Spending Score."
2.	Optimization: Used the Elbow Method and Silhouette Analysis to confirm 5 clusters.
3.	Visualization: Employed PCA and t-SNE for 2D and 3D visual validation of clusters.
📊 **Results and Insights**
•	Cluster Identification:
o	Target Group: High Income, High Spenders → Luxury products.
o	Budget Group: Low Income, Low Spenders → Value bundles.
o	Potential Group: High Income, Low Spenders → Brand engagement.
•	Business Conclusion: Identified 5 actionable customer personas for personalized marketing campaigns to maximize engagement and ROI.
________________________________________
**Task 3: Energy Consumption Time Series Forecasting**
Dataset: Household Power Consumption Dataset
Skills Used: Time Series Analysis, ARIMA, Facebook Prophet, XGBoost, Lag Engineering
🎯 **Objective**
To predict Global Active Power (total household electricity usage) using statistical, seasonal, and machine learning models.
💡 Approach
1.	Model Benchmarking: Evaluated ARIMA (Statistical), Prophet (Seasonal Trend), and XGBoost (Feature-based ML).
2.	Feature Engineering: Created time-based features (hour, day of week) and lag variables for temporal dependencies.
3.	Short-term Analysis: Zoom-in forecast on a 168-hour window (1 week) to compare model accuracy.
📊 **Results and Insights**
•	Model Comparison:
o	Prophet: Captures daily rhythms (e.g., morning peaks).
o	XGBoost: Responsive to sudden spikes.
o	ARIMA: Stable baseline but struggles with high volatility.
•	Conclusion: Hybrid models combining seasonal trends (Prophet) and reactive features (XGBoost) offer robust forecasting for load management.

