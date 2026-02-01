# Space-X-Falcon-9-First-Stage-Landing-Prediction
This is IBM Data Science capstone project analyzes SpaceX Falcon 9 launch data to predict first-stage landing success. It covers data collection via APIs, EDA, feature engineering, SQL analysis, visualization, and machine learning model evaluation.

# SpaceX Falcon 9 First Stage Landing Prediction 🚀

## Project Overview
This project is part of the **IBM Data Science Professional Certificate Capstone**. It focuses on predicting whether the **Falcon 9 first stage will land successfully**, which is a key factor in reducing launch costs through rocket reusability.

## Objectives
- Collect SpaceX launch data using REST APIs and web scraping  
- Perform Exploratory Data Analysis (EDA)  
- Analyze launch data using SQL  
- Apply feature engineering and one-hot encoding  
- Build and evaluate machine learning models  
- Identify the best-performing model for landing prediction  

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SQL (SQLite)  
- Scikit-learn  
- Folium, Plotly  
- Jupyter Notebook  

## Machine Learning Pipeline
The machine learning pipeline includes:
- Data preprocessing and standardization  
- Train-test split  
- Hyperparameter tuning using GridSearchCV  
- Model evaluation using accuracy and confusion matrix  

## Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  

## Key Insights
- Launch success rate increased over time  
- Payload mass and orbit type impact landing success  
- Decision Tree and SVM achieved the highest accuracy on test data  

## Project Structure
- `data_collection_api.ipynb`
- `data_wrangling.ipynb`
- `eda_visualization.ipynb`
- `sql_analysis.ipynb`
- `ml_prediction.ipynb`
- `dataset_part_*.csv`

## Conclusion
This project demonstrates an end-to-end data science workflow, following IBM industry standards, from data collection and analysis to machine learning prediction.
