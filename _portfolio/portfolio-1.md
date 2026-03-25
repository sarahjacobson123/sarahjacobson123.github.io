---
title: "Heart Attack Risk Prediction"
excerpt: "Developed and evaluated multiple machine learning models to predict heart attack risk, 
identifying key predictors and comparing model performance using real-world healthcare decision metrics.<br/><img src='/images/heartattack.png'>"
collection: portfolio
---
In this project, I used patient clinical data to predict whether a patient was at risk of an exercise-induced heart attack. I built and compared three classification models — **KNN, logistic regression, and decision tree** — and selected models based on cross-validated performance using **ROC AUC** and other classification metrics. I also evaluated the models using **precision, recall, specificity, confusion matrices, validation data, and Cohen’s Kappa** to understand performance from both a predictive and practical decision-making perspective.

One of the most valuable parts of this project was going beyond model accuracy and thinking about **business and operational context**. For example, I considered which model would be best if a hospital wanted to minimize missed high-risk patients, prioritize limited bed space, study root causes of heart attacks, or compare algorithm predictions with doctor diagnoses. This helped show how model selection depends not just on performance, but also on the real-world costs of different types of errors.

My analysis showed that **logistic regression performed especially well across multiple scenarios**, with strong recall and precision, while the **decision tree was particularly useful for interpretability**. Across the models, some of the most important predictors were **chest pain type, maximum heart rate achieved during exercise, sex, and age**.


This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  
