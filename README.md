
---

# 🌍 ImpactSense – Earthquake Impact Prediction

> ⚡ **Predicting the unseen. Saving lives before the shake.**

Earthquakes strike without warning, but their *impact* doesn’t have to remain unpredictable.
**ImpactSense** is a machine learning-powered project that forecasts the potential consequences of an earthquake—helping communities, city planners, and disaster management teams make informed, proactive decisions.

---

## 🚀 Project Overview

ImpactSense uses **geophysical & environmental data** (magnitude, depth, latitude, longitude, soil type, seismic features) to:

✅ Estimate the **severity or risk level** of an earthquake
✅ Highlight **high-risk urban zones**
✅ Assist **government & NGOs** in disaster response planning
✅ Support **infrastructure policy-making** in vulnerable areas

---

## 🎯 Key Use Cases

🔹 **Urban Risk Assessment**
Authorities can forecast the level of impact in densely populated regions.
*Example: Predict which districts face higher risk in a 5.5 magnitude quake based on soil type & location.*

🔹 **Infrastructure Planning**
City planners use predictions to guide safe construction policies.
*Example: Classify regions by seismic risk using soil density and fault line data.*

🔹 **Government Disaster Response**
Emergency teams prioritize areas for rescue & aid.
*Example: Rank impact zones for quick relief deployment.*

---

## 🏗️ System Architecture

![System Architecture](images/system_architecture.png)

The workflow covers:

1️⃣ **Data Exploration & Cleaning**
2️⃣ **Feature Engineering & Scaling**
3️⃣ **Model Development** (Logistic Regression → Random Forest → XGBoost)
4️⃣ **Model Evaluation** (Accuracy, F1, MAE/MSE, SHAP)
5️⃣ **(Optional) User Interface** with Streamlit for real-time predictions

---

## 🧩 Modules

**🔍 Data Exploration**

* Clean missing values, remove duplicates
* Visualize magnitude, depth, and locations

**⚙️ Feature Engineering**

* Normalize/scaling of numeric features
* Geospatial clustering & risk scoring
* Encode categorical values

**🤖 Model Development**

* Baseline: Logistic Regression, Decision Tree
* Advanced: Random Forest, Gradient Boosting, XGBoost

**📊 Evaluation**

* Classification: Accuracy, Precision, Recall, F1
* Regression: MAE, MSE, R²
* Visuals: Confusion Matrix, Feature Importance, SHAP

**💻 User Interface (Optional)**

* Simple Streamlit form
* Input: magnitude, depth, soil type, region
* Output: Risk category / damage score

---

## 🗓️ Project Timeline

**Milestone 1 – Data Foundations**

* 📅 Week 1: Dataset loading, feature exploration, geo-mapping
* 📅 Week 2: Preprocessing & feature engineering

**Milestone 2 – Modeling Core**

* 📅 Week 3: Baseline models (LogReg, Decision Tree)
* 📅 Week 4: Advanced models (RF, XGBoost, Hyperparameter tuning)

**Milestone 3 – Insights & UI**

* 📅 Week 5: Model explainability (Confusion Matrix, SHAP, training curves)
* 📅 Week 6: Streamlit prototype

**Milestone 4 – Polish & Present**

* 📅 Week 7: Testing edge cases, UI refinements
* 📅 Week 8: Final report, visualizations & presentation deck

---

## 📈 Model Performance

**For Classification (Risk Levels):**

* ✅ Accuracy – overall correctness
* ✅ Precision – correctness of "High Risk" predictions
* ✅ Recall – ability to capture all true "High Risk" cases
* ✅ F1-Score – balance of precision & recall
* ✅ Confusion Matrix – actual vs predicted

**For Regression (Damage/Cost Estimation):**

* 📉 MAE – Mean Absolute Error
* 📉 MSE – Mean Squared Error
* 📊 R² – Model’s explanatory power

**Explainability:**

* 🔎 Feature importance chart
* 🔎 SHAP values to explain predictions

---

## 🏆 Outcomes

By the end of the project, you’ll have:

✨ A cleaned and well-analyzed seismic dataset
✨ A trained ML model that predicts earthquake impact
✨ Visualizations of key features & model performance
✨ (Optional) A working **web-based predictor app**
✨ Final report & presentation for stakeholders

---

## ✅ Evaluation Criteria

* 🔹 Completion of milestones
* 🔹 Quality & reliability of predictions
* 🔹 Realism and interpretability of outputs
* 🔹 Clean documentation & visualization clarity

---

## 🌟 Inspiration

*"The biggest enemy of resilience is unpreparedness. Predicting impact is the first step toward saving lives."*

---

