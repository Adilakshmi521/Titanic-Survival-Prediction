# Titanic Survival Prediction

## Alfido Tech – Machine Learning Internship (Task 3)

### Project Overview
This project uses Machine Learning classification algorithms to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, fare and family size.

### Dataset
- Dataset: Titanic Passenger Dataset
- Source: Kaggle Titanic Competition
- File: train.csv
- Target Variable: Survived
  - 0 = Not Survived
  - 1 = Survived

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

### Project Workflow
1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Handling Missing Values
5. Feature Engineering
6. Categorical Encoding
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Feature Importance Analysis
11. Model Saving

### Feature Engineering
The following features were created:
- Title: Extracted passenger titles from names.
- FamilySize: Total number of family members travelling together.
- IsAlone: Identifies passengers travelling alone.

### Machine Learning Algorithms
Three classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

### Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Feature Importance
Random Forest feature importance was used to understand which passenger characteristics contributed most to survival predictions.

### Project Files
- Titanic_Survival_Prediction.ipynb – Project notebook
- best_titanic_model.pkl – Saved best-performing model and preprocessing information
- model_comparison.csv – Model evaluation results
- feature_importance.csv – Feature importance results
- README.md – Project documentation
- requirements.txt – Required Python libraries

### How to Run the Project
1. Download or clone this repository.
2. Install the required dependencies using:

   pip install -r requirements.txt

3. Open the Jupyter Notebook.
4. Upload the Titanic dataset (train.csv).
5. Run all notebook cells sequentially.
6. View the model evaluation results and survival predictions.

### Conclusion
This project demonstrates how machine learning classification techniques can be applied to predict Titanic passenger survival. Different classification algorithms were compared to identify the best-performing model.

*Developed as part of the Alfido Tech Machine Learning Internship.*
