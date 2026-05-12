# Machine Learning Driven Predictive Analysis of Postpartum Hemorrhage and Maternal Morbidity(Syentic data trained model)

Research Paper Presentation — ICASDA 2026
Kristu Jayanti University, Bangalore

---

## Overview

This research focuses on the application of machine learning and biostatistical analysis for the early prediction of Postpartum Hemorrhage (PPH) and maternal morbidity.

Postpartum Hemorrhage remains one of the leading causes of maternal mortality worldwide, especially in low and middle-income countries where access to timely obstetric care is limited. Traditional clinical assessment methods often fail to identify high-risk cases accurately due to the complex and multifactorial nature of maternal health conditions.

This study explores how data-driven predictive systems can support early intervention and improve maternal healthcare outcomes.

---

## Research Objective

The primary objective of this research is to develop a predictive framework capable of identifying high-risk PPH cases before delivery using clinical, demographic, and obstetric parameters.

The study aims to:

* Analyze major causes and contributing factors of PPH
* Apply machine learning techniques for predictive analysis
* Compare predictive performance of different models
* Improve early clinical decision-making in maternal healthcare

---

## Dataset Parameters

The study considers maternal and obstetric variables including:

* Maternal age
* Hemoglobin levels
* Blood pressure
* Delivery mode
* Previous C-section history
* Labour duration
* Placenta-related complications
* Fetal weight
* Pregnancy type (single/twin/triplet)
* BMI and maternal health indicators

---

## Methodology

The research methodology includes:

### Data Processing

* Data cleaning
* Missing value handling
* Feature scaling
* Categorical encoding

### Model Training

* 80/20 train-test split
* 5-fold cross-validation
* Imbalanced data handling using `scale_pos_weight`

### Machine Learning Models

* Logistic Regression
* Random Forest
* XGBoost

---

## Why XGBoost Was Selected

XGBoost was chosen due to:

* Strong performance on imbalanced medical datasets
* Sequential error correction capability
* High predictive accuracy
* Better feature importance analysis
* Ability to capture nonlinear relationships

The model demonstrated superior predictive performance compared to traditional statistical methods.

---

## Model Performance

| Model               | ROC-AUC Score |
| ------------------- | ------------- |
| Logistic Regression | 0.78          |
| Random Forest       | 0.85          |
| XGBoost             | 0.89          |

The results indicate that XGBoost provides the highest predictive capability for identifying high-risk PPH cases.

---

## Key Findings

* Machine learning models can significantly improve early detection of PPH risk.
* Important predictive factors include placenta previa, high BMI, neonatal weight, episiotomy, and IVF pregnancies.
* Hybrid approaches combining statistical analysis and machine learning improve reliability and interpretability.
* Predictive systems can support clinical decision-making and reduce preventable maternal deaths.

---

## Global Healthcare Context

According to WHO reports referenced in this study:

* Postpartum Hemorrhage contributes to nearly one-quarter of maternal deaths globally.
* Approximately 260,000 women die annually due to pregnancy and childbirth complications.
* Developing countries face the highest burden due to limited healthcare infrastructure and delayed interventions.

---

## Potential Applications

This research can contribute toward:

* Clinical decision support systems
* AI-assisted maternal healthcare monitoring
* Risk stratification during labor and delivery
* Integration into Electronic Health Record (EHR) systems
* Early emergency intervention planning

---

## Research Significance

The study demonstrates the potential of AI and machine learning in addressing critical maternal healthcare challenges through predictive analytics and data-driven intervention systems.

The work also highlights how computational intelligence can assist healthcare professionals in improving patient outcomes and reducing maternal mortality.

---

## Technologies & Concepts Used

* Machine Learning
* XGBoost
* Logistic Regression
* Random Forest
* Biostatistics
* Predictive Analytics
* Healthcare Data Analysis

---

## Academic Presentation

Presented at:
ICASDA 2026
Kristu Jayanti University
Bangalore, Karnataka

---

## Author

Anil Kumar Devaraj
BSc Mathematics, Statistics & Computer Science
Kristu Jayanti University

Research Interests:

* Artificial Intelligence
* Healthcare AI
* Predictive Systems
* Statistical Learning
* Medical Data Analytics

---

## Final Note

This research reflects an effort to combine artificial intelligence, statistics, and healthcare analytics to support safer maternal care systems and improve early clinical intervention strategies.
