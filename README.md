#  Personal Loan Acceptance Prediction using Machine Learning

##  Project Overview

This project develops a **machine learning classification model** to predict whether a customer will accept a personal loan offer based on demographic, financial, and campaign-related data.

The goal is to improve marketing efficiency by targeting customers who are more likely to convert.

---

##  Business Problem

Banks conduct large-scale marketing campaigns to promote loan products. However, targeting all customers is inefficient and costly.

This project helps to:

* Identify high-potential customers
* Improve campaign conversion rates
* Reduce marketing costs
* Enable data-driven decision-making

---

##  Dataset Description

The dataset is based on a bank marketing campaign and contains customer and campaign-related features.

### Key Features:

* `age` — Customer age
* `job` — Occupation
* `marital` — Marital status
* `education` — Education level
* `balance` — Account balance
* `housing` — Housing loan status
* `loan` — Personal loan status
* `poutcome` — Outcome of previous campaign

### Target Variable:

* `y` — Loan acceptance (yes/no)

---

## Data Preprocessing

* Corrected dataset format using proper delimiter (`;`)
* Standardized column names
* Applied one-hot encoding for categorical variables
* Prepared dataset for classification modeling

---

##  Exploratory Data Analysis (EDA)

Key analyses performed:

* Loan acceptance distribution
* Impact of age on acceptance
* Influence of job and marital status
* Effect of previous campaign outcomes

### Key Observations:

* Dataset is imbalanced with fewer positive responses
* Previous campaign success strongly influences acceptance
* Demographic and occupational factors impact customer decisions

---

##  Machine Learning Models

The following models were implemented:

* **Logistic Regression** — Baseline model for probability prediction
* **Decision Tree Classifier** — Captures nonlinear relationships

---

##  Model Training

* Train-test split with stratification
* Feature scaling using StandardScaler
* Pipeline implementation for structured workflow

---

##  Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score

### Results:

* Logistic Regression provided stable and generalizable performance
* Decision Tree captured complex patterns but required depth control
* ROC-AUC demonstrated strong predictive capability

---

##  Feature Importance

Feature importance analysis shows:

* Previous campaign outcome is the strongest predictor
* Job type and financial attributes significantly influence acceptance
* Behavioral data outperforms purely demographic features

---

##  Key Insights

* Past customer behavior is the most reliable predictor of future actions
* Targeted marketing significantly improves conversion rates
* Customer segmentation enhances campaign effectiveness

---

##  Business Recommendations

* Focus campaigns on customers with positive past responses
* Segment customers based on job, age, and financial profile
* Use predictive models to optimize marketing resource allocation

---

##  Risk Considerations

* False positives increase unnecessary marketing costs
* False negatives result in missed revenue opportunities
* Imbalanced data can bias model predictions

---

##  Limitations

* Dataset may not include all behavioral or economic factors
* Campaign outcomes may vary over time
* Model performance depends on data distribution

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

---

##  How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

Run all cells sequentially.

---

##  Project Structure

```
loan-acceptance-prediction/
│
├── loan_analysis.ipynb
├── README.md
└── requirements.txt
```
---
## Screen Shots
<img width="916" height="752" alt="image" src="https://github.com/user-attachments/assets/1d1e69de-27a3-457a-a203-7bce67706ba7" />
<img width="896" height="691" alt="image" src="https://github.com/user-attachments/assets/25e28970-20f0-495a-a10b-5988441ab7d7" />
<img width="1053" height="701" alt="image" src="https://github.com/user-attachments/assets/fb22b131-7d27-442d-ac02-e9f7fceb51fa" />
<img width="806" height="317" alt="image" src="https://github.com/user-attachments/assets/412202c7-cfb1-4dd4-8090-b143629fcfe8" />

---
---

##  Conclusion

This project demonstrates a complete **classification modeling workflow**, combining data analysis, predictive modeling, and business insights.

The results highlight how customer behavior and campaign history can be leveraged to improve marketing efficiency and decision-making.

---

##  Author

Muhammad Shoaib Inksar
Data Analyst | Machine Learning Enthusiast
