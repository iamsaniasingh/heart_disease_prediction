This project marks my first step into the world of machine learning. I developed a classification model using logistic regression to predict the likelihood of heart disease based on patient data. The entire project is based on a historical dataset—there is no real-time user input or deployment involved.

🧰 Tools & Technologies Used
Python – Programming language used for the entire project

Pandas – For data loading, cleaning, and manipulation

NumPy – For numerical operations and array handling

scikit-learn (sklearn) – For model building, preprocessing, training, and evaluation

These tools made it easy to handle data, build the model, and evaluate the results efficiently.

I used the Heart Disease Dataset, which includes 303 patient records and 14 health-related features. The goal is to predict the target column:

1: Heart disease present

0: No heart disease
| Feature    | Description                                       |
| ---------- | ------------------------------------------------- |
| `age`      | Age of the patient                                |
| `sex`      | Sex (1 = male, 0 = female)                        |
| `cp`       | Chest pain type (0–3)                             |
| `trestbps` | Resting blood pressure                            |
| `chol`     | Serum cholesterol                                 |
| `fbs`      | Fasting blood sugar > 120 mg/dl (1 = yes, 0 = no) |
| `restecg`  | Resting ECG results                               |
| `thalach`  | Maximum heart rate achieved                       |
| `exang`    | Exercise-induced angina                           |
| `oldpeak`  | ST depression from exercise                       |
| `slope`    | Slope of the ST segment                           |
| `ca`       | Number of major vessels seen in fluoroscopy       |
| `thal`     | Thalassemia status                                |
| `target`   | 1 = Heart disease, 0 = No heart disease           |



 What I Learned
How to preprocess and prepare real-world data for ML models.

How logistic regression works for binary classification.

The importance of evaluation metrics beyond just accuracy.

The end-to-end ML workflow from data to prediction.

