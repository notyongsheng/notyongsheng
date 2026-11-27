
# 👋 Hi, I'm Yong Sheng!

I'm a **Data Science and Analytics undergraduate at the National University of Singapore (NUS)** with interests in machine learning, statistical modelling and applied data analytics.

I'm particularly interested in building end-to-end machine learning systems that translate data into actionable business decisions, from feature engineering and model development to deployment and monitoring.

🔍 **Open to internship opportunities in Data Science, Data Analytics and Machine Learning.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ng-yong-sheng)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:E1398069@u.nus.edu)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/notyongsheng/)

---

## ⭐ Featured Projects

### 💳 Real-Time Transaction Fraud Detection System

End-to-End ML Engineering · DSA3101 Team Project · AY 2026/27

Collaboratively developed and deployed a real-time fraud decisioning system integrating supervised machine learning, transaction velocity, behavioural profiling and risk-based decision-making.

The system processes incoming transactions through AWS SQS, generates fraud risk scores using a Histogram-based Gradient Boosting classifier, and combines behavioural signals to determine whether to accept, flag for review or block a transaction.

**My Contributions:**

- Developed two feature selection profilers, evaluating **428 candidate features and selecting 311** based on training-only fraud signal, feature availability and redundancy.
- Implemented frozen, versioned feature contracts to prevent data leakage during feature selection and maintain training-inference consistency.
- Implemented correlation-based redundancy pruning while preserving informative missingness patterns.
- Built automated monitors to verify that offline feature profilers remained outside the live inference path across **100,000 unique transaction decisions**.
- Investigated seven tail-latency breaches using a reproducible Python analysis script, identifying isolated recurring spikes rather than sustained system degradation.
- Owned repository integration and merge queue management, authored feature profiler specifications and documented reproducible Docker deployment procedures on AWS.

**Team Results:**

- Increased fraud capture from **53.95% to 65.00% (+11.05 percentage points)** in a paired v1 versus v2 pipeline comparison on 40,034 labelled validation transactions.
- Increased the proportion of fraudulent transactions among reviewed cases from **13.74% to 22.40%**, while reducing review workload by **28.3%**.
- Achieved **41.6 ms p99 per-transaction decision latency** on an AWS t3.large instance, measured from message retrieval to decision readiness across 100,000 unique transactions in a course-provided stream, with **99.993% completed within 400 ms**.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, SQL, AWS SQS, AWS S3, Docker, Git, Pytest

[Explore all my repositories](https://github.com/notyongsheng?tab=repositories)

---

### 📊 Machine Learning & Data Analytics Projects

| Project | Description & Key Results | Technologies |
|---|---|---|
| **HDB Rental Price Prediction** | Developed a predictive ML pipeline using **172,442 rental records (2021–2025)**. Compared Linear Regression, Random Forest and XGBoost with cross-validation and hyperparameter optimisation. XGBoost achieved a test RMSE of **S$483.68**, a **6.02% reduction** over the linear baseline. | Python, Pandas, Scikit-learn, XGBoost |
| **HDB Resale Price Modelling** | Modelled **2,546 HDB resale transactions** using multiple regression, Weighted Least Squares and Ridge regularisation to address heteroscedasticity and multicollinearity. Estimated that properties in the **Outside Central Region were valued 13.37% lower than those in the Core Central Region**, holding other modelled property characteristics constant. | R, Regression Modelling, Statistical Inference |
| **Heart Disease Classification** | Compared K-Nearest Neighbours, Decision Tree and Logistic Regression classifiers using stratified 5-fold cross-validation, feature selection and hyperparameter optimisation. Selected a Decision Tree classifier achieving **81.1% recall, 83.3% precision and 0.855 ROC-AUC**, balancing sensitivity against false-positive predictions. | R, Classification, Statistical Learning |
| **Global Tourism & Air Travel Analytics** | Integrated holiday calendars and monthly air passenger data across **90 countries (2010–2018)**. Identified a weak negative correlation between holiday counts and passenger volume (**r = −0.219**), with average international passenger volumes exceeding domestic volumes only in July and August. | Python, Pandas, Matplotlib, Seaborn, Plotly |


---

## 🔭 Technical Interests

<img align="right" width="250" src="https://leetcard.jacoblin.cool/notyongsheng?theme=dark&font=Karla&ext=heatmap" alt="LeetCode statistics" />

- **Applied Machine Learning:** Feature selection, gradient boosting, hyperparameter optimisation and classification threshold selection.
- **ML Engineering:** Versioned model artefacts, reproducible training pipelines, real-time inference and model monitoring.
- **Statistical Modelling:** Regression diagnostics, regularisation, hypothesis testing and model interpretability.
- **Data Engineering:** Data integration, SQL, transaction processing and cloud-based ML workflows.
- **Problem Solving:** Data structures and algorithms through [LeetCode](https://leetcode.com/u/notyongsheng/).

<br clear="all" />

---


## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Data Science & Machine Learning**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)

**Data Visualisation & Business Intelligence**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)


**Development Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Cloud & Deployment — Project Exposure**

![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS SQS](https://img.shields.io/badge/AWS_SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)


---

## 📫 Let's Connect

I'm open to internship opportunities, collaborations and conversations about data science and machine learning.

- **LinkedIn:** [Ng Yong Sheng](https://www.linkedin.com/in/ng-yong-sheng)
- **Email:** [E1398069@u.nus.edu](mailto:E1398069@u.nus.edu)

Thanks for stopping by! 😊
