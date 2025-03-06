📊 Project Overview

This project explores the Portugal Bank Marketing dataset to predict whether a client will subscribe to a term deposit. We conduct Exploratory Data Analysis (EDA), preprocess the data, and build supervised learning models to make predictions.

🗃️ Dataset Description

The dataset contains 22 features, including demographic, economic, and campaign-related attributes. The target variable (y) indicates whether the client subscribed to a term deposit ("yes" or "no").

Bank client data: Age, Job, Marital Status, Education, Loan Status

Campaign data: Last contact duration, Number of contacts, Previous campaign outcome

Economic indicators: Employment variation rate, Euribor 3-month rate, Consumer price index

🔍 Tasks Performed

1. Exploratory Data Analysis (EDA)

Visualized distributions of categorical features

Analyzed correlations between numerical features

Identified insights such as higher subscriptions among retirees and students

2. Data Preprocessing

Missing Value Analysis: Handled missing values with imputation strategies

Encoding: Applied label encoding for categorical variables

Feature Selection: Used Decision Trees to select important features

Handling Class Imbalance: Applied SMOTE to balance the dataset

Standardization: Standardized numerical features using StandardScaler

3. Model Building 

Logistic Regression: Interpretable baseline model

Decision Tree: Captures complex decision boundaries

4. Model Evaluation & Tuning 

Metrics Compared: Accuracy, Precision, Recall, F1-Score, ROC-AUC

Hyperparameter Tuning: Performed GridSearchCV for optimal parameters

Best Model: Decision Tree outperformed Logistic Regression in identifying potential subscribers

🏁 Results

Logistic Regression: F1-Score: 0.78 | ROC-AUC: 0.81

Decision Tree (Tuned): F1-Score: 0.84 | ROC-AUC: 0.87

📂 Repository Structure

├── data/
│   └── bank_marketing.csv
├── notebooks/
│   ├── eda.ipynb
│   ├── preprocessing.ipynb
│   └── modeling.ipynb
├── README.md
└── requirements.txt

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/Rashu0304/Supervised-Learning-Project---Portugal-Bank-Marketing-Dataset.git

Install dependencies:

pip install -r requirements.txt

Execute the Jupyter Notebooks:

jupyter notebook

📘 Learnings

Importance of feature engineering and handling class imbalance

Model tuning significantly boosts performance

EDA helps uncover valuable patterns in customer behavior

🛠️ Tech Stack

Python: Pandas, NumPy, Matplotlib, Seaborn

ML Libraries: Scikit-learn, Imbalanced-learn

Tools: Jupyter Notebook, Git

📈 Future Improvements

Try ensemble models (Random Forest, XGBoost)

Use PCA for dimensionality reduction

Deploy the model using Flask or Streamlit

👩‍💻 Author

Rashmita GaudaAspiring Data Analyst | Machine Learning Enthusiast

Feel free to connect with me on LinkedIn 🚀 (https://www.linkedin.com/in/rashmitagauda/)
