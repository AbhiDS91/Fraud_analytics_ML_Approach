# Advanced Transaction Anomaly Detection 

This comprehensive project is dedicated to unmasking fraudulent financial transactions using cutting-edge AI and Machine Learning. This repository showcases a robust, end-to-end pipeline engineered for practical, production-ready fraud detection in real-world scenarios.

##  Project Objective

Our mission is to **design, train, and rigorously evaluate machine learning models capable of automatically identifying fraudulent activity.** By doing so, we aim to significantly reduce the need for manual review processes and mitigate financial risk for institutions.

##  Core Features & Technologies

This project highlights a full spectrum of skills and techniques crucial for building effective fraud detection systems:

###  Python Data Science Ecosystem
Leveraging the power of:
* "pandas" for data manipulation
* "numpy" for numerical operations
* "matplotlib" & "seaborn" for insightful visualizations
* "scikit-learn" for machine learning algorithms and utilities

###  Data Engineering & Preparation
* **Smart Missing Value Handling:** Strategically addressing gaps in the dataset.
* **Feature Scaling & Encoding:** Transforming raw features for optimal model performance.
* **Tackling Class Imbalance (Undersampling):** A critical step to handle the rarity of fraud cases and prevent model bias.

###  Feature Engineering & Selection
* **Correlation Analysis:** Understanding relationships between features.
* **Outlier Management:** Identifying and treating extreme data points.
* **Feature Importance Extraction:** Uncovering which attributes are most indicative of fraud.

###  Machine Learning Algorithms
Implementing and refining powerful classification models:
* **Random Forest Classifier:** A robust ensemble method known for its accuracy.
* **Decision Tree:** Used as a baseline for comparison and interpretability.
* **Hyperparameter Tuning:** Fine-tuning model parameters (`n_estimators`, `max_depth`) for peak performance.

###  Comprehensive Model Evaluation
Measuring effectiveness with fraud-specific metrics:
* **Confusion Matrix:** A detailed view of true positives, true negatives, false positives, and false negatives.
* **Precision, Recall, F1-Score:** Essential for evaluating performance on imbalanced datasets.
* **ROC-AUC:** Demonstrating strong discrimination capability, especially for imbalanced data.

###  Model Interpretability & Insights
* **Feature Ranking:** Understanding which features drive the model's decisions.
* **Trade-off Visualization (Precision vs. Recall):** Providing a clear picture for stakeholders to balance false alarms against missed fraud.

---

##  The Dataset

The core of this project relies on the **Kaggle Credit Card Fraud Detection Dataset**.

* **Size:** 284,807 transactions.
* **Fraud Rarity:** Only 492 of these transactions are fraudulent (approximately 0.17%), making it a highly imbalanced dataset.
* **Key Features:**
    * Time: Transaction timestamp.
    * Amount: Transaction value.
    * V1–V28: Anonymized features (PCA components).
    * Class: The binary label (0 for legitimate, 1 for fraud).

---

##  Achieved Outcomes & Performance Metrics

This project not only builds a model but also validates its real-world impact:

* **Significant Uplift in Fraud Detection:**
    * Our **Random Forest Classifier** consistently achieved **ROC-AUC scores above 0.97**, demonstrating exceptional ability to distinguish between fraudulent and legitimate transactions.
* **Balanced Precision & Recall:**
    * The model achieved a **Recall > 0.90 for the fraud class**, indicating it successfully captured a large majority of fraudulent transactions with minimal false negatives.
* **Improved Identification:**
    * Through rigorous evaluation using confusion matrices and F1-scores, the project shows **clear improvements in fraud identification** compared to simpler baseline models like the Decision Tree.
* **Visualized Trade-offs:**
    * Interactive visualizations of the **Precision vs. Recall trade-off** enable stakeholders to make informed decisions, balancing the desire to catch more fraud against the cost of false alarms.
* **Reusable & Scalable Pipeline:**
    * The well-structured notebook and modular code provide a **ready-to-use pipeline** for future model enhancements and potential deployment.

---

##  Explore the Notebook

Dive into the details and follow the entire fraud detection journey by exploring the main notebook:

* [`FraudDetection_Modeling.ipynb`](FraudDetection_Modeling.ipynb)
