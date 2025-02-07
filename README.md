## Optimizing CO2 Hydrogenation to Methanol Analysis with a Structure Network and Attention-Based Aggregation in a Hybrid CatBoost Framework
<img width="800" alt="截屏2025-02-07 11 46 58" src="https://github.com/user-attachments/assets/4e3fbd1b-df03-46d0-a5e3-7b7bfb28af4f" />

### Description:
This project focuses on optimizing the prediction of methanol yield in the CO2 hydrogenation process using machine learning techniques. Given the increasing importance of carbon capture and conversion, this study leverages a hybrid CatBoost model to handle complex catalytic behaviors and multiple data sources, including reaction conditions, physical properties, and electronic/3D structural features.
### The project introduces several innovative elements:
1. A lasso layer for feature selection, enhancing model interpretability.

2. A bagging layer to increase stability and reduce variance.

3. Ordered boosting for more refined incremental predictions.

4. An attention-based aggregation module combined with spectral clustering and a memory matrix, which dynamically adjusts feature weights for improved accuracy.

5. The model achieved an R² of 0.9312 and minimal overfitting, demonstrating its robustness in predicting methanol yield. SHAP analysis identified that reaction conditions (GHSV, temperature, and specific surface area) were the most influential factors, followed by catalyst and support properties.

6. Additionally, the project used Sparse Principal Component Analysis (SPCA) to further analyze the variation in the data. Key materials (In2O3, Cu, Pd, ZnO-ZrO2) were mapped within the principal component space, revealing important interactions that can help optimize catalyst design for CO2 hydrogenation to methanol.
This work showcases the potential of hybrid models for complex chemical systems and provides insights for improving catalyst performance in CO2 hydrogenation reactions.
### Technologies:
	• CatBoost, XGBoost, Random Forest, BP Neural Network
	• Feature Engineering, SPCA, SHAP Analysis
	• Python, R, Pandas, Scikit-learn, Matplotlib
### Skills:
	• Machine Learning, Data Preprocessing, Model Optimization
	• Statistical Analysis, Algorithm Tuning, Model Evaluation
	• Problem Solving, Data Visualization, Report Writing

