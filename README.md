#  CrimeLens-W  
### A Machine Learning–Based Risk Assessment System for Crimes Against Women
CrimeLens-W is a data-driven Machine Learning project designed to assess and classify the risk levels of crimes against women across Indian states. By leveraging NCRB crime data and advanced ensemble ML models, the system predicts whether a region falls under **Low**, **Medium**, or **High** risk categories, enabling proactive decision-making and policy planning.


## Project Objective
The primary objective of CrimeLens-W is to move beyond descriptive crime statistics and provide a **predictive and interpretable risk assessment framework** for gender-based crimes. The system aims to assist policymakers, researchers, and analysts in identifying vulnerable regions and prioritizing preventive interventions.


## Key Features
-  Analysis of NCRB district-wise crime data (2017 onwards)
-  Extensive data cleaning and preprocessing
-  Feature engineering through grouping of crime categories:
  - Sexual Offences  
  - Domestic Violence  
  - Trafficking  
  - Other Crimes
-  Risk classification into **Low / Medium / High** using statistical thresholds
-  Ensemble ML models:
  - Random Forest  
  - XGBoost  
  - LightGBM
-  Handling class imbalance using **SMOTE**
-  Model explainability using **SHAP**
-  Rich visualizations (confusion matrices, feature importance, risk distribution)
-  Interactive dashboard for real-time risk prediction


## Dataset
- **Source:** India Data Portal (NCRB – Crime Against Women Dataset)
- **Granularity:** District-wise (aggregated to State-Year level)
- **Time Period:** 2017 onwards
- **Data Type:** Government-published structured tabular data

> Note: The dataset is publicly available and may contain reporting inconsistencies inherent to crime data.


## Tech Stack & Tools
- **Programming Language:** Python  
- **Development Environment:** Google Colab  
- **Libraries & Frameworks:**
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - Scikit-learn  
  - XGBoost  
  - LightGBM  
  - Imbalanced-learn (SMOTE)  
  - SHAP  
- **Model Storage:** Joblib  
- **Version Control:** Git & GitHub  


## Methodology Overview
1. Data collection and understanding  
2. Data cleaning and preprocessing  
3. Feature engineering and crime grouping  
4. Risk label creation using statistical measures  
5. Train-test split with stratification  
6. Class imbalance handling using SMOTE  
7. Model training and hyperparameter tuning  
8. Model evaluation using standard metrics  
9. Explainable AI analysis using SHAP  
10. Dashboard-based prediction demonstration  


## Model Performance (Tuned Models)

| Model | Accuracy | Precision (W) | Recall (W) | F1-Score (W) |
|------|----------|----------------|-------------|--------------|
| Random Forest | **0.93** | 0.93 | 0.93 | 0.93 |
| XGBoost | 0.91 | 0.91 | 0.91 | 0.91 |
| LightGBM | 0.91 | 0.91 | 0.91 | 0.91 |

> Random Forest emerged as the best-performing and most stable model.


## Dashboard Preview
The project includes a simple interactive dashboard where users can input crime statistics and receive instant risk-level predictions. This demonstrates the real-world applicability of the model.


##  Future Enhancements
- Integration of socio-economic indicators (literacy, population, income)
- Time-series forecasting of crime trends
- District-level geospatial analysis
- Deployment as a web application
- Real-time data ingestion


## Authors
- **Sneha Rakheja**  
  B.Tech CSE (3rd Semester), IGDTUW  
- **Shravyaa Gupta**  
  B.Tech CSE, IGDTUW  


## License
This project is intended for **academic and research purposes** only.


## Acknowledgement
We sincerely thank our faculty mentors and the Department of Computer Science & Engineering, IGDTUW, for their guidance and support throughout the project.


>  *CrimeLens-W demonstrates how Machine Learning and Explainable AI can be applied responsibly to address real-world social challenges.*
