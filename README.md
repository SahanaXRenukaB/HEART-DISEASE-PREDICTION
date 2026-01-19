# HEART-DISEASE-PREDICTION

This project focuses on predicting the presence or absence of heart disease using data mining and machine learning techniques. The system analyzes patient clinical data and builds predictive models to support early diagnosis and decision-making in healthcare.

---

## Project Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection plays a crucial role in preventing severe complications and improving patient outcomes.  
This project applies supervised machine learning algorithms to classify patients into heart disease and non–heart disease categories based on medical attributes.

The project was developed as part of the **Data Mining Techniques (SWE2009)** course.

---

## Dataset Information

- Source: Kaggle – Heart Disease Dataset  
- Number of instances: **1025**
- Number of features: **14**
- Dataset type: Multivariate
- Target variable:
  - `1` – Absence of heart disease
  - `2` – Presence of heart disease

### Features include:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise induced angina
- ST depression (oldpeak)
- Slope of ST segment
- Number of major vessels
- Thalassemia

---

## Algorithms Used

The following machine learning models were implemented and compared:

- K-Nearest Neighbors (KNN)
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Neural Network
- AdaBoost (Ensemble Model)

---

## Methodology

1. Importing required libraries
2. Loading and understanding the dataset
3. Data sanity check and preprocessing
4. Exploratory Data Analysis (EDA)
5. Correlation analysis
6. Feature importance using F-score
7. Model training and evaluation
8. Performance comparison using metrics

---

## Performance Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve

### Model Accuracy Comparison

| Model               | Accuracy |
|---------------------|----------|
| KNN                 | 0.7317   |
| Naive Bayes         | 0.8000   |
| Logistic Regression | 0.7853   |
| Neural Network      | 0.7512   |
| SVM                 | 0.6829   |
| AdaBoost            | 0.8927   |

✅ **Best Model: AdaBoost (Accuracy = 89.27%)**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Results and Insights

- Ensemble learning significantly improved prediction accuracy
- Features such as chest pain type, maximum heart rate, and oldpeak strongly influenced predictions
- AdaBoost outperformed individual classifiers

---

## Conclusion

This project demonstrates the effectiveness of data mining and machine learning techniques in predicting heart disease. Ensemble models such as AdaBoost provide higher accuracy and robustness, making them suitable for healthcare decision-support systems.

---

## Future Enhancements

- Integrate the model into a web application
- Use deep learning models for improved accuracy
- Apply feature selection and dimensionality reduction techniques
- Test on larger and more diverse datasets
