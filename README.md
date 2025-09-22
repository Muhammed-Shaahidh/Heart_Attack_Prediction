Overview

This project aims to build a simple AI/ML-based bot for predicting the risk of heart attacks (or heart disease) using machine learning techniques. The focus is on the data preprocessing step of the ML pipeline, which includes handling missing values, data cleaning, feature scaling, and preparing the dataset for model training. The preprocessed data will be used to train models like logistic regression or random forests for prediction.


Dataset Details

1. Filename: data.csv
2. Rows: 282 patient records
3. Columns: 14 medical attributes
4. Target Variable: num (0 = no heart disease, 1 = heart disease)

5. Features:
      1. age: Age of the patient.
      2. sex: Gender (1 = male, 0 = female).
      3. cp: Chest pain type (1-4 values).
      4. trestbps: Resting blood pressure.
      5. chol: Serum cholesterol in mg/dl.
      6. fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
      7. restecg: Resting electrocardiographic results (0-2 values).
      8. thalach: Maximum heart rate achieved.
      9. exang: Exercise-induced angina (1 = yes, 0 = no).
      10. oldpeak: ST depression induced by exercise relative to rest.
      11. slope: Slope of the peak exercise ST segment (1-3 values).
      12. ca: Number of major vessels (0-3) colored by fluoroscopy.
      13. thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
      14. num: Target variable (0 = no heart disease, 1 = heart disease present).

6. Missing Values: Present (marked as "?") 


Group Members:

1. IT24104096 - Kaluarachchi S.S
2. IT24102659 - Senevirathna K.S.D.B
3. IT24103086 - Wanasundara W.A.A.L
4. IT24103607 - Lakshani K.A.A
5. IT24102908 - Galapitage S.A
6. IT24610823 - Shaahidh M.W.M


How to Run the Code

01. Clone the Repository
02. Install dependencies
03. Run the Preprocessing Script
