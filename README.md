# Healthcare Risk Prediction with Random Forest

This project is a healthcare AI model built using Python and scikit-learn to predict patient health risk levels (Low, Moderate, High) based on demographic, socioeconomic, and medical history data.

## 💡 Project Goal

The goal of this project is to explore machine learning in the healthcare space by building a classification model that predicts a patient's health risk score. The model can help identify high-risk individuals and support early intervention strategies.

## 📊 Dataset

The dataset includes synthetic healthcare data with the following features:

- Age
- Gender
- Ethnicity
- Income Level
- Employment Status
- Medical History
- Health Risk Score (Target)

Additional sample records were created to balance the dataset and improve classification performance.

## 🛠 Tools & Technologies

- **Python**
- **Pandas** for data processing
- **scikit-learn** for model training and evaluation
- **RandomForestClassifier** for classification
- **LabelEncoder** for categorical feature encoding
- **Google Colab** for development and execution

## 📈 Key Steps

- Data cleaning and encoding of categorical features
- Class filtering to remove underrepresented health risk classes
- Splitting data into training and testing sets (70/30)
- Training a Random Forest model
- Evaluating model performance with:
  - Confusion matrix
  - Classification report (accuracy, precision, recall)
- Exporting the trained model using `joblib`

## ⚙️ Model Performance

The initial model achieved **~62% accuracy** on the test data. Performance can be further improved by:
- Hyperparameter tuning
- Adding more diverse training data
- Exploring alternative classification algorithms

## 🚀 Future Improvements

- Implement cross-validation
- Tune hyperparameters using GridSearchCV
- Add more advanced visualizations (e.g., SHAP for feature importance)
- Improve dataset size and balance for better generalization

## 📂 Output

- Trained model saved as `random_forest_model.joblib`
- Notebook includes full pipeline from preprocessing to evaluation

## 🔗 Try It Out

This notebook was developed in **Google Colab** and can be adapted for use with any structured healthcare dataset.

---

*Project by [Your Name]*  
