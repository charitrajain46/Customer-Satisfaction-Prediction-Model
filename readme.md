# 📊 Customer Satisfaction Prediction

## Overview

This project analyzes customer support ticket data to understand the key drivers of customer satisfaction and to **predict satisfaction ratings** using machine learning. It demonstrates a complete **Data Analysis → Feature Engineering → Modeling → Evaluation** workflow implemented in a Jupyter Notebook.

---

## Problem Statement

Customer support teams handle large volumes of tickets across multiple channels. Manually identifying factors that affect customer satisfaction is inefficient. The goal is to **analyze historical ticket data** and build a model that can **predict customer satisfaction ratings** to support proactive service improvements.

---

## Dataset

The dataset contains customer support tickets for technology products.

**Target Variable:** Customer Satisfaction Rating (1–5)

**Key Features:**

* Customer demographics (age, gender)
* Product purchased
* Ticket type, priority, status, and channel
* First response time and time to resolution
* Ticket subject/description

---

## Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Environment:** Jupyter Notebook
* **Domain:** Data Analysis & Machine Learning

---

## Methodology

1. **Data Preprocessing** – handled missing values, encoded categorical variables, standardized numerical features
2. **Exploratory Data Analysis (EDA)** – visualized ticket trends, channels, priorities, and satisfaction distribution
3. **Feature Engineering** – created meaningful features and selected relevant predictors
4. **Modeling** – trained a **Random Forest Classifier**
5. **Evaluation** – assessed performance using accuracy, classification report, confusion matrix, and feature importance

---

## Key Insights

* Faster response and resolution times lead to higher satisfaction
* Ticket priority strongly impacts ratings
* Chat and phone channels generally show better satisfaction
* Unresolved high-priority tickets reduce customer ratings

---

## Project Structure

```
├── Customer Satisfaction Prediction.ipynb
├── customer_support_tickets.csv
├── Project_Report.pdf
├── README.md
```

---

## Conclusion

The project shows how **data-driven insights and machine learning** can improve customer support operations by predicting satisfaction in advance, enabling better SLA management and customer experience.

---

## Future Work

* Apply NLP for sentiment analysis on ticket text
* Try advanced models (XGBoost/LightGBM)
* Build a dashboard (Power BI/Tableau)
* Deploy the model using Flask or Streamlit

---

## Author

**Charitra Jain** — MCA Student | Aspiring Data Analyst & Data Scientist

Python | SQL | EDA | Machine Learning

🔗 LinkedIn: https://www.linkedin.com/in/charitra-jain-8271b4240/
