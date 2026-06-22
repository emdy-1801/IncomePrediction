# IncomePrediction
A Machine Learning project using Random Forest and Decision Tree classifiers to predict and score credit levels based on professional experience and occupation.
## 📌 Project Overview
This repository contains a Jupyter Notebook that demonstrates a complete data science workflow, including data preprocessing, feature encoding, model training, and evaluation for a credit scoring system.

The model utilizes two main machine learning algorithms:
*   **Random Forest Classifier**
*   **Decision Tree Classifier**

## 📊 Dataset Structure
The model processes an Excel file (`staff.xlsx`) containing the following attributes:
*   **Features:** `Kinh nghiệm` (Experience), `Nghề nghiệp` (Occupation)
*   **Target:** `Mức thu nhập` (Income Level / Credit Rank)

## 🛠️ Technologies & Libraries Used
*   **Python 3.13**
*   **Pandas** - For data manipulation and loading Excel files
*   **Scikit-Learn** - For data splitting, label encoding, model training, and evaluation
*   **Joblib** - For model serialization

## 🚀 Workflow
1.  **Data Loading:** Read raw data from `staff.xlsx`.
2.  **Data Preprocessing:** Convert categorical features (`Kinh nghiệm`, `Nghề nghiệp`, `Mức thu nhập`) into numerical values using `LabelEncoder`.
3.  **Train-Test Split:** Divide the dataset into training (75%) and testing (25%) sets.
4.  **Model Training:** Train both `RandomForestClassifier` and `DecisionTreeClassifier`.
5.  **Evaluation:** Evaluate the model's performance using accuracy metrics.
6.  **Prediction:** Predict credit scores for new personnel inputs.

## 📈 Results
*   The model achieves a reliable baseline accuracy score (approx. **75%**) for credit classification based on the test set.
