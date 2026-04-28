
# US Health Insurance Cost Prediction using Machine Learning

Streamlit App
https://gbinsuranceprediction-mupwwvqeeljhdzq2awy5f4.streamlit.app/

Hugging Face Deployment
https://huggingface.co/spaces/VTharun616/US_INSURENCE_PRIDICTION

## 1. Project Overview
Health insurance costs vary depending on multiple personal and health-related factors. In this project, I performed:
Data Cleaning
Duplicate Removal
Outlier Detection
Feature Preprocessing
Model Training using Multiple Regression Algorithms
Performance Evaluation using Regression Metrics
Final Model Selection based on Accuracy and Robustness
Deployment using Streamlit and Hugging Face

## 2. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Streamlit
- Hugging Face

## 3. Data Preprocessing

✔ Data Cleaning
Checked missing values
Removed duplicate rows

✔ Train Test Split
80% Training Data
20% Testing Data

✔ Outlier Handling
BMI column showed outliers using Boxplot
Used RobustScaler for numerical features

✔ Encoding
- OrdinalEncoder for categorical columns  
- RobustScaler for numerical columns  
- ColumnTransformer for preprocessing pipeline  

## 4. Algorithms Applied
I applied multiple regression algorithms for better model comparison:
✔ Gradient Boosting Regressor
✔ XGBoost Regressor
✔ Random Forest Regressor
✔ Linear Regression
✔ Decision Tree Regressor
✔ Support Vector Regressor
✔ KNN Regressor
✔ Extra Trees Regressor

## 5. Final Model Selection
- Gradient Boosting Regressor selected  
- Reason: highest accuracy, better robustness, good generalization 

Selected because of:
Higher Accuracy
Better Robustness
Strong Performance on Test Data
Better Generalization

## 6.Final model saved as:
gbr_model.pkl

## 7. Evaluation Metrics Used
✔ Mean Absolute Error (MAE)
✔ Root Mean Squared Error (RMSE)
✔ R2 Score
✔ Final MAE %
✔ Final RMSE %
These metrics helped compare all regression models and select the best one.

## 8. Project Workflow
Data Collection → Data Cleaning → EDA → Model Training → Evaluation → Deployment

## 9. Future Improvements
Add advanced feature engineering
Hyperparameter tuning using GridSearchCV
Cross Validation
Better UI improvements in Streamlit
Cloud deployment optimization

## Author
**Tharun Kumar Vadde**

Aspiring AI/ML Engineer focused on:
- Machine Learning  
- Deep Learning  
- NLP  
- RAG Systems  
- Generative AI Projects 
