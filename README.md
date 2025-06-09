# 🛍️ Customer Purchase Prediction using Decision Tree

## 📌 Project Objective
Build a Decision Tree Classifier to **predict whether an online visitor will make a purchase**, based on their **browsing behavior and session characteristics** using the **Online Shoppers Intention Dataset**.

---

## 🧠 Problem Statement
> Predict whether a customer will purchase a product or service based on their demographic and behavioral data.

This project addresses the real-world challenge of understanding user behavior on e-commerce platforms and predicting purchase intent.

---

## 📂 Dataset Used
- **Dataset**: Online Shoppers Intention Dataset  
- **Source**: Kaggle  
- **Target Variable**: `Revenue` (True = Purchase, False = No Purchase)  


---

## 🧾 Features Used
- **Behavioral Features**:  
  - Administrative, Informational, ProductRelated  
  - Duration on each type of page  
  - BounceRates, ExitRates, PageValues  
- **Session Context**:  
  - Month, OperatingSystems, Browser, Region, TrafficType  
  - VisitorType, Weekend  
- **Target Variable**: Revenue (binary classification)

---

## ⚙️ Technologies & Tools
- Python  
- Pandas  
- Scikit-learn  
- Seaborn

---

## 🧪 Model Used
- **Model**: `DecisionTreeClassifier` from `sklearn`
- **Train-Test Split**: 80% train, 20% test
- **Random State**: 4 (for reproducibility)

---

## 📊 Model Performance
- **Accuracy**: 85.96%
- **Precision (Purchase=True)**: 0.54  
- **Recall (Purchase=True)**: 0.58  
- **F1-score (Purchase=True)**: 0.56

---

## 📌 Key Insights
- The model performs well at predicting users who **did not purchase**.
- It has moderate performance in identifying actual purchasers.

