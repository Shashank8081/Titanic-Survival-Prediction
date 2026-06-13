# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

The Titanic Survival Prediction project aims to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, ticket class, fare, family members, and embarkation port.

This project demonstrates the complete Machine Learning workflow, including:

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Evaluation
* Feature Importance Analysis

---

## 📊 Dataset

The dataset contains information about Titanic passengers, including:

| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique Passenger ID               |
| Survived    | Survival Status (0 = No, 1 = Yes) |
| Pclass      | Passenger Class                   |
| Name        | Passenger Name                    |
| Sex         | Gender                            |
| Age         | Age of Passenger                  |
| SibSp       | Number of Siblings/Spouses Aboard |
| Parch       | Number of Parents/Children Aboard |
| Ticket      | Ticket Number                     |
| Fare        | Ticket Fare                       |
| Cabin       | Cabin Number                      |
| Embarked    | Port of Embarkation               |

Dataset Source:
https://www.kaggle.com/competitions/titanic/data

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Random Forest Classifier

---

## 📂 Project Workflow

### 1. Data Loading

* Imported Titanic dataset
* Inspected dataset structure

### 2. Data Cleaning

* Filled missing Age values using median
* Filled missing Embarked values using mode
* Removed Cabin column due to excessive missing values

### 3. Exploratory Data Analysis (EDA)

Visualized:

* Survival Distribution
* Gender vs Survival
* Passenger Class vs Survival
* Age Distribution

### 4. Feature Engineering

Converted categorical variables into numerical format using Label Encoding.

### 5. Model Building

Used Random Forest Classifier to train the prediction model.

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 7. Feature Importance

Analyzed the most influential features affecting passenger survival.

---

## 📈 Results

### Key Insights

✔ Female passengers had significantly higher survival rates.

✔ First-class passengers were more likely to survive.

✔ Fare was positively associated with survival probability.

✔ Age had a moderate impact on survival.

### Model Performance

* Algorithm: Random Forest Classifier
* Accuracy Achieved: ~84%

---

## 📊 Sample Visualizations

### Survival Distribution

Shows the number of passengers who survived and did not survive.

### Gender vs Survival

Demonstrates that female passengers had a higher survival rate.

### Passenger Class vs Survival

Illustrates survival differences across passenger classes.

### Feature Importance

Highlights the most influential features used by the model.

---

## 🚀 How to Run the Project

### Step 1

Clone the repository:

```bash
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
```

### Step 2

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 3

Open the Jupyter Notebook or Google Colab notebook.

### Step 4

Upload the Titanic dataset (train.csv).

### Step 5

Run all cells sequentially.

---

## 📁 Project Structure

```text
Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── train.csv
├── titanic_model.pkl
├── README.md
└── images/
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Data Preprocessing
* Missing Value Handling
* Data Visualization
* Feature Encoding
* Machine Learning Classification
* Model Evaluation
* Feature Importance Analysis

---

## 👨‍💻 Author

Shashank Singh 

B.Tech Student | Aspiring Data Analyst 

---

## ⭐ Future Improvements

* Hyperparameter Tuning
* Cross Validation
* Streamlit Web Application
* Deployment on Cloud Platforms
* Comparison with Multiple ML Algorithms

---

## 📜 License

This project is intended for educational and learning purposes.
