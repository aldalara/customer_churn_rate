
# Customer Churn Rate Telco Telecommunication

📂 Data:
This folder contains the datasets used in the project:

- WA_Fn-UseC_-Telco-Customer-Churn.csv - Original raw data.
- df_num.csv - Cleaned and transformed data for analysis and modeling.

📂 Memory:
This folder contains key project documents, organized by language (CAS for Spanish, ENG for English):

- Memory Telco Project.pdf - Complete project report, including analysis, methodologies, and results.
- Telco Cluster Segmentation.pdf: Detailed report on customer segmentation into clusters.

📂 Model:
This folder contains the final production model and the record of all tests performed during development:

- Predictor Model:

churn_detection_pipeline.pkl - Complete pipeline of the final model ready for production use, including all pre-processing, feature selection, and prediction stages.

- Model Tracking:

Model Tracking.pdf - Document detailing all tests conducted, hyperparameters evaluated, and results obtained in each iteration leading to the final model.

📂 Notebooks
The notebooks document the entire project development, from data preparation to segmentation and predictive modeling. They are organized sequentially:

- 1_Objectives_Data_preparation.ipynb:

    - Introduction to the project, definition of objectives, and initial exploratory analysis.
    - Data pre-processing, including cleaning and transformation.

- 2_RandomForest.ipynb

    - Implementation and evaluation of a Random Forest model as a starting point for predictions.
    - Key metrics and basic optimization.

- 3_LogisticRegression.ipynb

    - Application of a logistic regression model and transformations.
    - Comparison of results with other models.

- 4_XGBoost.ipynb

    - Implementation of the XGBoost model, including hyperparameter tuning.
    - Integration of an Ensemble Voting Classifier to combine models and improve performance.
    - Final result and analysis of the best predictor model.

- 5_KMeans_Segmentation.ipynb

    - Customer segmentation using K-Means clustering.
    - Identification of patterns and key groups for churn analysis. (Extended conclusions in the memory folder)

THANKS! Lara Aldalur :)

