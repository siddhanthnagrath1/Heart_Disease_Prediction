# Heart Disease Prediction

This project builds a machine learning model to predict heart disease using the UCI Heart Disease dataset.

## 📊 Dataset
The dataset contains patient health information such as age, cholesterol level, blood pressure, and other medical attributes.

## 📌 Features Used

| Column     | Description                                 |
|------------|---------------------------------------------|
| age        | Age of the patient                          |
| sex        | Sex (1 = male, 0 = female)                  |
| cp         | Chest pain type (0–3)                       |
| trestbps   | Resting blood pressure (in mm Hg)           |
| chol       | Serum cholesterol (in mg/dl)                |
| fbs        | Fasting blood sugar > 120 mg/dl (1 = true)  |
| restecg    | Resting electrocardiographic results (0–2)  |
| thalach    | Maximum heart rate achieved                 |
| exang      | Exercise-induced angina (1 = yes, 0 = no)   |
| oldpeak    | ST depression induced by exercise           |
| slope      | Slope of the ST segment (0–2)               |
| ca         | Number of major vessels (0–3) colored by fluoroscopy |
| thal       | Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect) |
| target     | Diagnosis of heart disease (1 = present, 0 = absent) |
## ⚙️ Models Applied
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

## 🧪 Evaluation
- Cross-validation (10-fold)
- Accuracy plotted for different values of K in KNN

## 📈 Results
| Model               | Accuracy |
|--------------------|----------|
| KNN (k=12)          | 0.84     |
| Random Forest (n=10)| 0.87     |

## 📎 How to Run
1. Clone the repository
2. Upload `heart.csv` in your working directory
3. Open `Heart Disease Prediction.ipynb` in Google Colab or Jupyter Notebook
4. Run cells step by step



## 🧑‍💻 Author
Siddhanth Nagrath
