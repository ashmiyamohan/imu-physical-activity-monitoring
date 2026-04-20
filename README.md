# IMU Physical Activity Monitoring

## Overview

This project focuses on human activity recognition using IMU sensor data and heart rate measurements. The goal is to analyze physical activities and build machine learning models to classify them effectively.

## Dataset

* Multi-sensor IMU data (hand, chest, ankle)
* Heart rate measurements
* Data collected from multiple subjects

Dataset is not included due to size limitations.

## Techniques Used

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* PCA (Dimensionality Reduction)
* Machine Learning Models:

  * Logistic Regression
  * Random Forest

## Results

* Logistic Regression Accuracy: ~87%
* Random Forest Accuracy: ~96%

## Key Insights

* Heart rate increases with activity intensity
* Temperature alone is not a strong predictor
* PCA reduced features to 22 components while retaining 94% variance

## Limitations

* Possible overfitting in Logistic Regression
* No subject-independent validation
* Limited hyperparameter tuning

## Future Improvements

* Apply feature scaling and tuning
* Improve model generalisation
* Deploy model for real-time predictions

## Conclusion

Random Forest with PCA performed best, achieving high accuracy and demonstrating strong capability in handling complex sensor data.

---

Developed as part of Machine Learning learning journey

