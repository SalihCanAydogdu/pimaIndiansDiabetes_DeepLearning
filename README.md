# Detection of Diabetes Using Deep Learning

## Project Description
This project aims to develop a deep learning model for detecting diabetes using clinical and physical data from the Pima Indians Diabetes dataset. By leveraging various deep learning techniques, the goal is to create an effective system for early diagnosis of diabetes.

## Dataset
- **Pima Indians Diabetes Dataset**: This dataset contains 768 observations of individuals, including information such as glucose levels, blood pressure, BMI, and whether the individual has diabetes (outcome).

## Preprocessing
1. Dataset balancing methods applied to address class imbalance, including SMOTE, Instance Hardness Threshold, and Edited Nearest Neighbors.
2. Data cleaned and normalized for effective model training.

## Machine Learning Models
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**
- **LightGBM**
- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Unit)**

## Ensemble Models
- **CNN + LSTM**
- **CNN + GRU**
- **CNN + LSTM + GRU**

## Results
- The best performing model was **Random Forest** with the **Instance Threshold** balancing method, achieving an accuracy of **92.66%**.
- Ensemble models provided robust performance but were not significantly better than Random Forest for this dataset.

## Conclusion
This project demonstrates that deep learning techniques, particularly Random Forest combined with effective dataset balancing, can achieve high accuracy in diagnosing diabetes. Future work could focus on further refining models and testing on larger datasets.

## References
- [Pima Indians Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [SMOTE for Imbalanced Classification](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/)
- Additional academic papers and resources on diabetes prediction and dataset balancing methods.
