This code is related to the implementation of a master’s thesis conducted under my supervision, 
entitled “Design and Implementation of a Machine Learning-Based Model for Referring Patients to Home Care Service Providers.” 
The thesis was carried out by Mr. Mehdi Heidarizadeh in the year 1405.


Abstract
Title: Presenting an Intelligent Machine Learning-Based Model for Optimal Referral of
Patients to Home Care Centers
Introduction: With the increasing elderly population and the prevalence of chronic diseases,
the need for home care services has become a key pillar of healthcare systems worldwide,including Iran. Accurate and timely referral of patients to home care centers plays a crucial
role in improving patients’ quality of life, reducing healthcare costs, minimizing unnecessary
hospital admissions, and preventing readmissions. However, the traditional referral process is
often fraught with challenges such as uncertainty, human error, and lack of standardization.
This research aims to present an intelligent Machine Learning (ML)-based model for
optimizing the referral process of patients requiring care to appropriate home care centers.
Methodology: In this study, real-world data collected from patients at Isfahan University of
Medical Sciences were utilized. First, a set of clinical, demographic, and medical history
features relevant to the need for home care were identified and extracted. Due to the inherent
data imbalance (the number of patients requiring home care compared to others), data
balancing techniques, specifically Synthetic Minority Over-sampling Technique (SMOTE),
were employed to improve model performance. Subsequently, four ML algorithms, including
Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and
Gradient Boosting Classifier, were trained and evaluated for predicting the probability of a
patient needing home care. Model performance was compared using standard evaluation
metrics such as Accuracy, Precision, Recall, and F1-Score, with a particular focus on the
minority class (patients requiring home care).
Findings: The results indicated that data imbalance significantly negatively impacted model
performance, especially in identifying patients needing home care. The application of the
SMOTE technique led to a substantial improvement in the Recall and F1-Score metrics for
the minority class across all investigated models. After applying SMOTE, Logistic
Regression and Gradient Boosting Classifier models demonstrated the best overall
performance, achieving high F1-Scores (59.0 and 59.0 for the minority class, respectively).
The SVM model also showed significant improvement post-SMOTE, and the KNN model
experienced a notable enhancement in the Recall metric for the minority class. These findings
suggest that ML models, particularly when using balanced data, possess a high capability in
accurately identifying patients requiring home care.
Discussion and Conclusion: This research has demonstrated the potential of the ML approach
in providing an intelligent and efficient referral system for patients needing home care. The
developed models hold significant promise for integration into clinical decision support
systems, assisting physicians and healthcare providers in making faster and more accurate
decisions. This can lead to improved quality of care, reduced healthcare costs, and increased
patient satisfaction. Although this study has limitations such as data volume and the need for
validation in other centers, its results paint a promising outlook for the application of artificial
intelligence in optimizing healthcare processes in Iran.
Keywords: Machine Learning, Home Care, Patient Referral, Data Imbalance, SMOTE,
Predictive Modeling, Clinical Decision Support System, Digital Health
