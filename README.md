# Diabetes Prediction using Machine Learning  

## Project Overview  
This project aims to build a **predictive model** for diabetes detection using various **machine learning algorithms**. We leverage the **Pima Indians Diabetes Dataset**, preprocess the data, train multiple models, and evaluate their performance using key metrics.  

## Dataset  
The dataset contains **768** records with **8 health-related features** and an outcome variable (**0 = No Diabetes, 1 = Diabetes**).  

### Features  
- `Pregnancies` – Number of times pregnant  
- `Glucose` – Plasma glucose concentration  
- `BloodPressure` – Diastolic blood pressure (mm Hg)  
- `SkinThickness` – Triceps skin fold thickness (mm)  
- `Insulin` – 2-Hour serum insulin (mu U/ml)  
- `BMI` – Body mass index (weight in kg/(height in m)^2)  
- `DiabetesPedigreeFunction` – Diabetes hereditary risk factor  
- `Age` – Age in years  
- `Outcome` – 1 (Diabetic) or 0 (Non-diabetic)  

## Project Workflow  

### 1️⃣ Data Preprocessing  
✔ Checked for missing values and handled them accordingly  
✔ Converted data types where necessary  
✔ Standardized numerical features for better model performance  
✔ Split dataset into **training (80%)** and **testing (20%)**  

### 2️⃣ Model Training & Evaluation  
We trained and evaluated **four machine learning models**:  

- **Random Forest Classifier**  
- **K-Nearest Neighbors (KNN)**  
- **Naïve Bayes Classifier**  
- **Gradient Boosting Classifier**  

## Performance Metrics  

| Model                | Accuracy | Precision | F1 Score | Recall | ROC AUC  |
|----------------------|----------|-----------|----------|--------|---------|
| Random Forest       | **72.46%** | 70.27%    | 57.78%   | 49.06% | 0.8064  |
| K-Nearest Neighbors | **73.19%** | 71.05%    | 59.34%   | 50.94% | 0.7491  |
| Naïve Bayes         | **71.01%** | 65.12%    | 58.33%   | **52.83%** | 0.7809  |
| Gradient Boosting   | **73.91%** | **72.97%** | **60.00%** | 50.94% | **0.8173**  |

### Key Insights  
✅ **Gradient Boosting performed best** with highest accuracy (**73.91%**) and ROC AUC (**0.8173**)  
✅ **Naïve Bayes had the highest recall** (52.83%), making it useful for detecting positive diabetes cases  
✅ **KNN & Random Forest had good overall performance**  

## Next Steps  
🚀 **Hyperparameter tuning** to improve model accuracy  
🚀 **Feature selection & engineering** for better predictions  
🚀 **Deploy the best model** as a web app or API  
🚀 **Collect more data** to improve generalization  


