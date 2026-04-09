# 🚢 Titanic Survival Prediction (ML Project)

## 📌 Overview

This project builds a Machine Learning model to predict whether a passenger survived the Titanic disaster based on features like age, gender, class, and more.

It demonstrates a complete **end-to-end ML pipeline**:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation

---

## 🎯 Objective

To predict passenger survival using historical Titanic dataset and apply real-world ML workflow.

---

## 🧠 Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib & Seaborn 📊
* Scikit-learn 🤖

---

## 📂 Project Structure

```
titanic-ml-project/
│── data/
│     └── titanic.csv
│── main.py
│── README.md
```

---

## ⚙️ Workflow

### 🔹 Phase 1: Data Gathering

* Loaded dataset using Pandas
* Inspected structure using `.info()`, `.describe()`

### 🔹 Phase 2: Data Preprocessing

* Handled missing values:

  * Age → median
  * Embarked → mode
* Dropped irrelevant columns:

  * Cabin, Ticket, Name, etc.
* Encoded categorical features:

  * Sex → numeric
  * Embarked → one-hot encoding

---

### 🔹 Phase 3: Exploratory Data Analysis (EDA)

* Visualized distributions:

  * Age, Fare, Survival
* Analyzed relationships:

  * Survival vs Gender
  * Survival vs Class
* Generated correlation heatmap

---

### 🔹 Phase 4: Feature Engineering

* Created new features:

  * `FamilySize`
  * `IsAlone`
  * `FarePerPerson`
  * `AgeGroup`
* Extracted `Title` from names

---

### 🔹 Phase 5: Model Training

* Train/Test Split (80/20)
* Model used:

  * Logistic Regression
* Evaluated using:

  * Accuracy
  * Confusion Matrix
  * Classification Report

---

## 📊 Results

* Achieved a working classification model
* Successfully predicted survival outcomes
* Built a complete ML pipeline

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run project
python main.py
```

---

## 💡 Key Learnings

* Handling missing data effectively
* Feature engineering improves model performance
* Importance of removing data leakage (Boat, Body)
* Real-world debugging of ML pipelines

---

## 🔥 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Model deployment using Flask or Streamlit
* Add UI dashboard


---

## ⭐ If you like this project

Give it a star ⭐ and feel free to contribute!
