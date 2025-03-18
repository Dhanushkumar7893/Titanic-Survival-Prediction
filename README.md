 🚢 Titanic Survival Prediction
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. By analyzing the dataset, we build a model to determine survival probability based on passenger details such as age, gender, class, and fare.

📌 Project Overview
The Titanic dataset is one of the most famous datasets in machine learning and is often used for binary classification problems. The goal is to predict whether a passenger survived the disaster based on given features.

📂 Project Structure
mathematica

📂 Titanic-Survival-Prediction
│── 📄 README.md                 ← Project Documentation
│── 📄 Titanic_Data_Preprocessing.ipynb  ← Data Cleaning & Preprocessing
│── 📄 Titanic_Model_Training.ipynb      ← Model Selection & Training
│── 📄 Titanic_Predictions.ipynb         ← Final Predictions
│── 📄 requirements.txt         ← Required Python Libraries
│── 📂 dataset                  ← Dataset Folder
│     ├── titanic_train.csv      ← Training Dataset
│     ├── titanic_test.csv       ← Test Dataset
│── 📂 models                   ← Saved Model Folder
│     ├── best_model.pkl         ← Trained Model File

🔹 Dataset
Source: Kaggle Titanic Dataset
Columns Used:
PassengerId: Unique ID of passenger
Survived: 0 = No, 1 = Yes (Target Variable)
Pclass: Passenger class (1st, 2nd, 3rd)
Name, Sex, Age: Passenger details
SibSp, Parch: Number of siblings/spouses and parents/children aboard
Ticket, Fare: Ticket number and fare paid
Cabin, Embarked: Cabin number and port of embarkation

🚀 Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Dhanushkumar7893/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction

2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt

3️⃣ Run Jupyter Notebook
bash
Copy
Edit
jupyter notebook
Open the .ipynb files in Jupyter Notebook and execute the code step by step.

🏆 Machine Learning Pipeline
Data Preprocessing

Handle missing values
Encode categorical variables
Feature scaling
Model Training

Tried multiple models (Logistic Regression, Random Forest, XGBoost)
Selected the best model based on accuracy and precision
Prediction & Evaluation

Evaluated using accuracy, precision, recall, F1-score
Saved the best-performing model as best_model.pkl

📊 Model Performance
Model	Accuracy
Logistic Regression	78.5%
Random Forest	83.2%
XGBoost	85.1%

✨ Future Improvements
Improve feature engineering
Hyperparameter tuning for better accuracy
Deploy as a web application using Flask

📜 License
This project is open-source and available under the MIT License.

🙌 Acknowledgments
Kaggle Titanic Dataset
Scikit-Learn Documentation
